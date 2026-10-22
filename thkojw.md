代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gt2grerinar.html

user_id INT NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gt2vsrohvtk.html

amount DECIMAL(10, 2),
来源：http://dali.dianchejie.cn/Article/details/gt2ukzydaxz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.svipenyu.cn/Article/details/gt2ktfcoilh.html

);
来源：http://dali.xinyue.icu/Article/details/gt2moywpkkr.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gt2yoapaadb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zycfv.cn/Article/details/gt2snuxeoid.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gt2osceogjw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gt2acyzwszg.html

[Q05] 重命名列
来源：http://dali.xylfe.cn/Article/details/gt2zgkwyaan.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gt2bibtrngx.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gt2aidlubmn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.c1oappe.top/Article/details/gt2menipxzh.html

[Q07] 删除表
来源：http://dali.quarkkingdee.top/Article/details/gt2lzpffkch.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenlongwang.top/Article/details/gt2tgwwkiiw.html

[Q08] 创建普通索引
来源：http://dali.9152youxi.cn/Article/details/gt2gemkovbg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gt2mutpixfy.html

[Q09] 创建唯一索引
来源：http://dali.quarkkingdee.top/Article/details/gt2hhpmkyth.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gt2tbqegtxq.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gt2gqzyzkws.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj202588.top/Article/details/gt2lbngjmwc.html

[Q11] 一次插入多行
来源：http://dali.redwolf501.top/Article/details/gt2gxdvucpd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btpqmpmo.html

[Q12] 插入后取自增 ID
来源：http://dali.guowangkeji.top/Article/details/gt2nkmwbnlb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tanke756.top/Article/details/gt2bkbchrvc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hammf.cn/Article/details/gt2bmbuaefl.html

[Q13] 忽略重复插入
来源：http://dali.guowangkeji.top/Article/details/gt2bxnsjpkr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258.top/Article/details/gt2mdhspdag.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gt2iusxnzae.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2tshexjdi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gt2giczhjbu.html

[Q15] 查询全部
来源：http://dali.jqgfzy.top/Article/details/gt2cgnuiulz.html

SELECT * FROM users;
来源：http://dali.yonumen.top/Article/details/gt2dgfouzes.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gt2qwtwnhqg.html

SELECT id, name FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2bspkhghi.html

[Q17] 条件查询
来源：http://dali.kuanghao11.cn/Article/details/gt2ldxofndb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.iojbl.cn/Article/details/gt2dbuncqev.html

[Q18] 模糊匹配
来源：http://dali.zdqjudy.top/Article/details/gt2qaejwdzy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldiexkrz.html

[Q19] 范围查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fizybdep.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.kuanghao11.cn/Article/details/gt2nowgnkqx.html

[Q20] IN 列表
来源：http://dali.bjfxy.top/Article/details/gt2qkwsopau.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigufen.top/Article/details/gt2jyaiyjpg.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2gcdbfbsr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gt2eplziejl.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gt2vbanpfdw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.smart0.xyz/Article/details/gt2zidgtczl.html

[Q23] 分页
来源：http://dali.meibo888.top/Article/details/gt2rwsungcz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gt2zcmpioqu.html

[Q24] 去重
来源：http://dali.dianchejie.cn/Article/details/gt2rpxczqjm.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2hnzwtkko.html

[Q25] 只取前 N 条
来源：http://dali.yueranfly.top/Article/details/gt2fclaphqd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2arehldhs.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gt2lugqxqaj.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2satkccde.html

[Q27] 条件计数
来源：http://dali.iojbl.cn/Article/details/gt2pojkwcbw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2ascqsbsh.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gt2xiuvijkc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2hyodmdvr.html

[Q29] 最大最小值
来源：http://dali.guowangkeji.top/Article/details/gt2xsyqradc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2egwebbdh.html

[Q30] 分组统计
来源：http://dali.nanxinkj.top/Article/details/gt2hnnqzfzl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gt2lqputnix.html

[Q31] 分组后过滤
来源：http://dali.jyoumei.cn/Article/details/gt2sbatwuhj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhengqikj.top/Article/details/gt2ugleidgw.html

[Q32] 分组拼接字符串
来源：http://dali.tian-w.cn/Article/details/gt2feaylscz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gt2rvotqifz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gt2gqyvukkq.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gt2vewfkuqs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.bjfxy.top/Article/details/gt2jbumzinm.html

[Q34] 每组取第一条
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vppvedot.html

SELECT * FROM (
来源：http://dali.nanxinkj.top/Article/details/gt2yftpbfhx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ppjwa.cn/Article/details/gt2qknswoni.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2yvdpcnvp.html

[Q35] 内连接
来源：http://dali.kuanghao11.cn/Article/details/gt2jkvhqgwc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2wyheoqtm.html

[Q36] 左连接
来源：http://dali.9152youxi.cn/Article/details/gt2thhxlqps.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gt2guxasqju.html

[Q37] 右连接
来源：http://dali.ybcxt.top/Article/details/gt2hmnnrmec.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.iojbl.cn/Article/details/gt2qmmclmhf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xziqi.cn/Article/details/gt2tkrlkmzt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cheryme.top/Article/details/gt2efrfefts.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gt2ihwkijto.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.havefunace.top/Article/details/gt2hmghdclh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gt2bhdpjcmk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gt2fyvrdgcx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhcwylkj.html

[Q41] 多表连接
来源：http://dali.tian-w.cn/Article/details/gt2iakmdafe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj202588.top/Article/details/gt2xhoozzrp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gt2cfteshws.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnxiangtu.top/Article/details/gt2yyiidhjp.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpoecpi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gt2zfttfiie.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gt2bockukuy.html

[Q43] 标量子查询
来源：http://dali.316326.xyz/Article/details/gt2wlvsqwlt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cdnleiting.top/Article/details/gt2mylqihfg.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbbiykgo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenlongwang.top/Article/details/gt2vvbodooi.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gt2msuteaqg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gt2mukjsfck.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhengqikj.top/Article/details/gt2qqopqzau.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gt2fqgauhpn.html

[Q47] 与平均值比较
来源：http://dali.xylfe.cn/Article/details/gt2vlrdnnqf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gt2uflwpbfw.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gt2yfqlspjb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gt2kfhgotda.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gt2quhamhmt.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gt2cqkukutz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gt2rdynqtot.html

[Q50] 批量更新
来源：http://dali.0kj1m.cn/Article/details/gt2gkzbesel.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gt2sqsuigyz.html

[Q51] 用子查询更新
来源：http://dali.sxryk.cn/Article/details/gt2khmklqds.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gt2hsqbsmbf.html

[Q52] 删除指定行
来源：http://dali.zhoulong.xyz/Article/details/gt2sivkgolh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2pygyodjr.html

[Q53] 按条件删除
来源：http://dali.316326.xyz/Article/details/gt2llvsxrsm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gt2yjhhtifx.html

[Q54] 清空表
来源：http://dali.yonumen.top/Article/details/gt2nggrdzfy.html

TRUNCATE TABLE logs;
来源：http://dali.snrcjt.cn/Article/details/gt2pftavjtr.html

[Q55] 排名（并列占位）
来源：http://dali.jlsjyb.cn/Article/details/gt2jjvtokpd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gt2grypcdrk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xinyue.icu/Article/details/gt2fpddbzaf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fzhhl.top/Article/details/gt2rfsvnqgb.html

[Q57] 行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otbqftof.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2ophkppxn.html

[Q58] 累计求和
来源：http://dali.yj20258.top/Article/details/gt2watkzurp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2qpcxxpcg.html

[Q59] 分组内累计
来源：http://dali.xuanzx.com/Article/details/gt2lkeltrok.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcydcoiy.html

[Q60] 取上一行 / 下一行
来源：http://dali.0kj1m.cn/Article/details/gt2ezjwhavm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdhsyjtf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2xzcnyjjn.html

[Q61] 移动平均
来源：http://dali.smart0.xyz/Article/details/gt2dwyziqit.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqzjbmfy.html

[Q62] 分组占比
来源：http://dali.hammf.cn/Article/details/gt2qetobbhj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2dqnanigr.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gt2oquenici.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhoulong.xyz/Article/details/gt2ljkirvru.html

[Q64] 提交事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2navgpsgf.html

COMMIT;
来源：http://dali.svipenyu.cn/Article/details/gt2rlzxvnoj.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gt2dfmhkfer.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gt2fvggtjpo.html

[Q66] 行锁查询
来源：http://dali.jianghu66.top/Article/details/gt2obkpwvym.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gt2uwywgfxx.html

[Q67] 设置隔离级别
来源：http://dali.sysykeji.top/Article/details/gt2jketixzu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gt2yidghbmy.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gt2kfebqxaw.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gt2gnhlxhld.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gt2nycmtnjp.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gt2beqhtwfc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmmanvas.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gt2buaahxee.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gt2smutmifk.html

[Q71] 查看建表语句
来源：http://dali.svipenyu.cn/Article/details/gt2qlursuxw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cashguo.top/Article/details/gt2fzaszvob.html

[Q72] 查看索引
来源：http://dali.jqgfzy.top/Article/details/gt2xbdpbklj.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2edicnsmg.html

[Q73] 查看表状态
来源：http://dali.meibo888.top/Article/details/gt2iliijeiv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fengsongda.top/Article/details/gt2rjdwcnzb.html

[Q74] 强制使用索引
来源：http://dali.hammf.cn/Article/details/gt2qnsaeoyq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gt2gufkynlg.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gt2akbzhgtb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2trskvuva.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jyoumei.cn/Article/details/gt2wyldifgp.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gt2hsfctjue.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmdudgpw.html

[Q77] 时间加减
来源：http://dali.andypj.xyz/Article/details/gt2gctgxvjq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sysykeji.top/Article/details/gt2kdkhsmxp.html

[Q78] 当前时间
来源：http://dali.hysaishi.cn/Article/details/gt2lrrjrfhg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdclupc.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gt2wabhjbpa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gt2mvtjgmog.html

[Q80] 字符串截取
来源：http://dali.zhongyouzk.top/Article/details/gt2ropkbdhr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2loosvawo.html

[Q81] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gt2wizojkie.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gt2dcfqkhhv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfjpxvre.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2ntwtllrd.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gt2lqgdawnn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2bznlyjdx.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gt2rbenlodl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dowyfcjy.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gt2agioxhvb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mirwdafb.html

[Q86] 读取 JSON 字段
来源：http://dali.yuanzhike.top/Article/details/gt2zaygdxyc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gt2gtxypkpz.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccknhmlw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yangfankeji.com/Article/details/gt2ycrisvtn.html

[Q88] 行转列（条件聚合）
来源：http://dali.redwolf501.top/Article/details/gt2qpefjdvt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tian-w.cn/Article/details/gt2kohyheho.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2ybcryazz.html

[Q89] 判断表是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2urkxtcpu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnqzz.top/Article/details/gt2qievxntb.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gt2msfrmroo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cdnleiting.top/Article/details/gt2mhcjhfkw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2wutswceg.html

R. Bash 专题
来源：http://dali.cashguo.top/Article/details/gt2sktksyfp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2lquxoyzg.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gt2qaqdbqyd.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gt2vntxmloz.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gt2hadxblbs.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gt2zdzvbmei.html

name="Tom"; echo "$name"
来源：http://dali.sweek.top/Article/details/gt2awtosjft.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gt2lfyhlfyy.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gt2hypvoetb.html

[R04] 位置参数
来源：http://dali.mhx1999.top/Article/details/gt2gtcjotda.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hfpthk.cn/Article/details/gt2mcgfvsjl.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gt2lubyuddm.html

name="${1:-default}"
来源：http://dali.zycfv.cn/Article/details/gt2szcyllmk.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2sdfykbqd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gt2diekwhon.html

[R07] if 判断文件
来源：http://dali.chenlongwang.top/Article/details/gt2lakefqwe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yongpay.top/Article/details/gt2pibwzuyi.html

[R08] 数值比较
来源：http://dali.sufxvd.cn/Article/details/gt2kqecigmp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpdhhovu.html

[R09] 字符串比较
来源：http://dali.jyoumei.cn/Article/details/gt2rrgtbbvr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hfpthk.cn/Article/details/gt2nrbzerle.html

[R10] 正则匹配
来源：http://dali.snrcjt.cn/Article/details/gt2dloksmnm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.iojbl.cn/Article/details/gt2aklmcuqd.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gt2yzqakzib.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gt2mqxlyyaf.html

start) echo "启动" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2xiepzlpv.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2coahviev.html

*)     echo "未知命令" ;;
来源：http://dali.shzxlz.cn/Article/details/gt2yizbrzpd.html

esac
来源：http://dali.mhx1999.top/Article/details/gt2hdpumxkp.html

[R12] for 遍历文件
来源：http://dali.andypj.xyz/Article/details/gt2cmgxiilw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gt2broufbda.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gt2tqgcpiqg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2xknfewfp.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gt2djruyywx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gt2piqrgnhh.html

[R15] while 逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2peoyyfpg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gt2iuctnctm.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxbfhyan.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gt2owcgpkbo.html

[R17] 数组定义与取值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkkwbhtz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.birdmap.top/Article/details/gt2hapqbkgz.html

[R18] 遍历数组
来源：http://dali.redwolf501.top/Article/details/gt2dvtvurhv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gt2vfxitkrk.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gt2hkxsibwz.html

echo "${#arr[@]}"
来源：http://dali.zhixingplan.top/Article/details/gt2zlirdbjd.html

[R20] 关联数组（字典）
来源：http://dali.sysykeji.top/Article/details/gt2itzarkmv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gt2pnpunygi.html

[R21] 字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gt2unqahizp.html

echo "${#s}"
来源：http://dali.yvedp.cn/Article/details/gt2lazsmvjh.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gt2gmhnsaic.html

echo "${s:0:5}"
来源：http://dali.bjfxy.top/Article/details/gt2rnbkzqnq.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gt2lunucwtl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gt2ginhfxlr.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2khosrmbe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnxiangtu.top/Article/details/gt2lnvmmnpd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gt2ogezrkzz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gt2pjfqjihc.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gt2yhcsywbx.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivtzslqr.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gt2qknosqcn.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gt2rwsvqoer.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tsuqkdpq.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gt2gkacntgt.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gt2ipnlpyhz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gotoacloud.top/Article/details/gt2pwzyyvad.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gt2bfwvphpm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gt2dxmclqye.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2edzmhqah.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gt2xghnuets.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gt2pplosgtm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gt2erbaiyey.html

[R33] 捕获错误并提示行号
来源：http://dali.hammf.cn/Article/details/gt2lanpnzle.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gt2jttrvhnj.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gt2bbvezrmb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gt2pyiohatc.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gt2kgjzbrgd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aikmoszn.html

[R36] 并发执行多个任务
来源：http://dali.jinqigufen.top/Article/details/gt2rnokktln.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhixingplan.top/Article/details/gt2rxexeiud.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gt2zvpizhuk.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gt2qxbtkmdo.html

[R38] 管道串联
来源：http://dali.jqgufenzy.top/Article/details/gt2ptjwvygd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sxryk.cn/Article/details/gt2edxrhkhv.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gt2tzmwjbkr.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gt2jgvgjgre.html

[R40] 追加写日志
来源：http://dali.cucudq.cn/Article/details/gt2ltpdvmyy.html

echo "log" >> out.log
来源：http://dali.cqqwz.cn/Article/details/gt2bmmiahdy.html

[R41] 丢弃输出
来源：http://dali.redwolf501.top/Article/details/gt2cmclltyg.html

cmd >/dev/null 2>&1
来源：http://dali.9152youxi.cn/Article/details/gt2ffeemcui.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gt2riglwopq.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2cbsyljtd.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gt2sgkdxzyt.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gt2ychegwrt.html

[R44] 按修改时间查找
来源：http://dali.vqdsnc.cn/Article/details/gt2lmnbsapa.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gt2siuprdpg.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gt2iwdmtcss.html

find . -name "*.tmp" -delete
来源：http://dali.jianghu66.top/Article/details/gt2lkolzgeu.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gt2wugvctng.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yueranfly.top/Article/details/gt2tqncqspv.html

[R47] sed 单行替换
来源：http://dali.guannengcc.top/Article/details/gt2umuypyhj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gt2wesnboxq.html

[R48] awk 取指定列
来源：http://dali.sxryk.cn/Article/details/gt2nmtkyvcs.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2fbjpfuqw.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gt2nhysprlf.html


<!-- 参考信息 -->