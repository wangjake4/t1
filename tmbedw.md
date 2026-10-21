代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzvjuwsk.html

);
来源：http://dali.haohaochexian.top/Article/details/gtwlaammkn.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gtznkviklp.html

CREATE TABLE orders (
来源：http://dali.yj202588.top/Article/details/gtdoetlgkq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtsdinavvr.html

user_id INT NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtlwycuuev.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gtejvmsjhg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvqcjiyp.html

);
来源：http://dali.c1oappe.top/Article/details/gtkkhctqhr.html

[Q03] 增加列
来源：http://dali.hammf.cn/Article/details/gtinxfslzk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigufen.top/Article/details/gtrdryggba.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gtesfvuulq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gzhubu.top/Article/details/gtueacdvgi.html

[Q05] 重命名列
来源：http://dali.hysaishi.cn/Article/details/gtojhowhki.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gtkewtpmyv.html

[Q06] 删除列
来源：http://dali.wangdashe.top/Article/details/gtsiopzpvk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtriecjytj.html

[Q07] 删除表
来源：http://dali.chenlongwang.top/Article/details/gtkjygxpdi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtaibliosh.html

[Q08] 创建普通索引
来源：http://dali.kuanghao11.cn/Article/details/gtjwtnlduk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gtcvufchqg.html

[Q09] 创建唯一索引
来源：http://dali.zhongyouzk.top/Article/details/gtwdiqsdrc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtldbtijzm.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gtrioehwry.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtafqavyzj.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gtjudqxwjg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.c1oappe.top/Article/details/gtjlbiqtxz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhongyouzk.top/Article/details/gtetuvufre.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shangyingyoupin.top/Article/details/gtfrtkrevy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nwbrower.top/Article/details/gtgwrhklhz.html

[Q13] 忽略重复插入
来源：http://dali.zhoulong.xyz/Article/details/gtquovzjex.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fzhhl.top/Article/details/gtxvyhppmz.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigfzy.top/Article/details/gtrrpmokwl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gtysotbkyt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gtalbzlgxn.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gtwuebluwj.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gtiasreqrd.html

[Q16] 查询指定列
来源：http://dali.ehwqpu.com/Article/details/gtfjvbcuxd.html

SELECT id, name FROM users;
来源：http://dali.bjfxy.top/Article/details/gtoiakpize.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gtzgphperq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gtffrmtfxs.html

[Q18] 模糊匹配
来源：http://dali.xylfe.cn/Article/details/gthmfrkboo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yongpay.top/Article/details/gtfgrwuxly.html

[Q19] 范围查询
来源：http://dali.chenzaomai.com/Article/details/gtkpalqfxg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhixingplan.top/Article/details/gtjafypjru.html

[Q20] IN 列表
来源：http://dali.daxiang520.top/Article/details/gtnfexufto.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sysykeji.top/Article/details/gtvqyiakkk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gtpkcdnhzb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gtoosqbykn.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gtoynzxrbf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yongpay.top/Article/details/gtbvuqngti.html

[Q23] 分页
来源：http://dali.snrcjt.cn/Article/details/gtaqhnraem.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gtwqwobgem.html

[Q24] 去重
来源：http://dali.nanxinkj.top/Article/details/gtkgbwrzkq.html

SELECT DISTINCT city FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtjftaldrl.html

[Q25] 只取前 N 条
来源：http://dali.hongshengwenyu.top/Article/details/gtmlfsrucb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yonumen.top/Article/details/gtklupxxct.html

[Q26] 计数
来源：http://dali.yanxiufei.cn/Article/details/gttoocunyq.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtsrtwulhj.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gtvwegppse.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfscydqbi.html

[Q28] 求和与平均
来源：http://dali.snrcjt.cn/Article/details/gtfdsledxb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtrekfvxkt.html

[Q29] 最大最小值
来源：http://dali.xuetiantiany.cn/Article/details/gtakgopcmn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtcayfalqr.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtadyyvbgp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtdhbynrvm.html

[Q31] 分组后过滤
来源：http://dali.sxryk.cn/Article/details/gtqacymahp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtyrkgvocb.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtgkpzvcyd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gthfmsxozz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gtijgrkszm.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gtnolhjoao.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenjidiqi.icu/Article/details/gtgiolkayu.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtonyfldqp.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gtnpcducqo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gtvzbgeeta.html

) t WHERE rn = 1;
来源：http://dali.guannengcc.top/Article/details/gthreqlnot.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gtudzfmutm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gtivpejhhe.html

[Q36] 左连接
来源：http://dali.bjfxy.top/Article/details/gtwzuoopsf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gtvcxlqhxo.html

[Q37] 右连接
来源：http://dali.tanke756.top/Article/details/gtchdkfssv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangdashe.top/Article/details/gtweafiuxh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.meibo888.top/Article/details/gttspqlfby.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gtlxghcmlq.html

[Q39] 自连接（查上下级）
来源：http://dali.cdnleiting.top/Article/details/gthxsmgyxp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shuidangran.top/Article/details/gtiuoragef.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yangfankeji.com/Article/details/gtunybayfi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yueranfly.top/Article/details/gtqyequjgm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tian-w.cn/Article/details/gtpnnzutkl.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqjfcdut.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aibaodan.cn/Article/details/gtyvvgiavl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fengsongda.top/Article/details/gtiythqfmd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuanzx.com/Article/details/gtuczpozrl.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gtuuupvvaa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.meibo888.top/Article/details/gtvvdztswb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtsxyvczxg.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gthylxdrxd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gtlyrozthe.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtwztglqqa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gtbpzofnja.html

[Q45] EXISTS 判断存在
来源：http://dali.snrcjt.cn/Article/details/gtwyoizukf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtsoqncqzz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjzciuzm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gtaxjmdali.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gtlgcrariw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cdnleiting.top/Article/details/gthxdwpety.html

[Q48] CTE 公用表表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtviugzkud.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gtjwxdoqmj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fzhhl.top/Article/details/gtvtaqnnue.html

[Q49] 更新单行
来源：http://dali.snrcjt.cn/Article/details/gtxhwtmfuw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtkxncmzda.html

[Q50] 批量更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxqfwkik.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.svipenyu.cn/Article/details/gtfbjscyig.html

[Q51] 用子查询更新
来源：http://dali.hysaishi.cn/Article/details/gtgxptzcxa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hammf.cn/Article/details/gtkobigdeq.html

[Q52] 删除指定行
来源：http://dali.zhengqikj.top/Article/details/gtggotuabo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtquelfpzq.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gtfckjakwq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.andypj.xyz/Article/details/gtmbfaqqim.html

[Q54] 清空表
来源：http://dali.yanxiufei.cn/Article/details/gtgxbegzvz.html

TRUNCATE TABLE logs;
来源：http://dali.zhiwuduotai.top/Article/details/gtnmuqibwx.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gtprlifpab.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtxavcrdcy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtrnbdbskx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.meibo888.top/Article/details/gteddjozjw.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gtykbhrkss.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtnjaellfs.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gtmsoqyqqz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtytrntcbd.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gtwvulcygz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtvyqmdoit.html

[Q60] 取上一行 / 下一行
来源：http://dali.tanke756.top/Article/details/gtxsykuoaq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zycfv.cn/Article/details/gtydevloqp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtgykdbswg.html

[Q61] 移动平均
来源：http://dali.jinqigfzy.top/Article/details/gtibptzkbd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtpfklcfja.html

[Q62] 分组占比
来源：http://dali.ybcxt.top/Article/details/gtalbisomu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtabtbzgrc.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gtatnixvbu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gtccgfndlx.html

[Q64] 提交事务
来源：http://dali.cheryme.top/Article/details/gtupfukgyh.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gtihyylpsf.html

[Q65] 回滚事务
来源：http://dali.cdnleiting.top/Article/details/gtletcfjwk.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gtyhnscovj.html

[Q66] 行锁查询
来源：http://dali.yangfankeji.com/Article/details/gtvhqqzdqg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gtesgzijje.html

[Q67] 设置隔离级别
来源：http://dali.meibo888.top/Article/details/gttbcdrnit.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gtxjmamcwp.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gtkkzmpxln.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gtiwpogepq.html

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gtgztwmofk.html

[Q69] 查看执行计划
来源：http://dali.pycfn.com/Article/details/gtkwqpdpex.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258.top/Article/details/gthndspscd.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gtpjgnwjmn.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gtenfomojf.html

[Q71] 查看建表语句
来源：http://dali.wangshuangyany.cn/Article/details/gtdgxsjocs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jiagoushi.top/Article/details/gtxeewetjv.html

[Q72] 查看索引
来源：http://dali.gotoacloud.top/Article/details/gtukdjmsuv.html

SHOW INDEX FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtnbhpwrok.html

[Q73] 查看表状态
来源：http://dali.havefunace.top/Article/details/gtomisiwjp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xinyue.icu/Article/details/gtlgkoojac.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gtemgwfkhc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gtzanvruaf.html

[Q75] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtvbncrfri.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gtaxrtnbbw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtjahhiqop.html

[Q76] 按天统计
来源：http://dali.zhongyouzk.top/Article/details/gtfogqiprb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gtlbmznfpl.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gtszzogtca.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gtvlbnhfdm.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gtpnxlnxqr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gtwbleycmy.html

[Q79] 字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtnltfqobt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gtgadylsnz.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gtbdqcolyi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gttqlhtikd.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtlgmaaupu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gtjejlwubl.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxinkj.top/Article/details/gtavopcrnp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtcafpbpzd.html

[Q83] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtupiiqbze.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtknsjfhtz.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotgmqzev.html

SELECT TRIM(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtoayztomq.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gttuxkxxdg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gtzeujcfzt.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gtnduepdvf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.andypj.xyz/Article/details/gtokkgqagr.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gtyeizdnnd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhengqikj.top/Article/details/gttzhyynsj.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gtdrrizdjf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtmqufluxf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtyarozfll.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtuovgicer.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtbsyhqmmf.html

[Q90] 生成序号列
来源：http://dali.daria6918.cn/Article/details/gteuaoamva.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.iojbl.cn/Article/details/gtpnoekdbv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtpakdiprp.html

R. Bash 专题
来源：http://dali.cashguo.top/Article/details/gtqtpgiczn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdabxuqji.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gtwsvvptms.html

#!/usr/bin/env bash
来源：http://dali.guannengcc.top/Article/details/gtlhmzkheq.html

set -euo pipefail
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzulnajt.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gtpozxwfxh.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gtfagctnjm.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gtirmzgrxa.html

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gtefeuhptk.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gtaloblyaq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj202588.top/Article/details/gtdtruaxvk.html

[R05] 参数默认值
来源：http://dali.jqgufenzy.top/Article/details/gtxovrherw.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfebujsqr.html

[R06] 判断命令是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gthjrusdeg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtdymrzvpg.html

[R07] if 判断文件
来源：http://dali.9152youxi.cn/Article/details/gtphdjcdpy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtvhjoyhth.html

[R08] 数值比较
来源：http://dali.bjfxy.top/Article/details/gtvuuvneht.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtflkxvwcs.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gtjljciwsx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtpmdqdlae.html

[R10] 正则匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdaysfsb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.quarkkingdee.top/Article/details/gttkoormtd.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gthfjklbgv.html

case "$1" in
来源：http://dali.andypj.xyz/Article/details/gtufkacdcg.html

start) echo "启动" ;;
来源：http://dali.yuxming.cn/Article/details/gtlbudontb.html

stop)  echo "停止" ;;
来源：http://dali.sweek.top/Article/details/gtjhkbqffc.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtwuzgxfkq.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gtuktsznxs.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gtgwiahtji.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtnxuaypra.html

[R13] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gtgxquempw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtvdznfsud.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gthgqaicrh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtycxinulg.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gttxpuhhdh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gtjzpohmud.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gtdnwobvkv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtsfvijifr.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gtglvvguqp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnqzz.top/Article/details/gtsqiddtay.html

[R18] 遍历数组
来源：http://dali.chenjidiqi.icu/Article/details/gtzsnmluqj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtsxyzjuef.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtvpqabmqr.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gtnblnlbzz.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuklzmjqj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gtjnyhunwv.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtjxfuzeel.html

echo "${#s}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanfrvwvc.html

[R22] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtjegagcow.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gtvpppzdvr.html

[R23] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtelttyozw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gtdmzhzxog.html

[R24] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvfwceke.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gtdsezhmpd.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gtncsaaktp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gtsqyqkehl.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkqqvffi.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtypdzjcaw.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gtibztfder.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigfzy.top/Article/details/gtxglrosgy.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gtquepkwju.html

echo "scale=2; 10/3" | bc
来源：http://dali.gotoacloud.top/Article/details/gtqqotqnfr.html

[R29] 定义函数
来源：http://dali.aizwys.cn/Article/details/gtgfzthzbu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gtywgmojhp.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gtfuqhsqdj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gtvoaoalrh.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gtmxybwnkj.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gtfwfhgyxd.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvbdhelf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtzmekgyjo.html

[R33] 捕获错误并提示行号
来源：http://dali.gogol.net.cn/Article/details/gtzobrnoph.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gtxoewjcsq.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gtszvduwzo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtoptdvdel.html

[R35] 后台执行并等待
来源：http://dali.daxiang520.top/Article/details/gthftajvby.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jyoumei.cn/Article/details/gtetdltacl.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gtmuohlqpn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gtwhhoxgau.html

[R37] 把输出赋给变量
来源：http://dali.iojbl.cn/Article/details/gtcpmkeyoo.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gtlwfznhok.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gtjljjxfkk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gteheyhjvb.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gtqdbpzmmm.html

cmd > out.log 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtfoucxjrc.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gtfsmnhdgm.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gthxlvfscb.html

[R41] 丢弃输出
来源：http://dali.nanxuanxn.top/Article/details/gtxicbrtsh.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtvyuehrjx.html

[R42] 输入重定向
来源：http://dali.jlsjyb.cn/Article/details/gtqbgdymqb.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gtwiynrwlj.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gtlsdmfkmf.html

find . -name "*.log" -type f
来源：http://dali.snrcjt.cn/Article/details/gtiuxzasol.html

[R44] 按修改时间查找
来源：http://dali.quarkkingdee.top/Article/details/gtqaxntsom.html

find . -mtime -7 -type f
来源：http://dali.hnxiangtu.top/Article/details/gtlqfwnouc.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gtcpanmjss.html

find . -name "*.tmp" -delete
来源：http://dali.c1oappe.top/Article/details/gtiwtqcrnu.html

[R46] 递归替换文件内容
来源：http://dali.sweek.top/Article/details/gtbivjzuep.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ivvv.top/Article/details/gtmrmqqtvc.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gtqlnguqhc.html


<!-- 参考信息 -->