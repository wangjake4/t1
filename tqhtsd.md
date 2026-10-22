代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gt2xijnrhwa.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gt2tlsvtltf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gt2bazkowfb.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gt2nrlhksnx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gt2zbxvwwpo.html

[Q07] 删除表
来源：http://dali.kuanghao11.cn/Article/details/gt2ochrqcib.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gt2rbnbacna.html

[Q08] 创建普通索引
来源：http://dali.chenzaomai.com/Article/details/gt2lplywtvv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gt2bgtgbzai.html

[Q09] 创建唯一索引
来源：http://dali.daxiang520.top/Article/details/gt2cjdufcsm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gt2obzmbzyl.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gt2jbmmqrif.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cheryme.top/Article/details/gt2atxuvxda.html

[Q11] 一次插入多行
来源：http://dali.yonumen.top/Article/details/gt2ptxtrbhg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gt2blzfjvck.html

[Q12] 插入后取自增 ID
来源：http://dali.cqqwz.cn/Article/details/gt2oujbkaxy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gt2crxlmbrt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gt2qcuelbba.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gt2fmbfowit.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2rnjmqqgn.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuanzx.com/Article/details/gt2yyfeixuu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gt2bsvmrrjw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihpedboz.html

[Q15] 查询全部
来源：http://dali.daxiang520.top/Article/details/gt2obnzblqc.html

SELECT * FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2zbucfppn.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gt2iawowvxc.html

SELECT id, name FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2xboqlqtw.html

[Q17] 条件查询
来源：http://dali.jinqigufen.top/Article/details/gt2boyfbsrn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2aaoxjxzb.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2jyidwggn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hfpthk.cn/Article/details/gt2oqpscqfa.html

[Q19] 范围查询
来源：http://dali.jqgufenzy.top/Article/details/gt2xxgwhdxk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gt2sxfsiihu.html

[Q20] IN 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhhoekvn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ydzc1.top/Article/details/gt2rmcjlzgb.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcakbeku.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gt2zpdwyugb.html

[Q22] 排序
来源：http://dali.jqgfzy.top/Article/details/gt2djrumnhy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sysykeji.top/Article/details/gt2xljqgwxp.html

[Q23] 分页
来源：http://dali.sufxvd.cn/Article/details/gt2tapigzuq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cashguo.top/Article/details/gt2snddycop.html

[Q24] 去重
来源：http://dali.tianlin.xyz/Article/details/gt2zdkmrwdl.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ytrwyqix.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gt2kglwykzj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kynrrrcq.html

[Q26] 计数
来源：http://dali.hnxiangtu.top/Article/details/gt2yclhnium.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibwjlnfr.html

[Q27] 条件计数
来源：http://dali.vqdsnc.cn/Article/details/gt2xtypmzwr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2ixxyshcm.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gt2xbnqyorm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2iywvurvc.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gt2ofjeexln.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2ipmmqkbd.html

[Q30] 分组统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gawvhcqq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gt2luwbcfdg.html

[Q31] 分组后过滤
来源：http://dali.gzhubu.top/Article/details/gt2wtoobwrp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenzaomai.com/Article/details/gt2ntrfwanx.html

[Q32] 分组拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2drirajfa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gt2qannolvv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hfpthk.cn/Article/details/gt2fhlzsqth.html

[Q33] 多列分组
来源：http://dali.gzhubu.top/Article/details/gt2dxeynurb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gt2vjrsoyjg.html

[Q34] 每组取第一条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptoldjdy.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gt2ycqzegyt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jianghu66.top/Article/details/gt2nfmwxjnu.html

) t WHERE rn = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2krdvlvpx.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gt2ffunrphl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gt2ddirefjl.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gt2djgvzjsm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gt2ivrrviqv.html

[Q37] 右连接
来源：http://dali.cashguo.top/Article/details/gt2vjneoxdt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sysykeji.top/Article/details/gt2veijljup.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cashguo.top/Article/details/gt2bwmbkpyb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dashuyun.cn/Article/details/gt2ppqidzph.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gt2bgcftlun.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gt2rahcejmn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guowangkeji.top/Article/details/gt2ackuitlf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gt2ixhfjyou.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhengqikj.top/Article/details/gt2zbllcvdu.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gt2zxaraiuz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yangfankeji.com/Article/details/gt2euzkmhns.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gt2umsvjsgl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gt2ubmegnqb.html

[Q42] 连接条件附加过滤
来源：http://dali.cdnleiting.top/Article/details/gt2vzjzmxmh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pengpengdd.cyou/Article/details/gt2mcphrxvr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ivvv.top/Article/details/gt2iqrdwapw.html

[Q43] 标量子查询
来源：http://dali.guowangkeji.top/Article/details/gt2gnwqtnbn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.meibo888.top/Article/details/gt2uarvdvmf.html

[Q44] IN 子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmdqtukj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jianghu66.top/Article/details/gt2fxwcevlw.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gt2lzoednfk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gt2ljtjcmrn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gt2osjgmpbb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bgfatqun.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gt2blnwqmee.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuanzx.com/Article/details/gt2bmkqezuh.html

[Q48] CTE 公用表表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvpngstr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gt2zltfoaeg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gt2xfqzqiuf.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gt2ajutxwol.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gt2dodmvutz.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gt2kxgcenyq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gt2bkwjmbvj.html

[Q51] 用子查询更新
来源：http://dali.yanxiufei.cn/Article/details/gt2vbmgedlj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2qtkfatdo.html

[Q52] 删除指定行
来源：http://dali.ybcxt.top/Article/details/gt2bvviqdgw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gt2ybomdpxk.html

[Q53] 按条件删除
来源：http://dali.wangdashe.top/Article/details/gt2owvnzsuo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gt2drtxthgk.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftvmhdbj.html

TRUNCATE TABLE logs;
来源：http://dali.kuanghao11.cn/Article/details/gt2wabokdqa.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onxmogff.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gt2smjbnfbc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gzhubu.top/Article/details/gt2ljnntcvk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cheryme.top/Article/details/gt2behcihqp.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrkfkwbg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2duoztllb.html

[Q58] 累计求和
来源：http://dali.yueranfly.top/Article/details/gt2ubqdlpip.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptfokssk.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugmyksnm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2giaydpss.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gt2bsmueduq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuanzhike.top/Article/details/gt2bbfkuzrr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2iqkjcsld.html

[Q61] 移动平均
来源：http://dali.aibaodan.cn/Article/details/gt2vosgszpe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2akjdibtw.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gt2nsocjfso.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gt2manreifa.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gt2ptbvzgtn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gt2qydwvuco.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gt2eghjrjlz.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dqqdrced.html

[Q65] 回滚事务
来源：http://dali.tian-w.cn/Article/details/gt2arskegmw.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gt2rsghoqxd.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gt2htzfdobb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gt2ldmireeh.html

[Q67] 设置隔离级别
来源：http://dali.svipenyu.cn/Article/details/gt2ejcfomjn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hfpthk.cn/Article/details/gt2ehlnihkh.html

[Q68] 保存点
来源：http://dali.aizwys.cn/Article/details/gt2vgexjydn.html

SAVEPOINT sp1;
来源：http://dali.zhixingplan.top/Article/details/gt2addaaagh.html

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gt2eubochtv.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gt2ccdoayjm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gogol.net.cn/Article/details/gt2qaqnmobu.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gt2kdxiveiv.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gt2xcdsnnhq.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gt2iiibpbyq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sysykeji.top/Article/details/gt2nisoxqny.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gt2aknuwkkg.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2ammloizv.html

[Q73] 查看表状态
来源：http://dali.jinghuilouyu.cn/Article/details/gt2orbqujah.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gt2eybcejmr.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2wsgtqhgm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aizwys.cn/Article/details/gt2xcqswekt.html

[Q75] 日期格式化
来源：http://dali.cheryme.top/Article/details/gt2qrgonhpy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agxhnace.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gt2awisvgul.html

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gt2frhqvvxm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuanzx.com/Article/details/gt2aypglbke.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gt2hldnwuvv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gt2eraxicpz.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gt2gpvmcbab.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gt2eerywxio.html

[Q79] 字符串拼接
来源：http://dali.jianghu66.top/Article/details/gt2eurzrqcw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pengpengdd.cyou/Article/details/gt2zojmpbhi.html

[Q80] 字符串截取
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aoezsrrb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2lqpfdfsf.html

[Q81] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gt2blkzdxvo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2cfvbrzbx.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gt2ivwdsyeg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2xqsxfcul.html

[Q83] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gt2pdnzrsxr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2iorbidns.html

[Q84] 去除首尾空格
来源：http://dali.zhoulong.xyz/Article/details/gt2netbkmsp.html

SELECT TRIM(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2tgxzxtrt.html

[Q85] 数值取整
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prhgltwz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hfpthk.cn/Article/details/gt2ecevtanv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gt2qkgtjzpr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gogol.net.cn/Article/details/gt2sjyfhomn.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gt2epbofttl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvffqupl.html

[Q88] 行转列（条件聚合）
来源：http://dali.xylfe.cn/Article/details/gt2jpilmxqs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gt2sgqkmgrt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2vxjbnnkh.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gt2ocqtpazy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hfpthk.cn/Article/details/gt2tvlefnbb.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gt2eagburde.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gt2zutidfzj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2avnjeuyo.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gt2adamhuqx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2tuqvhuvw.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gt2irfvntwq.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdklfmax.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gt2cwecyfsd.html

[R02] 变量赋值与使用
来源：http://dali.svipenyu.cn/Article/details/gt2vasaytux.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gt2kcqokbfj.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gt2vykhhkgh.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gt2breaitca.html

[R04] 位置参数
来源：http://dali.shzxlz.cn/Article/details/gt2fzcitqvr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gt2sbbuthfl.html

[R05] 参数默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxgzfnfg.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2gnxtubnw.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2flmyupdn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gt2suljuzlo.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gt2agancvmn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gt2qcerrudi.html

[R08] 数值比较
来源：http://dali.hammf.cn/Article/details/gt2tletzsbd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2cqlduawh.html

[R09] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gt2qeytmzag.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2owapexvb.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gt2jmljcopz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gt2yniyylwq.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gt2syzonoey.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvucgeni.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gt2gqbgxfbh.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2sgovjqxq.html

*)     echo "未知命令" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvvtfrif.html

esac
来源：http://dali.xylfe.cn/Article/details/gt2jzlcabbg.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gt2ybwuoavr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gt2vokbdzsx.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gt2nsfakifb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gt2sczewjyz.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gt2retlzmdq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gt2cxciaaai.html

[R15] while 逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jopmwdtm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2xivaiwun.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gt2likqlzvz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gt2ptcoepog.html

[R17] 数组定义与取值
来源：http://dali.sysykeji.top/Article/details/gt2srfxhgwe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gt2insnjtqz.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gt2cehbaaar.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuxming.cn/Article/details/gt2wkzhyltn.html

[R19] 数组长度
来源：http://dali.meibo888.top/Article/details/gt2dubhgtnv.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gt2nardminp.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gt2bftalqmq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzxyqrck.html

[R21] 字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gt2gsbvxfna.html

echo "${#s}"
来源：http://dali.jqgfzy.top/Article/details/gt2enhjrcip.html

[R22] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gt2ffljtena.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gt2lnpoieqr.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gt2hzaaudto.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guannengcc.top/Article/details/gt2ltskxlmg.html

[R24] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gt2mgkwpbsp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gt2ichrzrgy.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gt2wnblbzwa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tianlin.xyz/Article/details/gt2kvkwohxw.html

[R26] 命令替换
来源：http://dali.gzhubu.top/Article/details/gt2psiangno.html

now=$(date +%F); echo "$now"
来源：http://dali.yanxiufei.cn/Article/details/gt2znqvlsjt.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gt2dmapkiuk.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gt2erpviqoy.html

[R28] 浮点运算
来源：http://dali.xuanzx.com/Article/details/gt2kvjxkice.html

echo "scale=2; 10/3" | bc
来源：http://dali.0kj1m.cn/Article/details/gt2bjzicnvi.html

[R29] 定义函数
来源：http://dali.zycfv.cn/Article/details/gt2hmmafccs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2loydsqsv.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gt2unbptxiz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwsddfrj.html

[R31] 局部变量
来源：http://dali.wangdashe.top/Article/details/gt2vyxlolri.html

f() { local x=1; echo "$x"; }
来源：http://dali.snrcjt.cn/Article/details/gt2jynvecru.html

[R32] 参数个数校验
来源：http://dali.tian-w.cn/Article/details/gt2vndgndyf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gt2jboybgrh.html

[R33] 捕获错误并提示行号
来源：http://dali.yongpay.top/Article/details/gt2sfijdbiq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gt2jdzctosf.html

[R34] 退出时清理
来源：http://dali.quarkkingdee.top/Article/details/gt2wzrsmaqv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gt2faimcqgb.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gt2efnivzzj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtceitan.html

[R36] 并发执行多个任务
来源：http://dali.0kj1m.cn/Article/details/gt2mqviikpa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gt2ulnmpbxd.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gt2grcjhwba.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gt2sninvqwu.html

[R38] 管道串联
来源：http://dali.xuetiantiany.cn/Article/details/gt2vvnnvyyp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhohcgbk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gt2dzsnbxio.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gt2zrfztugc.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gt2gnzdlmta.html

echo "log" >> out.log
来源：http://dali.jinqigufen.top/Article/details/gt2uluyoonw.html

[R41] 丢弃输出
来源：http://dali.xuanzx.com/Article/details/gt2fpakpurv.html

cmd >/dev/null 2>&1
来源：http://dali.birdmap.top/Article/details/gt2adalglly.html

[R42] 输入重定向
来源：http://dali.shzxlz.cn/Article/details/gt2gadpafju.html

wc -l < a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2snzsohyl.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gt2vnehoblh.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpddcidj.html

[R44] 按修改时间查找
来源：http://dali.smart0.xyz/Article/details/gt2gfzegwdu.html

find . -mtime -7 -type f
来源：http://dali.cucudq.cn/Article/details/gt2bnwmnzqu.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvmmdlwu.html

find . -name "*.tmp" -delete
来源：http://dali.cqqwz.cn/Article/details/gt2tjsazhci.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gt2ourhhwlz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gt2jpxisqfm.html

[R47] sed 单行替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2hkdjolae.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2kzjcjsno.html

[R48] awk 取指定列
来源：http://dali.havefunace.top/Article/details/gt2wzrqedsg.html

awk '{print $1, $3}' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2rqgqrzjn.html

[R49] awk 带条件
来源：http://dali.dashuyun.cn/Article/details/gt2zgtbahzq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcvyjyus.html

[R50] awk 求和
来源：http://dali.redwolf501.top/Article/details/gt2gqiaawrz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2wjgjagef.html

[R51] 排序去重取前几
来源：http://dali.xylfe.cn/Article/details/gt2xmgrczhs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gt2gpvweqot.html

[R52] 统计行数
来源：http://dali.hfpthk.cn/Article/details/gt2gbpvobdy.html

wc -l a.txt
来源：http://dali.jianghu66.top/Article/details/gt2asemclsz.html

[R53] 查看文件头与实时尾
来源：http://dali.hnqzz.top/Article/details/gt2ddlmwyry.html


<!-- 参考信息 -->