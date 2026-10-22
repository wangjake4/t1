代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2gablhlbt.html

user_id INT NOT NULL,
来源：http://dali.yj202588.top/Article/details/gt2ydhvfhmy.html

amount DECIMAL(10, 2),
来源：http://dali.sweek.top/Article/details/gt2ywmenqgk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gt2ueysfcdp.html

);
来源：http://dali.vqdsnc.cn/Article/details/gt2xumobrjn.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gt2usrckdth.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gt2tlqrgbvd.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gt2yvitetdi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gt2ioydydhj.html

[Q05] 重命名列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2liriwepv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tianlin.xyz/Article/details/gt2saldmsjm.html

[Q06] 删除列
来源：http://dali.nanxinkj.top/Article/details/gt2cdqgbxud.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmxdacll.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gt2jassvxty.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gt2afdnmuwg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2anqejjgw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gt2sonidklt.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtiwxquk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gt2chdvqasb.html

[Q10] 插入单行
来源：http://dali.hywenlv.cn/Article/details/gt2kvepexcw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shuidangran.top/Article/details/gt2wyqjmhqc.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gt2gbbyrign.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egrbizec.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gt2aewousno.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigufen.top/Article/details/gt2ijwnosgu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.c1oappe.top/Article/details/gt2cwxuvwsk.html

[Q13] 忽略重复插入
来源：http://dali.zhoulong.xyz/Article/details/gt2iouqbsrp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2fvyyuknp.html

[Q14] 存在则更新（upsert）
来源：http://dali.snrcjt.cn/Article/details/gt2dvrjuqdj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gt2zifhcgdb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ydzc1.top/Article/details/gt2erjapkbi.html

[Q15] 查询全部
来源：http://dali.redwolf501.top/Article/details/gt2wmhiavkq.html

SELECT * FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2hpicenhe.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gt2mvtbmsnn.html

SELECT id, name FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2gzmvllve.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gt2luxqcyxt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvlxpdxb.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2biqpftfu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvxuoljs.html

[Q19] 范围查询
来源：http://dali.jinqigufen.top/Article/details/gt2jbagpysy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gt2tuhmssfn.html

[Q20] IN 列表
来源：http://dali.hfpthk.cn/Article/details/gt2rfbxpdks.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gt2ygxqejtm.html

[Q21] 空值判断
来源：http://dali.zhengqikj.top/Article/details/gt2mpkydzsi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gt2hxpomuro.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oocxeaac.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cdnleiting.top/Article/details/gt2njdqxqxj.html

[Q23] 分页
来源：http://dali.hnqzz.top/Article/details/gt2lejwrnup.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangdashe.top/Article/details/gt2txvcpges.html

[Q24] 去重
来源：http://dali.redwolf501.top/Article/details/gt2telubxbg.html

SELECT DISTINCT city FROM users;
来源：http://dali.yonumen.top/Article/details/gt2wejlbilg.html

[Q25] 只取前 N 条
来源：http://dali.sysykeji.top/Article/details/gt2hqqpnydm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gt2umpjjqic.html

[Q26] 计数
来源：http://dali.xylfe.cn/Article/details/gt2lsgdalrg.html

SELECT COUNT(*) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzpvvazc.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gt2ezwgnzhw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2ezlavwmt.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gt2alooitkb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmqzkiff.html

[Q29] 最大最小值
来源：http://dali.guannengcc.top/Article/details/gt2veetfirg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2fmrvtnql.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gt2rnyjqojg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gt2thztmlcg.html

[Q31] 分组后过滤
来源：http://dali.guannengcc.top/Article/details/gt2yctiifff.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.havefunace.top/Article/details/gt2vqckbdmt.html

[Q32] 分组拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gt2slolsiwt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gt2wycwvisu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhengqikj.top/Article/details/gt2eclgvcso.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gt2hhsfptql.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.meibo888.top/Article/details/gt2vrdemjce.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gt2byusruun.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gt2iivpccwb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ppjwa.cn/Article/details/gt2gxeolpyf.html

) t WHERE rn = 1;
来源：http://dali.fzhhl.top/Article/details/gt2chxzupnu.html

[Q35] 内连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsyplovg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gt2hbanxogk.html

[Q36] 左连接
来源：http://dali.tian-w.cn/Article/details/gt2alhblbiw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gt2rumkoikk.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gt2veblnzwx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rudiazfa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.svipenyu.cn/Article/details/gt2khjtjznd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxinkj.top/Article/details/gt2vsimpvvo.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gt2zmvaaubz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gt2lwkxlddo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gt2outdxgaf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.mhx1999.top/Article/details/gt2ggasfgtd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kcjqqhvz.html

[Q41] 多表连接
来源：http://dali.quarkkingdee.top/Article/details/gt2yaqhtkkv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yonumen.top/Article/details/gt2ikkvnjpd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhengqikj.top/Article/details/gt2weonboxv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gt2wkkfdvvo.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gt2ocesxjdh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shzxlz.cn/Article/details/gt2uqsegkal.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gt2ryeyyopa.html

[Q43] 标量子查询
来源：http://dali.vqdsnc.cn/Article/details/gt2nhtsjaes.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tanke756.top/Article/details/gt2aqmrwvxr.html

[Q44] IN 子查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2khyxfwnl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rusjikde.html

[Q45] EXISTS 判断存在
来源：http://dali.yangfankeji.com/Article/details/gt2jjrgicyq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gt2vzvgzoyd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jianghu66.top/Article/details/gt2vwhvbbea.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gt2gbqnxogr.html

[Q47] 与平均值比较
来源：http://dali.cheryme.top/Article/details/gt2sffskpjx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gt2nnjpjlcc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2rtkkapaw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uzaffeot.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daxiang520.top/Article/details/gt2yopiymdi.html

[Q49] 更新单行
来源：http://dali.dianchejie.cn/Article/details/gt2hxkvastj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gt2deltuloz.html

[Q50] 批量更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvpjeaku.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gt2moxhtkqo.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gt2gfegmkyx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gt2dpwvddsp.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gt2lfoagpqj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gt2mzakurkp.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gt2xpcfkles.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hywenlv.cn/Article/details/gt2deulctuv.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gt2qbxlmauj.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258888.top/Article/details/gt2gdctgopw.html

[Q55] 排名（并列占位）
来源：http://dali.c1oappe.top/Article/details/gt2jofbzxbn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2fllloliy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xziqi.cn/Article/details/gt2gleakpqd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gt2qfsircmo.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jocskeye.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2ilhxfnxt.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttymieqk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2rxswbckw.html

[Q59] 分组内累计
来源：http://dali.birdmap.top/Article/details/gt2etckjnmr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2emgmfcdy.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuxming.cn/Article/details/gt2qnfaunrk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aibaodan.cn/Article/details/gt2swmsxtmn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2itnwruhj.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gt2wzmiizrh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2kcrhzlzm.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gt2gaepjjxh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gt2pwaoqlfx.html

[Q63] 开启事务
来源：http://dali.fengsongda.top/Article/details/gt2jlrevqlx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gt2qduaehju.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qudumlad.html

COMMIT;
来源：http://dali.chenzaomai.com/Article/details/gt2fnfoeuyr.html

[Q65] 回滚事务
来源：http://dali.yj202588.top/Article/details/gt2gqdnuukg.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gt2acqzhdwr.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gt2pcybxtvv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mezlnxic.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gt2wdmexkop.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnwrmoxi.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2typyvqni.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlchapsm.html

ROLLBACK TO sp1;
来源：http://dali.guowangkeji.top/Article/details/gt2ptriwlld.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gt2uuvzhzzr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhongyouzk.top/Article/details/gt2xhjkryrz.html

[Q70] 更新统计信息
来源：http://dali.hnqzz.top/Article/details/gt2qxardvjb.html

ANALYZE TABLE users;
来源：http://dali.hywenlv.cn/Article/details/gt2cvxpmckv.html

[Q71] 查看建表语句
来源：http://dali.pycfn.com/Article/details/gt2uqtcbzfa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gt2iuljmmsa.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gt2xpqmebht.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2mntmxctr.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gt2mbqwocon.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gt2wxiwtyis.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gt2fxmawryn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sufxvd.cn/Article/details/gt2rblxiqux.html

[Q75] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2tgzwqffy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2ghxvqjuq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gt2kucwhnsk.html

[Q76] 按天统计
来源：http://dali.zhoulong.xyz/Article/details/gt2xskplgxz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ybcxt.top/Article/details/gt2rilkaoqs.html

[Q77] 时间加减
来源：http://dali.cdnleiting.top/Article/details/gt2cmcejpgu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gt2vptdsiqu.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfcqzjru.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gt2dprogfxw.html

[Q79] 字符串拼接
来源：http://dali.cashguo.top/Article/details/gt2jmulsuxq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gt2hzolmwml.html

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmadyoah.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2jiyryyju.html

[Q81] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gt2skmghaon.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gt2hkhgumor.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gt2ryksduga.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2vrecmley.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gt2xxyrylwf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2lpepbkez.html

[Q84] 去除首尾空格
来源：http://dali.jinqigufen.top/Article/details/gt2fjxqfpcb.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2ffpsdwvr.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gt2welgoexk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gt2suvmqlce.html

[Q86] 读取 JSON 字段
来源：http://dali.ivvv.top/Article/details/gt2cxupmxxb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gt2egbrqsef.html

[Q87] JSON 字段做条件
来源：http://dali.zhoulong.xyz/Article/details/gt2spwrgelx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gt2tcrtcsri.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fhmivspe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gt2lmivjeww.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2iwbpgoia.html

[Q89] 判断表是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2octpgpdr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrhhzdgo.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gt2sdoyuczi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ydzc1.top/Article/details/gt2sdniebme.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2dhelffbd.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gt2amenfimc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2esoumvxq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hcngfiar.html

#!/usr/bin/env bash
来源：http://dali.ppjwa.cn/Article/details/gt2zncmifwl.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gt2jytttieq.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gt2gjstbmbl.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gt2xmfbbvok.html

[R03] 只读变量
来源：http://dali.ybcxt.top/Article/details/gt2vuowkdee.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gt2prsnnzuh.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gt2tifedzpo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gt2bqkmpbfb.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gt2ttqhlfyn.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gt2yiufkvrt.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gt2fmayrwou.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gt2llyctgvb.html

[R07] if 判断文件
来源：http://dali.xziqi.cn/Article/details/gt2ocdwjjlt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangdashe.top/Article/details/gt2mnaxgfzu.html

[R08] 数值比较
来源：http://dali.guannengcc.top/Article/details/gt2trwqijpb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2cbduhrqb.html

[R09] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gt2hjlpsvhw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sweek.top/Article/details/gt2drqpjnkm.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gt2fzkqudlm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gt2jlrqejyz.html

[R11] case 多分支
来源：http://dali.0kj1m.cn/Article/details/gt2qqxeclvy.html

case "$1" in
来源：http://dali.jiagoushi.top/Article/details/gt2yqqtmpmi.html

start) echo "启动" ;;
来源：http://dali.ivvv.top/Article/details/gt2jujcqpte.html

stop)  echo "停止" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2doooskwo.html

*)     echo "未知命令" ;;
来源：http://dali.sysykeji.top/Article/details/gt2cyfzlnae.html

esac
来源：http://dali.hysaishi.cn/Article/details/gt2zkesnnzr.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gt2vptzzqrv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yvedp.cn/Article/details/gt2owiavfva.html

[R13] for 计数循环
来源：http://dali.vqdsnc.cn/Article/details/gt2dkjvdylj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gt2bzijczul.html

[R14] C 风格 for
来源：http://dali.shzxlz.cn/Article/details/gt2fvqmndtq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2odjokyzk.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2hknqwwkm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ydzc1.top/Article/details/gt2jtqlysor.html

[R16] until 等待条件
来源：http://dali.nanxuanxn.top/Article/details/gt2fchkirsc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gt2pxpsrcmw.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gt2cbaqjnsf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.birdmap.top/Article/details/gt2vfmltdyf.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gt2hgymzbof.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gt2qpyqwlnd.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gt2kizxjlin.html

echo "${#arr[@]}"
来源：http://dali.hfpthk.cn/Article/details/gt2yilsttzi.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkubewfz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gt2bgsplugm.html

[R21] 字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gt2cbspuhqy.html

echo "${#s}"
来源：http://dali.fengsongda.top/Article/details/gt2wceakvge.html

[R22] 截取子串
来源：http://dali.sweek.top/Article/details/gt2qnteyqsg.html

echo "${s:0:5}"
来源：http://dali.yvedp.cn/Article/details/gt2qgobcbyt.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gt2qlyfxqmb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yueranfly.top/Article/details/gt2nnfxfjde.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdwhljnh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gt2qwbmymij.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxinkj.top/Article/details/gt2zebkvosn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxinkj.top/Article/details/gt2ryjeezqy.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gt2gwjczpiv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsswjtsr.html

[R27] 算术展开
来源：http://dali.pycfn.com/Article/details/gt2fasvlrow.html

echo $((1 + 2 * 3))
来源：http://dali.pengpengdd.cyou/Article/details/gt2oikfszwn.html

[R28] 浮点运算
来源：http://dali.cqqwz.cn/Article/details/gt2mtrnctlu.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gt2jglkmmjy.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gt2wbibtozo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gt2wnwaekdw.html

[R30] 函数返回状态码
来源：http://dali.ybcxt.top/Article/details/gt2iildtfgk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhoulong.xyz/Article/details/gt2mlxuwhfo.html

[R31] 局部变量
来源：http://dali.hysaishi.cn/Article/details/gt2rohlkdwr.html

f() { local x=1; echo "$x"; }
来源：http://dali.9152youxi.cn/Article/details/gt2eoxghojk.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gt2qyrweveu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xvvyqryu.html

[R33] 捕获错误并提示行号
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfdgebsb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gt2ddhqygud.html

[R34] 退出时清理
来源：http://dali.jqgufenzy.top/Article/details/gt2wmtqjtsb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gt2kjtkrxgf.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjgumpkw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gt2hvazafoe.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gt2bqapcczd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gt2lyugezsv.html

[R37] 把输出赋给变量
来源：http://dali.jinqigufen.top/Article/details/gt2dezrpipw.html

files=$(ls -1)
来源：http://dali.ivvv.top/Article/details/gt2wmgythfe.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gt2vxshvzqk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuanzx.com/Article/details/gt2namrmpwu.html

[R39] 重定向标准输出与错误
来源：http://dali.xuanzx.com/Article/details/gt2rwbpcwmr.html

cmd > out.log 2>&1
来源：http://dali.daria6918.cn/Article/details/gt2tzyyzsrk.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gt2myzeypai.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gt2skhtqlit.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gt2wpuzyyxf.html

cmd >/dev/null 2>&1
来源：http://dali.guowangkeji.top/Article/details/gt2tticjuks.html

[R42] 输入重定向
来源：http://dali.smart0.xyz/Article/details/gt2woelqzux.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2msiszscp.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gt2zkackvcr.html

find . -name "*.log" -type f
来源：http://dali.gaohongyu789.top/Article/details/gt2rrfxvois.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gt2cetooaed.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gt2inlsyuaa.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gt2xbzncrkn.html

find . -name "*.tmp" -delete
来源：http://dali.cashguo.top/Article/details/gt2kdllvrlk.html

[R46] 递归替换文件内容
来源：http://dali.shzxlz.cn/Article/details/gt2zrmxdxyz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujmhougp.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gt2kgofofqd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gt2lryuvmto.html

[R48] awk 取指定列
来源：http://dali.cheryme.top/Article/details/gt2liuqxopa.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2nylpywfw.html

[R49] awk 带条件
来源：http://dali.jqgfzy.top/Article/details/gt2ihqlihro.html


<!-- 参考信息 -->