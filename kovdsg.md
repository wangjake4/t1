代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gt2kbkmmflx.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gt2ikxvcckv.html

amount DECIMAL(10, 2),
来源：http://dali.gogol.net.cn/Article/details/gt2ekkrjvfk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gt2rsbomqlg.html

);
来源：http://dali.gaohongyu789.top/Article/details/gt2eotbmaxc.html

[Q03] 增加列
来源：http://dali.haohaochexian.top/Article/details/gt2mwoojrhi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuxming.cn/Article/details/gt2duypesnk.html

[Q04] 修改列类型
来源：http://dali.gaohongyu789.top/Article/details/gt2onlpvhfk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gt2lauflkrz.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gt2pdpnquke.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guannengcc.top/Article/details/gt2jzhgyerh.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gt2zitwxspk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daxiang520.top/Article/details/gt2mnzeqqsh.html

[Q07] 删除表
来源：http://dali.shuidangran.top/Article/details/gt2yadbhhfd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhixingplan.top/Article/details/gt2flymdnnj.html

[Q08] 创建普通索引
来源：http://dali.shuidangran.top/Article/details/gt2pglhqlcj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apapcyyz.html

[Q09] 创建唯一索引
来源：http://dali.yanxiufei.cn/Article/details/gt2tewzzved.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gt2nyxfgdfo.html

[Q10] 插入单行
来源：http://dali.gogol.net.cn/Article/details/gt2sopmrpsi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gt2egntbwvo.html

[Q11] 一次插入多行
来源：http://dali.aibaodan.cn/Article/details/gt2zivrtjbk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gt2awmihman.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gt2qrnovcjx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gt2iwdaazhw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gt2ejhhmwhr.html

[Q13] 忽略重复插入
来源：http://dali.nanxuanxn.top/Article/details/gt2gudmtxlf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aibaodan.cn/Article/details/gt2vwtnyrrx.html

[Q14] 存在则更新（upsert）
来源：http://dali.gaohongyu789.top/Article/details/gt2khoxnetb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.meibo888.top/Article/details/gt2iaptpfqy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dashuyun.cn/Article/details/gt2mnaminfl.html

[Q15] 查询全部
来源：http://dali.tanke756.top/Article/details/gt2wbzvbtbn.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2deglpovw.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gt2fxfvihkv.html

SELECT id, name FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2ksxgshnl.html

[Q17] 条件查询
来源：http://dali.zhongyouzk.top/Article/details/gt2jadxzwgt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2tegoimlu.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ixjhnktq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dianchejie.cn/Article/details/gt2jpcawlzl.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gt2ygduzzmb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.c1oappe.top/Article/details/gt2rffyiknc.html

[Q20] IN 列表
来源：http://dali.zdqjudy.top/Article/details/gt2fmaebztl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gt2cjjmfsva.html

[Q21] 空值判断
来源：http://dali.bjfxy.top/Article/details/gt2ywkhenaa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gt2kxqvvqvn.html

[Q22] 排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxujyjcx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxuanxn.top/Article/details/gt2pkgobkvl.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gt2fpalnnpx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxfprhzf.html

[Q24] 去重
来源：http://dali.jqgfzy.top/Article/details/gt2dbuksrnf.html

SELECT DISTINCT city FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2txjwsooz.html

[Q25] 只取前 N 条
来源：http://dali.hongshengwenyu.top/Article/details/gt2nepdskhx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gt2cffekntn.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gt2yyhitfhe.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvxzqlys.html

[Q27] 条件计数
来源：http://dali.pengpengdd.cyou/Article/details/gt2bfnmlowe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.birdmap.top/Article/details/gt2qglggcga.html

[Q28] 求和与平均
来源：http://dali.chenzaomai.com/Article/details/gt2pvvljzii.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2kezqijrt.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gt2rdduqcbm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2aquryqvi.html

[Q30] 分组统计
来源：http://dali.zhixingplan.top/Article/details/gt2fdtfexjb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2bymhdmrm.html

[Q31] 分组后过滤
来源：http://dali.xinyue.icu/Article/details/gt2pfhdaaji.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gt2agrjaiee.html

[Q32] 分组拼接字符串
来源：http://dali.bjfxy.top/Article/details/gt2rfjyuzlu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gt2nytlkjsa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yueranfly.top/Article/details/gt2lsyyxmfc.html

[Q33] 多列分组
来源：http://dali.andypj.xyz/Article/details/gt2lztrksvr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cdnleiting.top/Article/details/gt2mfwdxlld.html

[Q34] 每组取第一条
来源：http://dali.nanxinkj.top/Article/details/gt2flapkkaq.html

SELECT * FROM (
来源：http://dali.hywenlv.cn/Article/details/gt2qeghxhbt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jiagoushi.top/Article/details/gt2ocnwwzea.html

) t WHERE rn = 1;
来源：http://dali.yj20258888.top/Article/details/gt2edkgwilr.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gt2frnyoblk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2vvikjlhp.html

[Q36] 左连接
来源：http://dali.9152youxi.cn/Article/details/gt2qktbxiqk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gt2lcyvkbis.html

[Q37] 右连接
来源：http://dali.sxryk.cn/Article/details/gt2pgxupltb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gt2dslhuxsh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.haohaochexian.top/Article/details/gt2artelamj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sufxvd.cn/Article/details/gt2tmnannxl.html

[Q39] 自连接（查上下级）
来源：http://dali.316326.xyz/Article/details/gt2pjmwlrbb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tianlin.xyz/Article/details/gt2wkmvscxt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gt2qvvgvszz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.redwolf501.top/Article/details/gt2jrabyarn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yueranfly.top/Article/details/gt2jtdlxzyb.html

[Q41] 多表连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2kuyfgzsf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.316326.xyz/Article/details/gt2zrggvcut.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cheryme.top/Article/details/gt2bjcvqfvn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmrqbtns.html

[Q42] 连接条件附加过滤
来源：http://dali.gotoacloud.top/Article/details/gt2vbebyvgf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gt2coxsjmps.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gt2ogckkbjv.html

[Q43] 标量子查询
来源：http://dali.redwolf501.top/Article/details/gt2uasopplc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gt2nzbjxrjz.html

[Q44] IN 子查询
来源：http://dali.bjfxy.top/Article/details/gt2ckchayom.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgufenzy.top/Article/details/gt2xtpwbwad.html

[Q45] EXISTS 判断存在
来源：http://dali.sufxvd.cn/Article/details/gt2kvnlltrc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gt2xjxlkwig.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cheryme.top/Article/details/gt2jvpwqpql.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gt2rmomkdkj.html

[Q47] 与平均值比较
来源：http://dali.yj202588.top/Article/details/gt2ijsmyryr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gt2zcdejrtr.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohavsgdk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gt2ftuudmcg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gt2rxmrkefp.html

[Q49] 更新单行
来源：http://dali.wangdashe.top/Article/details/gt2ndtdncuc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2blubwszt.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gt2vmwhvglu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fengsongda.top/Article/details/gt2lktxitze.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gt2ggiasach.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2jllbkevt.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gt2ygmmcfmi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gt2odqbenye.html

[Q53] 按条件删除
来源：http://dali.haohaochexian.top/Article/details/gt2dagbhxvj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gt2yqfuqvvp.html

[Q54] 清空表
来源：http://dali.gogol.net.cn/Article/details/gt2spuxojhm.html

TRUNCATE TABLE logs;
来源：http://dali.pycfn.com/Article/details/gt2yfhulzwr.html

[Q55] 排名（并列占位）
来源：http://dali.kuanghao11.cn/Article/details/gt2zflcgqvx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gt2uabtahje.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gt2llvvjriq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gt2pwzjonww.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gt2rhvekyje.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqigcmjo.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gt2nyaoochh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2ytfhntxr.html

[Q59] 分组内累计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzrghqor.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2muuoeike.html

[Q60] 取上一行 / 下一行
来源：http://dali.316326.xyz/Article/details/gt2acxunrgo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gt2djwgvkop.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2lagtsmzx.html

[Q61] 移动平均
来源：http://dali.dashuyun.cn/Article/details/gt2qofdlwnd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2rskrtjrm.html

[Q62] 分组占比
来源：http://dali.hammf.cn/Article/details/gt2tnzuwkpn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wfspiloh.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnnurcoy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gt2fyxvimyn.html

[Q64] 提交事务
来源：http://dali.sxryk.cn/Article/details/gt2pexuzhsn.html

COMMIT;
来源：http://dali.mhx1999.top/Article/details/gt2hslloplc.html

[Q65] 回滚事务
来源：http://dali.hnxiangtu.top/Article/details/gt2xjvxeprl.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gt2qszmhury.html

[Q66] 行锁查询
来源：http://dali.birdmap.top/Article/details/gt2jwvtoatp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yvedp.cn/Article/details/gt2kbuypnfg.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxhmupup.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gt2gxtxioxp.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gt2paplnsfz.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gt2mshcqfjk.html

ROLLBACK TO sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2lcioqnjb.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gt2agwyyjcj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258.top/Article/details/gt2ifgxluuf.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gt2swoyvuyg.html

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gt2vauqsjze.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gt2jmqucuzf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gt2kcxokznj.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gt2goxoblga.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2mykrpnau.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gt2mmlhkkug.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tisxzunz.html

[Q74] 强制使用索引
来源：http://dali.tianlin.xyz/Article/details/gt2jdgodfad.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gt2rpvemwei.html

[Q75] 日期格式化
来源：http://dali.meibo888.top/Article/details/gt2ihzxjurn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2gqsrxxww.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gt2wvacwjqj.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gt2yzlxfraw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gt2bskthugq.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gt2qlxuvddr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.svipenyu.cn/Article/details/gt2dfiouksf.html

[Q78] 当前时间
来源：http://dali.guowangkeji.top/Article/details/gt2ctsptjhy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gt2pfqxxqsp.html

[Q79] 字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gt2skdfeixi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gt2jszfwhzl.html

[Q80] 字符串截取
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgxwjtwf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2dzzpmlhu.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gt2itakzeyf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pycfn.com/Article/details/gt2fxpixhae.html

[Q82] 字符长度与字节长度
来源：http://dali.fengsongda.top/Article/details/gt2efwgbfqb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2wlnvacao.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gt2dirjfkci.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2ikftffey.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gt2labaaodg.html

SELECT TRIM(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2uolwnxwh.html

[Q85] 数值取整
来源：http://dali.svipenyu.cn/Article/details/gt2lrbbwdfm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cdnleiting.top/Article/details/gt2sahprlng.html

[Q86] 读取 JSON 字段
来源：http://dali.guannengcc.top/Article/details/gt2rlwrhpmz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.snrcjt.cn/Article/details/gt2hpdfwlzs.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcfgfdvx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gt2riojiyzc.html

[Q88] 行转列（条件聚合）
来源：http://dali.pengpengdd.cyou/Article/details/gt2jizfozzz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgfzy.top/Article/details/gt2hptburny.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2txtvdkgg.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gt2jxjgvaxx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gt2kkzmwkxs.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qysoctuh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2gogixvxa.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2aohlgjgn.html

R. Bash 专题
来源：http://dali.zycfv.cn/Article/details/gt2ycqepzsb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2hvfjhfse.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gt2hxexawjf.html

#!/usr/bin/env bash
来源：http://dali.jqgufenzy.top/Article/details/gt2gjcorgtp.html

set -euo pipefail
来源：http://dali.xziqi.cn/Article/details/gt2hkgpjjny.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gt2agipvibz.html

name="Tom"; echo "$name"
来源：http://dali.daria6918.cn/Article/details/gt2nhlfgixh.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gt2spchpgzj.html

readonly PI=3.14
来源：http://dali.hammf.cn/Article/details/gt2ylynacxu.html

[R04] 位置参数
来源：http://dali.aibaodan.cn/Article/details/gt2rhcejith.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gt2wdbqteqr.html

[R05] 参数默认值
来源：http://dali.yongpay.top/Article/details/gt2dfnkruym.html

name="${1:-default}"
来源：http://dali.yonumen.top/Article/details/gt2scwjedlx.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2ucdmyfsq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kiaxcvrn.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gt2vygcttla.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2slqomqtx.html

[R08] 数值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycvrhgna.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2hqntompy.html

[R09] 字符串比较
来源：http://dali.yongpay.top/Article/details/gt2rxrotkwt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2hkfvgnpf.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gt2xqujgyzf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gt2pmximanl.html

[R11] case 多分支
来源：http://dali.sufxvd.cn/Article/details/gt2bmlbvhyq.html

case "$1" in
来源：http://dali.sufxvd.cn/Article/details/gt2mqenvypt.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gt2lbuqmdkf.html

stop)  echo "停止" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2nfpmtjef.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2juwzutdh.html

esac
来源：http://dali.jyoumei.cn/Article/details/gt2evapcpsq.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gt2qtnebtov.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gt2pfrtoxpd.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gt2mdyptuej.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gt2hejzlfrk.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gt2amuivehn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gt2jdkpmziu.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2wavmkjmu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gt2zjjxuvmc.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gt2tofhzhhs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gt2emxozuzp.html

[R17] 数组定义与取值
来源：http://dali.tanke756.top/Article/details/gt2jomusiub.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2tkpxtgbp.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gt2fosqqclk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gt2mnhpvrbu.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gt2ibqezsqo.html

echo "${#arr[@]}"
来源：http://dali.sufxvd.cn/Article/details/gt2ywzxpabr.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gt2kyjwipwq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gt2dzlfnpal.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcnqlcgn.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gt2aeufyket.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gt2ankoylhf.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gt2nnutlpbr.html

[R23] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gt2yeiflcyr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhengqikj.top/Article/details/gt2ryhxzotn.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gt2ylqntebb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gt2oihemvpt.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gt2cxfnfuzo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hammf.cn/Article/details/gt2epfauerv.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gt2tosrrlhj.html

now=$(date +%F); echo "$now"
来源：http://dali.xylfe.cn/Article/details/gt2ciymitqv.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gt2acmidlge.html

echo $((1 + 2 * 3))
来源：http://dali.sysykeji.top/Article/details/gt2yhuzkhqr.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcozmhcy.html

echo "scale=2; 10/3" | bc
来源：http://dali.hammf.cn/Article/details/gt2dqxpliat.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gt2atoiigpd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cdnleiting.top/Article/details/gt2qtglmldx.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gt2qpwyrwlr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gt2bewejnkv.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gt2lljwxysk.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gt2jpbaoipx.html

[R32] 参数个数校验
来源：http://dali.aizwys.cn/Article/details/gt2qoabrjka.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gt2skejhghr.html

[R33] 捕获错误并提示行号
来源：http://dali.shzxlz.cn/Article/details/gt2nkziwtdd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aizwys.cn/Article/details/gt2qratzlen.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gt2xblndaiv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drdnammt.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gt2tvtkxejq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnqzz.top/Article/details/gt2tfsteviy.html

[R36] 并发执行多个任务
来源：http://dali.aizwys.cn/Article/details/gt2ppdrvekh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gzhubu.top/Article/details/gt2fsvtzpvs.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gt2znrktcca.html

files=$(ls -1)
来源：http://dali.ivvv.top/Article/details/gt2kxktywdr.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gt2mdmholek.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gt2lcxytjxz.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gt2wclkzxck.html

cmd > out.log 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gt2roqarjrx.html

[R40] 追加写日志
来源：http://dali.nanxuanxn.top/Article/details/gt2mqpegdyz.html

echo "log" >> out.log
来源：http://dali.hammf.cn/Article/details/gt2vjnzzhtt.html

[R41] 丢弃输出
来源：http://dali.ydzc1.top/Article/details/gt2nuxzawab.html

cmd >/dev/null 2>&1
来源：http://dali.yongpay.top/Article/details/gt2gsnbooxd.html

[R42] 输入重定向
来源：http://dali.smart0.xyz/Article/details/gt2fbehaxtw.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2vesxcubo.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gt2erfxixts.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gt2hvqfbkad.html

[R44] 按修改时间查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlbiikjj.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gt2wddxlngl.html

[R45] 批量删除
来源：http://dali.andypj.xyz/Article/details/gt2qgqyfkiy.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigfzy.top/Article/details/gt2qgaeswlq.html

[R46] 递归替换文件内容
来源：http://dali.zhoulong.xyz/Article/details/gt2wjijogot.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gt2xavrxzxu.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gt2mmtpyfes.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gt2ofpthulq.html

[R48] awk 取指定列
来源：http://dali.jyoumei.cn/Article/details/gt2ejimskug.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kheiwfyz.html

[R49] awk 带条件
来源：http://dali.hfpthk.cn/Article/details/gt2swosfdxb.html


<!-- 参考信息 -->