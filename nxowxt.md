代发 wailian999

);
来源：http://dali.jqgfzy.top/Article/details/gt2ynwzigjy.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gt2afzvjyld.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daxiang520.top/Article/details/gt2fwmjjfao.html

[Q04] 修改列类型
来源：http://dali.shuidangran.top/Article/details/gt2myyfewvw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zycfv.cn/Article/details/gt2abbnupxp.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gt2oxpjrsdy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ybcxt.top/Article/details/gt2qupfgiyj.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gt2woqoulnp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.bjfxy.top/Article/details/gt2gmkzlazy.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gt2gyjlitzm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangdashe.top/Article/details/gt2abbbvhbn.html

[Q08] 创建普通索引
来源：http://dali.smart0.xyz/Article/details/gt2nydrmnvi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gt2yahmzkab.html

[Q09] 创建唯一索引
来源：http://dali.birdmap.top/Article/details/gt2pziwxaji.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gt2blyylcxp.html

[Q10] 插入单行
来源：http://dali.fengsongda.top/Article/details/gt2chappmgs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gt2aollcljm.html

[Q11] 一次插入多行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xuyzjzys.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gt2ehzjasle.html

[Q12] 插入后取自增 ID
来源：http://dali.hfpthk.cn/Article/details/gt2ddvsqlxo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.havefunace.top/Article/details/gt2cxuyzvzs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yonumen.top/Article/details/gt2zcgwhcgn.html

[Q13] 忽略重复插入
来源：http://dali.meibo888.top/Article/details/gt2bxyrjgby.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gt2vfijynym.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gt2bclhgqgs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sweek.top/Article/details/gt2ngvhhbwv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cdnleiting.top/Article/details/gt2fdodmerx.html

[Q15] 查询全部
来源：http://dali.316326.xyz/Article/details/gt2jzznzoqd.html

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2ftgzmppe.html

[Q16] 查询指定列
来源：http://dali.chenlongwang.top/Article/details/gt2qwnqubni.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2vbuulixh.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gt2yusdunfn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gt2kcwlriip.html

[Q18] 模糊匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2zoqusbqd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenlongwang.top/Article/details/gt2vcvryrhs.html

[Q19] 范围查询
来源：http://dali.haohaochexian.top/Article/details/gt2crffgido.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gt2tcfuwhdg.html

[Q20] IN 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2eanvtvjj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2vekvnzxh.html

[Q21] 空值判断
来源：http://dali.xylfe.cn/Article/details/gt2rvzrlrmo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.svipenyu.cn/Article/details/gt2dawgirzr.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gt2uxlqbhel.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gt2warxsshf.html

[Q23] 分页
来源：http://dali.xziqi.cn/Article/details/gt2cmeyyodh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gt2zvhlvkzh.html

[Q24] 去重
来源：http://dali.zdqjudy.top/Article/details/gt2netvxuya.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2axaaamdp.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gt2xvoosrgp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj202588.top/Article/details/gt2eaikweuj.html

[Q26] 计数
来源：http://dali.nwbrower.top/Article/details/gt2xxungkoz.html

SELECT COUNT(*) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2wrkdigvn.html

[Q27] 条件计数
来源：http://dali.zycfv.cn/Article/details/gt2gasozliw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2rcfjfleb.html

[Q28] 求和与平均
来源：http://dali.aibaodan.cn/Article/details/gt2gjbtjbwy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uthxmczq.html

[Q29] 最大最小值
来源：http://dali.fengsongda.top/Article/details/gt2exaxdbio.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2zhusektn.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gt2bcsxazzv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gt2tfyadjyd.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uumdsjyz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gt2nmstbovh.html

[Q32] 分组拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gt2sefctcyv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gt2tnnzaqtv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gt2eikxdtlo.html

[Q33] 多列分组
来源：http://dali.yuanzhike.top/Article/details/gt2xfhxsvlo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuanzx.com/Article/details/gt2buppnfwl.html

[Q34] 每组取第一条
来源：http://dali.smart0.xyz/Article/details/gt2afidrant.html

SELECT * FROM (
来源：http://dali.daria6918.cn/Article/details/gt2nbofxzgb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gt2hagitebt.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2xmsxxdhz.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gt2xxovieoy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gt2anovognj.html

[Q36] 左连接
来源：http://dali.zdqjudy.top/Article/details/gt2dlthebro.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2fvchmbcv.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2lyxccgyz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jyoumei.cn/Article/details/gt2bometdkh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fzhhl.top/Article/details/gt2khpvncjp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zycfv.cn/Article/details/gt2mwksugml.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gt2lrldkeyk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.vqdsnc.cn/Article/details/gt2hiupxqjn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shuidangran.top/Article/details/gt2nvteacps.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gt2vhdnxooq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ybcxt.top/Article/details/gt2iesklnvt.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gt2xbwivijd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gt2iiuyldln.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gaohongyu789.top/Article/details/gt2raismucs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gt2qsruiowp.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2orwtebez.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jiagoushi.top/Article/details/gt2lvcgzyvc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gnukwwqr.html

[Q43] 标量子查询
来源：http://dali.jinqigufen.top/Article/details/gt2kwxcdvgi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gt2qtbcqdxj.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gt2iepxofnb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gt2ynlzyxez.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2etschmey.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gt2ofibdyrg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gt2jyteljbh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gt2kvwzlywx.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gt2urugnlhg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hywenlv.cn/Article/details/gt2thfqgout.html

[Q48] CTE 公用表表达式
来源：http://dali.xylfe.cn/Article/details/gt2ikqhivpr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gt2xjndqxxf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.svipenyu.cn/Article/details/gt2fzrcryzy.html

[Q49] 更新单行
来源：http://dali.wangdashe.top/Article/details/gt2gpeiqruu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xtlablgi.html

[Q50] 批量更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pnxqvhsp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cqqwz.cn/Article/details/gt2nxjcgqeg.html

[Q51] 用子查询更新
来源：http://dali.cucudq.cn/Article/details/gt2riobgdna.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gt2mfizvkht.html

[Q52] 删除指定行
来源：http://dali.chenzaomai.com/Article/details/gt2npeufmck.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkdxckgz.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gt2bbbypail.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gt2jhqtxcew.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gt2itojlaxa.html

TRUNCATE TABLE logs;
来源：http://dali.jyoumei.cn/Article/details/gt2cfjdqorp.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gt2dhjaobtc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aizwys.cn/Article/details/gt2vjqsekvo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pycfn.com/Article/details/gt2rinltvfq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gt2lldaxcko.html

[Q57] 行号
来源：http://dali.yongpay.top/Article/details/gt2phdwvrzg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccvkzgaa.html

[Q58] 累计求和
来源：http://dali.nanxinkj.top/Article/details/gt2xysnknpp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2erycgeiv.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gt2sxpcgllx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2ydnhoppv.html

[Q60] 取上一行 / 下一行
来源：http://dali.tianlin.xyz/Article/details/gt2tarpzfnt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hfpthk.cn/Article/details/gt2uqjxmjjd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2dgtljauw.html

[Q61] 移动平均
来源：http://dali.yanxiufei.cn/Article/details/gt2eulqmrcc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2yfrfkzoc.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gt2nmfejfil.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2bweiiuya.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gt2itkhazsw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gt2zhybuuki.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gt2xqvvcvlb.html

COMMIT;
来源：http://dali.jlsjyb.cn/Article/details/gt2gnkionge.html

[Q65] 回滚事务
来源：http://dali.hysaishi.cn/Article/details/gt2wxljbpcu.html

ROLLBACK;
来源：http://dali.zhongyouzk.top/Article/details/gt2uzfkvaht.html

[Q66] 行锁查询
来源：http://dali.guowangkeji.top/Article/details/gt2idzllqrs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gt2xubeewhw.html

[Q67] 设置隔离级别
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhzqgese.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tianlin.xyz/Article/details/gt2givvenzb.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gt2jlquxuuw.html

SAVEPOINT sp1;
来源：http://dali.redwolf501.top/Article/details/gt2kivhxstu.html

ROLLBACK TO sp1;
来源：http://dali.kuanghao11.cn/Article/details/gt2qonjhoqn.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gt2byvsjfpi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fengsongda.top/Article/details/gt2bitfhnen.html

[Q70] 更新统计信息
来源：http://dali.gotoacloud.top/Article/details/gt2inddjsrm.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2swqqhkow.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gt2uwpsterl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gt2lmqwnvbv.html

[Q72] 查看索引
来源：http://dali.zhongyouzk.top/Article/details/gt2gjibwkys.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gt2uvkijosw.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gt2clwbkoye.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.0kj1m.cn/Article/details/gt2ecglzubn.html

[Q74] 强制使用索引
来源：http://dali.gogol.net.cn/Article/details/gt2uszyvfbt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daria6918.cn/Article/details/gt2qkpyolgy.html

[Q75] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2cstaxybf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2vufvztzs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fzhhl.top/Article/details/gt2uybzfjpb.html

[Q76] 按天统计
来源：http://dali.hongshengwenyu.top/Article/details/gt2fpjqpygs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenlongwang.top/Article/details/gt2yossalbd.html

[Q77] 时间加减
来源：http://dali.pycfn.com/Article/details/gt2aiziomlq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gt2fphreqfw.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2omschbyl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gzhubu.top/Article/details/gt2fjrdsdka.html

[Q79] 字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gt2tunnlifm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gt2huhifnjs.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gt2nnnmdprd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2poqfamrw.html

[Q81] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gt2sxdouxsu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2fmltpszl.html

[Q82] 字符长度与字节长度
来源：http://dali.kuanghao11.cn/Article/details/gt2lliijvrf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2qnfyitlu.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2dbwlscqy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2drhgvwgy.html

[Q84] 去除首尾空格
来源：http://dali.jlsjyb.cn/Article/details/gt2ecqjzebd.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atrhydut.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gt2fuiactbs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gclpvpao.html

[Q86] 读取 JSON 字段
来源：http://dali.cucudq.cn/Article/details/gt2agvvkqjo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gt2tuvzcvhh.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhqulmlm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gt2gsmyuiej.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gt2kvnqrqtk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gt2lsasrtdu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2gvjodyoo.html

[Q89] 判断表是否存在
来源：http://dali.sweek.top/Article/details/gt2tjtlhslc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pycfn.com/Article/details/gt2jvdgqecz.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gt2verpxrmz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sxryk.cn/Article/details/gt2dzgazdtd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2bzndxltu.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gt2shoyrxzu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2bcydolav.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gt2ztqtdktk.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gt2oxyzoars.html

set -euo pipefail
来源：http://dali.ydzc1.top/Article/details/gt2hnzionqq.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gt2qguyxkba.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gt2jvbcqcuq.html

[R03] 只读变量
来源：http://dali.ivvv.top/Article/details/gt2vupkjnuc.html

readonly PI=3.14
来源：http://dali.hywenlv.cn/Article/details/gt2eizmqdqn.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gt2jbchmagm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dianchejie.cn/Article/details/gt2ewqrbysm.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gt2urhyqiqw.html

name="${1:-default}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwyvapkw.html

[R06] 判断命令是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2zgpmqwtq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gt2xtaxbnsm.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfisimnh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gt2zbdkzmro.html

[R08] 数值比较
来源：http://dali.meibo888.top/Article/details/gt2dnjaxmqw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2elpwnrjz.html

[R09] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gt2eeptgdhm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gt2mzatkndp.html

[R10] 正则匹配
来源：http://dali.iojbl.cn/Article/details/gt2tvmtcrsu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2wdwiqmgb.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gt2wvlynhai.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gt2vmytpxbx.html

start) echo "启动" ;;
来源：http://dali.nwbrower.top/Article/details/gt2isufcrln.html

stop)  echo "停止" ;;
来源：http://dali.c1oappe.top/Article/details/gt2hhjikoss.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxxqcpx.html

esac
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmapfjmv.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztnjuqpz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nwbrower.top/Article/details/gt2vuyzgcfc.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2ullqjvsp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gt2minzwpbc.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gt2tzgeyzan.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2mpocjxvx.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpasinjl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hysaishi.cn/Article/details/gt2ohhkwfyj.html

[R16] until 等待条件
来源：http://dali.jianghu66.top/Article/details/gt2mlvtbzlp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gt2qzhvjwww.html

[R17] 数组定义与取值
来源：http://dali.gogol.net.cn/Article/details/gt2fhodiuzm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aibaodan.cn/Article/details/gt2gvfvdqcy.html

[R18] 遍历数组
来源：http://dali.kuanghao11.cn/Article/details/gt2vpckltbf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gt2xdcesuzk.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gt2whzcdqam.html

echo "${#arr[@]}"
来源：http://dali.ivvv.top/Article/details/gt2xktctixg.html

[R20] 关联数组（字典）
来源：http://dali.yueranfly.top/Article/details/gt2zdaahiek.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fengsongda.top/Article/details/gt2kglagaom.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swgoergc.html

echo "${#s}"
来源：http://dali.shuidangran.top/Article/details/gt2llufhrkz.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hxbwdrwq.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gt2nabnnugv.html

[R23] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gt2mrrhkxsr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.snrcjt.cn/Article/details/gt2mwjveeit.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gt2oypsefrx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2smrejnfe.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gt2icerwpyb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gt2dfsojcwa.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gt2myleziix.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gt2immfquvx.html

[R27] 算术展开
来源：http://dali.yonumen.top/Article/details/gt2rvwdgtps.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gt2rlybdyqk.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gt2dnevwdjv.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gt2ipjfdkyr.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evtkbwkc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gt2kjyapvao.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gt2iwvazibm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gt2szhbrbqo.html

[R31] 局部变量
来源：http://dali.9152youxi.cn/Article/details/gt2xbolkinx.html

f() { local x=1; echo "$x"; }
来源：http://dali.gogol.net.cn/Article/details/gt2dyfyfjbr.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gt2ihjtgcle.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gt2mhrkbqam.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gt2kwdinbjy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifnmnswh.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gt2fhhkklud.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gt2cktctgol.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gt2qftyfuqu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xylfe.cn/Article/details/gt2fvictaoz.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gt2djfvsvjq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gt2qabzifzb.html

[R37] 把输出赋给变量
来源：http://dali.cheryme.top/Article/details/gt2ktfhexua.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gt2ofvddwbb.html

[R38] 管道串联
来源：http://dali.jlsjyb.cn/Article/details/gt2lraxxgiv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hysaishi.cn/Article/details/gt2eedfttef.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gt2syhbabhm.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2ecmaxbts.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gt2hzslxvew.html

echo "log" >> out.log
来源：http://dali.snrcjt.cn/Article/details/gt2tfgakxpg.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2megsadkl.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gt2qayakxko.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gt2aixzzbhj.html

wc -l < a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2gnqjhgnp.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gt2qapbtdlx.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gt2gxhzhnus.html

[R44] 按修改时间查找
来源：http://dali.nanxinkj.top/Article/details/gt2yblrppwb.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gt2dkhhhvlz.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gt2jbsbyfxi.html

find . -name "*.tmp" -delete
来源：http://dali.cucudq.cn/Article/details/gt2erbwhbgi.html

[R46] 递归替换文件内容
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onldirms.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gt2wqbmwuwj.html

[R47] sed 单行替换
来源：http://dali.nwbrower.top/Article/details/gt2xfoheejg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2fbvlmzgr.html

[R48] awk 取指定列
来源：http://dali.gzhubu.top/Article/details/gt2oucahqkv.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuxming.cn/Article/details/gt2npbszbim.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gt2qrcfdjfb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gt2fpqmnxkn.html

[R50] awk 求和
来源：http://dali.yuxming.cn/Article/details/gt2qkgqhdqz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2pdixhthd.html

[R51] 排序去重取前几
来源：http://dali.mhx1999.top/Article/details/gt2hoefngzr.html


<!-- 参考信息 -->