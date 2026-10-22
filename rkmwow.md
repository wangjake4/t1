代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhiwuduotai.top/Article/details/gtcdcdebbf.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtoxybynhm.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtbvkbanik.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gtuajbsdyi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyehhcgo.html

user_id INT NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gtegrzwzwk.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gtyvfmnvfd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gtuphbwylt.html

);
来源：http://dali.zycfv.cn/Article/details/gtjlmiaozt.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gthnpdfxmt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgufenzy.top/Article/details/gtkytvrein.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gtrnymwxkn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fzhhl.top/Article/details/gtqcyqrpfm.html

[Q05] 重命名列
来源：http://dali.jinqigufen.top/Article/details/gtjkdpnlqp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.feifeiyinyue.top/Article/details/gtmyjccaxl.html

[Q06] 删除列
来源：http://dali.c1oappe.top/Article/details/gtgrdxhlnp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gtwvohurxa.html

[Q07] 删除表
来源：http://dali.9152youxi.cn/Article/details/gtdcuynxxp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yueranfly.top/Article/details/gtfetulusf.html

[Q08] 创建普通索引
来源：http://dali.zhongyouzk.top/Article/details/gtmirzimin.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtlgmcrpuo.html

[Q09] 创建唯一索引
来源：http://dali.hongshengwenyu.top/Article/details/gtewggwpxb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtbveyymrt.html

[Q10] 插入单行
来源：http://dali.hywenlv.cn/Article/details/gtmtmwhkuu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gtskosriqt.html

[Q11] 一次插入多行
来源：http://dali.jqgufenzy.top/Article/details/gtojvczxhw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tanke756.top/Article/details/gtleylaqjb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gthwpgzvls.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shangyingyoupin.top/Article/details/gttgthpkyc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuanzx.com/Article/details/gtxoalyzou.html

[Q13] 忽略重复插入
来源：http://dali.hnqzz.top/Article/details/gtfdaphaon.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.svipenyu.cn/Article/details/gteaqrrxco.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gteimcgljc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangdashe.top/Article/details/gtzdceeslb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.c1oappe.top/Article/details/gtxaadfrul.html

[Q15] 查询全部
来源：http://dali.xziqi.cn/Article/details/gtasfukoed.html

SELECT * FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtmjuhpyqz.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdstctqz.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtqxmapwah.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gtankrjecq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgfzy.top/Article/details/gtodqlyhcx.html

[Q18] 模糊匹配
来源：http://dali.jianghu66.top/Article/details/gtsjaqveyc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daxiang520.top/Article/details/gtmbbjxplh.html

[Q19] 范围查询
来源：http://dali.meibo888.top/Article/details/gtbwyhdarv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xziqi.cn/Article/details/gtdgjqzzcc.html

[Q20] IN 列表
来源：http://dali.tanke756.top/Article/details/gtcbqykzaz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklfeqmaj.html

[Q21] 空值判断
来源：http://dali.gzhubu.top/Article/details/gtczlfjbls.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gtfzlnlgsq.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gtqgfsibaz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gtnbyrguwj.html

[Q23] 分页
来源：http://dali.tian-w.cn/Article/details/gtohwqqiuu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shzxlz.cn/Article/details/gtrtqrgkob.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gtxgptbubv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gthgvtzdjb.html

[Q25] 只取前 N 条
来源：http://dali.nanxinkj.top/Article/details/gtcdgedlqb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnqzz.top/Article/details/gtzghuoolo.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gtnaewprke.html

SELECT COUNT(*) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtfxikfoom.html

[Q27] 条件计数
来源：http://dali.zhoulong.xyz/Article/details/gtutclyrhu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuanzx.com/Article/details/gtugvqzsoh.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gtoepbtpcd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtlhagxoof.html

[Q29] 最大最小值
来源：http://dali.sweek.top/Article/details/gtkxgmlkyo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gtokcvegkj.html

[Q30] 分组统计
来源：http://dali.nwbrower.top/Article/details/gtvmcitdht.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtpuhajodt.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gtnikdgodj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtxcjbsgbg.html

[Q32] 分组拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtzexfduvu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtdqiecpyh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gtxvgttamf.html

[Q33] 多列分组
来源：http://dali.zhixingplan.top/Article/details/gtwymquqsq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhongyouzk.top/Article/details/gtusjmvrjd.html

[Q34] 每组取第一条
来源：http://dali.tian-w.cn/Article/details/gtkidzafok.html

SELECT * FROM (
来源：http://dali.zdqjudy.top/Article/details/gtmzrafxbo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xziqi.cn/Article/details/gtnolblvam.html

) t WHERE rn = 1;
来源：http://dali.nwbrower.top/Article/details/gtonfmqidq.html

[Q35] 内连接
来源：http://dali.gzhubu.top/Article/details/gtiurkakxr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gtjdgzstop.html

[Q36] 左连接
来源：http://dali.xuetiantiany.cn/Article/details/gtusryrmbx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtrfrzeiev.html

[Q37] 右连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxiejsko.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gtyoisrtzl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cheryme.top/Article/details/gtknumbprk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gtuwjintnw.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gtfqzjyzqi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sysykeji.top/Article/details/gtdkimwyrt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.andypj.xyz/Article/details/gtbjyqekjg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gtrizailkt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gtrzvlsxox.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gtmhkanxrr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cqqwz.cn/Article/details/gtwsxrchmo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gtinkutvzs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jianghu66.top/Article/details/gtllmueuxe.html

[Q42] 连接条件附加过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmojyipq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gtggbmbuow.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ivvv.top/Article/details/gtsffealbz.html

[Q43] 标量子查询
来源：http://dali.xziqi.cn/Article/details/gtusnswzoq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gtrjmlzbeu.html

[Q44] IN 子查询
来源：http://dali.iojbl.cn/Article/details/gttqpawkkg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cdnleiting.top/Article/details/gtsmcmetvo.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxuanxn.top/Article/details/gtazwvjnrr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gtujhrucip.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gtfvrizvgw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjioytwxi.html

[Q47] 与平均值比较
来源：http://dali.zdqjudy.top/Article/details/gtwnvhwcpp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tianlin.xyz/Article/details/gtxzavglod.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gttcncwsts.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuetiantiany.cn/Article/details/gtniagetft.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenjidiqi.icu/Article/details/gtxnlztfcu.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gtpxzyygps.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtmpwqqmgf.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gtcpgkzvxp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtwjikljko.html

[Q51] 用子查询更新
来源：http://dali.sweek.top/Article/details/gtnzzdykbm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.birdmap.top/Article/details/gtjnpvfyvc.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gtgcxbhvqp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtgsunlthj.html

[Q53] 按条件删除
来源：http://dali.zhongyouzk.top/Article/details/gttjczclef.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaurlexxj.html

[Q54] 清空表
来源：http://dali.hammf.cn/Article/details/gtzroqvnqg.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gtghofjipf.html

[Q55] 排名（并列占位）
来源：http://dali.hnqzz.top/Article/details/gtfjrbtdii.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepwxbehm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqkawcqx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtcqouzjct.html

[Q57] 行号
来源：http://dali.svipenyu.cn/Article/details/gtrmestqzs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gtscvcexnw.html

[Q58] 累计求和
来源：http://dali.xziqi.cn/Article/details/gtoqiynjyk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtubyfulgl.html

[Q59] 分组内累计
来源：http://dali.svipenyu.cn/Article/details/gthlfksmni.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydpfeijt.html

[Q60] 取上一行 / 下一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfsbflct.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.mhx1999.top/Article/details/gtqttzpplq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjlzvisc.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gtzwliggdy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtfknkbhyp.html

[Q62] 分组占比
来源：http://dali.birdmap.top/Article/details/gtaymlxpmc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtikfapton.html

[Q63] 开启事务
来源：http://dali.dianchejie.cn/Article/details/gtgsrrdgaa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gtvoakdjpu.html

[Q64] 提交事务
来源：http://dali.smart0.xyz/Article/details/gtmbcwvqau.html

COMMIT;
来源：http://dali.tanke756.top/Article/details/gtaxgyvvpx.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gtqpjzgnxb.html

ROLLBACK;
来源：http://dali.kuanghao11.cn/Article/details/gtpiwohwnx.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gtuwbvkmpt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gtqksuslen.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gtopcnwqpu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnxiangtu.top/Article/details/gtnplsfehr.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gtqmlkaywf.html

SAVEPOINT sp1;
来源：http://dali.jianghu66.top/Article/details/gteuiiafee.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gtzpmlwcbh.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gthkstbjrw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gtwdoljwqy.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyukekpm.html

ANALYZE TABLE users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtceznjlyp.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gtieliuvwz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxinkj.top/Article/details/gtemwuymxh.html

[Q72] 查看索引
来源：http://dali.gzhubu.top/Article/details/gtwvzngfax.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gtzorydank.html

[Q73] 查看表状态
来源：http://dali.hfpthk.cn/Article/details/gtezrpcutf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gtlqdewrpa.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gtmldcvqhf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aibaodan.cn/Article/details/gtzoohyixa.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtgholoote.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtrrecgdgq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenzaomai.com/Article/details/gtgqbpjqkl.html

[Q76] 按天统计
来源：http://dali.mhx1999.top/Article/details/gtmzdjxemq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gtpsyaixsh.html

[Q77] 时间加减
来源：http://dali.nwbrower.top/Article/details/gtlsbfoneb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.9152youxi.cn/Article/details/gtebjuceky.html

[Q78] 当前时间
来源：http://dali.nanxinkj.top/Article/details/gtcoaxbilj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hongshengwenyu.top/Article/details/gtnsdkjaps.html

[Q79] 字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gtcqittdnu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daxiang520.top/Article/details/gtmvcjqdct.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gtjagjoehh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtifeconkh.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejifpsbr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gtegjsobgq.html

[Q82] 字符长度与字节长度
来源：http://dali.sysykeji.top/Article/details/gtwwbiuyzz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtzzhxhthm.html

[Q83] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtezsrexse.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtzjahklrd.html

[Q84] 去除首尾空格
来源：http://dali.nwbrower.top/Article/details/gtduyqiogr.html

SELECT TRIM(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtlkrptmex.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gtqsbojuyf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dashuyun.cn/Article/details/gtzzfuppqw.html

[Q86] 读取 JSON 字段
来源：http://dali.cdnleiting.top/Article/details/gtoxlgjxfs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.andypj.xyz/Article/details/gtiwphlefu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gtdyietaqx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhongyouzk.top/Article/details/gtqjpekvue.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gtykxvutqa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtniydtgbb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtoeuacoiq.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gtjsaswwkb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hfpthk.cn/Article/details/gttcqxdsxt.html

[Q90] 生成序号列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqwpfjlm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvccnbcq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjiihfxfr.html

R. Bash 专题
来源：http://dali.kuanghao11.cn/Article/details/gtuxbkxtox.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtbiicakws.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtgkdmubku.html

#!/usr/bin/env bash
来源：http://dali.aizwys.cn/Article/details/gtmyjrukad.html

set -euo pipefail
来源：http://dali.zhiwuduotai.top/Article/details/gtmwynxnph.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gttdpunhui.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gthnugirbi.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gtgnvknorv.html

readonly PI=3.14
来源：http://dali.chenzaomai.com/Article/details/gtqvwgmwye.html

[R04] 位置参数
来源：http://dali.daria6918.cn/Article/details/gtxbmsnubd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtvaumkuti.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gtosoccwpk.html

name="${1:-default}"
来源：http://dali.tanke756.top/Article/details/gtjsyzekgs.html

[R06] 判断命令是否存在
来源：http://dali.nwbrower.top/Article/details/gtmiivovpm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gtacfkfflb.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtyjszqluj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gogol.net.cn/Article/details/gtjgnmogbs.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gtbkfrbinu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cqqwz.cn/Article/details/gtubvvimmv.html

[R09] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtbblkqzpb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtcmeovuti.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gthvakjbdr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gtbmfplqbx.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gtwtmzmqxw.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gtukbbpdnu.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gtcouwaprl.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gtcxqrdmyi.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtahawxdtk.html

esac
来源：http://dali.hongshengwenyu.top/Article/details/gtimbakyei.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gtrrsmaxdn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.c1oappe.top/Article/details/gtycmcuxfl.html

[R13] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvegrbws.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtnysdglvg.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gtkypbrivx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtdzuxeljj.html

[R15] while 逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtmhuercjv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gtdqehjdwx.html

[R16] until 等待条件
来源：http://dali.zycfv.cn/Article/details/gtvmbbvkmj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtihcsewjg.html

[R17] 数组定义与取值
来源：http://dali.kuanghao11.cn/Article/details/gtgmhyyqak.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.bjfxy.top/Article/details/gtbkasejii.html

[R18] 遍历数组
来源：http://dali.jyoumei.cn/Article/details/gtvzzzrhez.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gtcuxquipa.html

[R19] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtntzobzbk.html

echo "${#arr[@]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtxfldsvrb.html

[R20] 关联数组（字典）
来源：http://dali.bjfxy.top/Article/details/gtdxrzlygy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gtmquykite.html

[R21] 字符串长度
来源：http://dali.meibo888.top/Article/details/gtpxuyjqzm.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gthhzsiggq.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtysoezmvt.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gtcziplsjd.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzzchvkk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmmxyuch.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gttjkasoeh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtvrjuxoql.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtreuaxvoi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gtqogwsysz.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gtvpokpsiu.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gttilywwbx.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gtvceunddi.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gtfevmrplm.html

[R28] 浮点运算
来源：http://dali.jinqigufen.top/Article/details/gtjerftzxf.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gtyelgxycz.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtiwjwffny.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gtkahvzduh.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gtykjzmhuv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gtbcwvhawe.html

[R31] 局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gtflgkfrhv.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gtpxiowniy.html

[R32] 参数个数校验
来源：http://dali.yuanzhike.top/Article/details/gtzmkbdkhp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtihjqfaki.html

[R33] 捕获错误并提示行号
来源：http://dali.gotoacloud.top/Article/details/gtcsvnicll.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.svipenyu.cn/Article/details/gtsjagcpij.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpzvzlwb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtpqtzavwg.html

[R35] 后台执行并等待
来源：http://dali.gotoacloud.top/Article/details/gtmrbxokxa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.316326.xyz/Article/details/gtitlwpyug.html

[R36] 并发执行多个任务
来源：http://dali.tanke756.top/Article/details/gtoikghtrd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gtxbngexty.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gtrufjeztm.html

files=$(ls -1)
来源：http://dali.yuxming.cn/Article/details/gthubcwdmx.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gtvadbppbp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtgqxnstsy.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gtoigjifnk.html

cmd > out.log 2>&1
来源：http://dali.c1oappe.top/Article/details/gtpsyyssxx.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyjtkuww.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gtpsuepapa.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gtkinfaqtg.html

cmd >/dev/null 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtbilpylaz.html

[R42] 输入重定向
来源：http://dali.jinghuilouyu.cn/Article/details/gtqojlohgw.html

wc -l < a.txt
来源：http://dali.9152youxi.cn/Article/details/gtclewptrj.html

[R43] 按名字查找文件
来源：http://dali.xylfe.cn/Article/details/gtskfjwjnu.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtgvbhwfap.html

[R44] 按修改时间查找
来源：http://dali.daria6918.cn/Article/details/gtlcbyejfc.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtcudqqygj.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gtymkxlygd.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gtbqxgvfyk.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gtbbpgypox.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gtnknmpzbf.html

[R47] sed 单行替换
来源：http://dali.dianchejie.cn/Article/details/gtlictlimb.html


<!-- 参考信息 -->