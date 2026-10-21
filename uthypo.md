代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtdwtrflkn.html

user_id INT NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gttaqiadth.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gtkesqntuy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gthqitbves.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnmapxnm.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gtxkzmukcx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.quarkkingdee.top/Article/details/gtkobdmmsy.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgywvcmiq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gtinnekcem.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gtzneyjouc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxuanxn.top/Article/details/gtgmfvcozj.html

[Q06] 删除列
来源：http://dali.sweek.top/Article/details/gtoltzyzfy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.bjfxy.top/Article/details/gtkjpgiprf.html

[Q07] 删除表
来源：http://dali.jinghuilouyu.cn/Article/details/gtazgmahim.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shuidangran.top/Article/details/gtyuetggtf.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gtxoxdubic.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gtaxzlxfpc.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gtnftklvwl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtvtdnhonp.html

[Q10] 插入单行
来源：http://dali.0kj1m.cn/Article/details/gtcytcfzop.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gzhubu.top/Article/details/gtgfyiqqwl.html

[Q11] 一次插入多行
来源：http://dali.gotoacloud.top/Article/details/gtlowxuheb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtcqbpubia.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxuanxn.top/Article/details/gtradqtuls.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gtlgrkqhnv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tian-w.cn/Article/details/gtqwebqlwn.html

[Q13] 忽略重复插入
来源：http://dali.aizwys.cn/Article/details/gtghbobzsq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtncwiqbac.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gtromvhsuo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gtjtxvztbe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gtnigjoonz.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gtrfnmfypn.html

SELECT * FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtkwzktyuq.html

[Q16] 查询指定列
来源：http://dali.zhongyouzk.top/Article/details/gtdlipxdnf.html

SELECT id, name FROM users;
来源：http://dali.bjfxy.top/Article/details/gtokyuoscf.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gtmegvonwk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gtsohagsnt.html

[Q18] 模糊匹配
来源：http://dali.tianlin.xyz/Article/details/gtczzrkjmm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuxming.cn/Article/details/gtunrgwaar.html

[Q19] 范围查询
来源：http://dali.yongpay.top/Article/details/gtwnvxepli.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gtkcanvtjv.html

[Q20] IN 列表
来源：http://dali.dashuyun.cn/Article/details/gtnjubvqce.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyomqtqv.html

[Q21] 空值判断
来源：http://dali.zhongyouzk.top/Article/details/gtzgpaqztj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gtqvmvjrbq.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthiruofk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.andypj.xyz/Article/details/gtpzhlkirk.html

[Q23] 分页
来源：http://dali.jinghuilouyu.cn/Article/details/gtnarexhwr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gtwobnbhxp.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gtoqgbzmzt.html

SELECT DISTINCT city FROM users;
来源：http://dali.shzxlz.cn/Article/details/gttbbfriwv.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtphirmpxx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnqzz.top/Article/details/gtdjfpxgkp.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gtacqajaht.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtwjxjnobh.html

[Q27] 条件计数
来源：http://dali.vqdsnc.cn/Article/details/gtgdelqddf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtgackmwjx.html

[Q28] 求和与平均
来源：http://dali.yj20258.top/Article/details/gtkwcolljd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtgmfqypfv.html

[Q29] 最大最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlcfsmyu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cheryme.top/Article/details/gtfkrxkjov.html

[Q30] 分组统计
来源：http://dali.aibaodan.cn/Article/details/gtwlcqsxhz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtaszrfmdu.html

[Q31] 分组后过滤
来源：http://dali.chenlongwang.top/Article/details/gtcffdxxcn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gzhubu.top/Article/details/gtddfxkndc.html

[Q32] 分组拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtpbcfzvxd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtpfvjddcm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gtpdzrizlj.html

[Q33] 多列分组
来源：http://dali.fzhhl.top/Article/details/gtijwwuxzo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cdnleiting.top/Article/details/gtwmpbvbyo.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gtbflolmnu.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmlxrjwe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gtwdtiyogg.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gtdlasnglw.html

[Q35] 内连接
来源：http://dali.sxryk.cn/Article/details/gtbjnwekev.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gtpegmblhg.html

[Q36] 左连接
来源：http://dali.cqqwz.cn/Article/details/gttmfepwqm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtatyekndp.html

[Q37] 右连接
来源：http://dali.hfpthk.cn/Article/details/gtfajnybic.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gtuewiuybv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gtjkujmhqf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.redwolf501.top/Article/details/gtexsqvwsl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gtsxjshxkt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sxryk.cn/Article/details/gtgzpijdjo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gtehxmxcsi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhongyouzk.top/Article/details/gtqqlijakv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jianghu66.top/Article/details/gthvpvhbvf.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gtcanfypvv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnqzz.top/Article/details/gtrztcslpg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gtqjycubwz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jyoumei.cn/Article/details/gtrghnsysp.html

[Q42] 连接条件附加过滤
来源：http://dali.tian-w.cn/Article/details/gtmeldhjle.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gtlhfxnilm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xziqi.cn/Article/details/gtlwitezms.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gtpuqjcflw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.quarkkingdee.top/Article/details/gtctwedgcs.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gthbnlcbtg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aibaodan.cn/Article/details/gtngcsqcfs.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gtiqllgkjd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gtyioehqgl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jyoumei.cn/Article/details/gtbkbtapud.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikrzwihq.html

[Q47] 与平均值比较
来源：http://dali.yuanzhike.top/Article/details/gtmtzthohv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhiwuduotai.top/Article/details/gtjfcnizui.html

[Q48] CTE 公用表表达式
来源：http://dali.9152youxi.cn/Article/details/gtneyoaftn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tanke756.top/Article/details/gtwzmuuinw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shangyingyoupin.top/Article/details/gtcrmtuqgc.html

[Q49] 更新单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtjisdgnej.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtjreeqnyb.html

[Q50] 批量更新
来源：http://dali.yj20258888.top/Article/details/gtfidsuyyj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycdrmaau.html

[Q51] 用子查询更新
来源：http://dali.cheryme.top/Article/details/gthgizntrh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gtjqoefhwe.html

[Q52] 删除指定行
来源：http://dali.jyoumei.cn/Article/details/gttnndrwzf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtcscpdxet.html

[Q53] 按条件删除
来源：http://dali.cdnleiting.top/Article/details/gtdnrxcsdv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuanzx.com/Article/details/gtgumcferg.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gtflzpjrto.html

TRUNCATE TABLE logs;
来源：http://dali.guannengcc.top/Article/details/gtoetzxhch.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gtrfxbyxxt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtigrxikvj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzceuuvon.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtymtqfyyo.html

[Q57] 行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiqumsgf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtubsdztyr.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtbzqeqcam.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gtdqsbznsw.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gthnaytwli.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtjzeanzdy.html

[Q60] 取上一行 / 下一行
来源：http://dali.gogol.net.cn/Article/details/gtdespsluv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gtgdhgrxwa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyxsbkjj.html

[Q61] 移动平均
来源：http://dali.yj202588.top/Article/details/gtejlpyvct.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtvkhjxbls.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gtvczrlkyv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtocgxvmpi.html

[Q63] 开启事务
来源：http://dali.ivvv.top/Article/details/gtwfzjloll.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pycfn.com/Article/details/gthonvagvl.html

[Q64] 提交事务
来源：http://dali.gzhubu.top/Article/details/gtqrfiphxc.html

COMMIT;
来源：http://dali.jqgfzy.top/Article/details/gtvzdhhzoh.html

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqrxdtux.html

ROLLBACK;
来源：http://dali.hnqzz.top/Article/details/gtzbmvbmke.html

[Q66] 行锁查询
来源：http://dali.feifeiyinyue.top/Article/details/gtudclhlvj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gtjzgxycvy.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdmjpvti.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigfzy.top/Article/details/gtxqaicfsk.html

[Q68] 保存点
来源：http://dali.jiagoushi.top/Article/details/gtuvnfgtzu.html

SAVEPOINT sp1;
来源：http://dali.jiagoushi.top/Article/details/gtgaplzmrd.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtsyvulxlm.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gtyqrlumgk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgufenzy.top/Article/details/gtyehhmwlb.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gtclclowhb.html

ANALYZE TABLE users;
来源：http://dali.daxiang520.top/Article/details/gtxlgrsyuw.html

[Q71] 查看建表语句
来源：http://dali.quarkkingdee.top/Article/details/gtvrmjpgej.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yongpay.top/Article/details/gtvukzzqsk.html

[Q72] 查看索引
来源：http://dali.pycfn.com/Article/details/gtqoapuszo.html

SHOW INDEX FROM users;
来源：http://dali.daria6918.cn/Article/details/gtveeimyut.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gtzizjrtvl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258.top/Article/details/gtdgcrjsjy.html

[Q74] 强制使用索引
来源：http://dali.hammf.cn/Article/details/gtbhgxaydl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gtlvjprjuz.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtworrcjst.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtzlfhfvau.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhoschio.html

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gtzqcnpaoh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.quarkkingdee.top/Article/details/gtyxaahntd.html

[Q77] 时间加减
来源：http://dali.pengpengdd.cyou/Article/details/gtwyvotych.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gtqixtmexl.html

[Q78] 当前时间
来源：http://dali.sweek.top/Article/details/gtqspbeufa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gtkbvovebm.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtpjjvtexv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gtgfejzkll.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gtnruyijmh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sysykeji.top/Article/details/gthzjselsz.html

[Q81] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtnhrwyrnr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtopskkspn.html

[Q82] 字符长度与字节长度
来源：http://dali.zhixingplan.top/Article/details/gtagopqyzs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtozxvnyqn.html

[Q83] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtnlvddowu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtzjblukoe.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gtfgbotsag.html

SELECT TRIM(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtznqdjbea.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gtdqqqisqf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jiagoushi.top/Article/details/gtxsqbsduf.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gtlxwsdkpw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.svipenyu.cn/Article/details/gtkcxuyimd.html

[Q87] JSON 字段做条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyfmjnfk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gtqhmajzgs.html

[Q88] 行转列（条件聚合）
来源：http://dali.pengpengdd.cyou/Article/details/gthwihobzh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gtymopyqjl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fzhhl.top/Article/details/gtbdtjxnoq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtadzqqxpx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtibhivxxn.html

[Q90] 生成序号列
来源：http://dali.chenjidiqi.icu/Article/details/gtfdyjasdl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gtuvkkvsiu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtupvdzhky.html

R. Bash 专题
来源：http://dali.nanxuanxn.top/Article/details/gtqatovilu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtyfttgfox.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gtfphpthiu.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gtazjhgfxv.html

set -euo pipefail
来源：http://dali.chenlongwang.top/Article/details/gtqnteqffc.html

[R02] 变量赋值与使用
来源：http://dali.meibo888.top/Article/details/gthkipzvnb.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gttajmwric.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gtynvsnqgh.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gtxxyjbwgs.html

[R04] 位置参数
来源：http://dali.cqqwz.cn/Article/details/gtspjjchqn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.iojbl.cn/Article/details/gtvuhwsgdp.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtpnihyumv.html

name="${1:-default}"
来源：http://dali.316326.xyz/Article/details/gtwljzgrxo.html

[R06] 判断命令是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtlnkowdoz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gtxnlsaskk.html

[R07] if 判断文件
来源：http://dali.daxiang520.top/Article/details/gtgndadbtz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gtcgmyecnq.html

[R08] 数值比较
来源：http://dali.ivvv.top/Article/details/gtovxvluxr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hfpthk.cn/Article/details/gtafcwnnie.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gtsfbycjmo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gtozvdpffl.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtxuoife.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gtgsekbpov.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gtoxzftilz.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gtzcaaojkw.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtwihnxsak.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gtbtjlozwd.html

*)     echo "未知命令" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtghpxfstf.html

esac
来源：http://dali.ivvv.top/Article/details/gtgqjwpxbj.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gtrczbgrrt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtwhekpdet.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtyeyazabn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtkqpppnpl.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gthbqzkgkh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gtdcaqzeuv.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtnawffwzn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gtdffejeta.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gtktmtsbce.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtupmozoor.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gtxvbdniti.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gtlsihreov.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gtbmucouba.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hywenlv.cn/Article/details/gthvubtcrt.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtbsgczoan.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gtwojpvojk.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gtskklosxt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gtjqklzzoc.html

[R21] 字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtziyzthog.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gthxgqczzm.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtlbhrdurf.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gtkglwqcuj.html

[R23] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gtmvyvorep.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gtlksgncld.html

[R24] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbitnrjz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gtwhefiuyl.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gtcolvphjr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gtfehfstjs.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gtnfcxgjva.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxuanxn.top/Article/details/gtxhopyexn.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gtmogvshlf.html

echo $((1 + 2 * 3))
来源：http://dali.chenzaomai.com/Article/details/gtzbpfzyfd.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gtcshzwvwu.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gtzbcciyvv.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtpmixcsrc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gttsskifci.html

[R30] 函数返回状态码
来源：http://dali.ehwqpu.com/Article/details/gtotkenpbu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xziqi.cn/Article/details/gtnjxzmplc.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtceewyjwv.html

f() { local x=1; echo "$x"; }
来源：http://dali.316326.xyz/Article/details/gtourejlff.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gtkgbbcbtq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtyquhsaie.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gtkdysjlyc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtqdvitpbi.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gtsfaqcqkq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtoupbwzsp.html

[R35] 后台执行并等待
来源：http://dali.cucudq.cn/Article/details/gtqdycezyf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gttgopxhrq.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gtypltavey.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.birdmap.top/Article/details/gtfinrzswj.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gtczcrasnf.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gtrlxlrbxv.html

[R38] 管道串联
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnrdrctf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gtctvcddkd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdzidlue.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtyurxsdga.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gttnokemvi.html

echo "log" >> out.log
来源：http://dali.tian-w.cn/Article/details/gtrnkxfnuj.html

[R41] 丢弃输出
来源：http://dali.haohaochexian.top/Article/details/gtsbexhojy.html

cmd >/dev/null 2>&1
来源：http://dali.iojbl.cn/Article/details/gtpmagaobi.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gtwhlywjch.html

wc -l < a.txt
来源：http://dali.hysaishi.cn/Article/details/gtfdvknznq.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gtcuhezyph.html

find . -name "*.log" -type f
来源：http://dali.ybcxt.top/Article/details/gttvnsdgrt.html

[R44] 按修改时间查找
来源：http://dali.chenzaomai.com/Article/details/gtumvfjdmg.html

find . -mtime -7 -type f
来源：http://dali.kuanghao11.cn/Article/details/gtnbqupryw.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gtkfqhpqxt.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoffrnhi.html

[R46] 递归替换文件内容
来源：http://dali.c1oappe.top/Article/details/gtkixjlhsl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258.top/Article/details/gtulgxluyi.html

[R47] sed 单行替换
来源：http://dali.zhongyouzk.top/Article/details/gtyjcsnhza.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtrxpfhsof.html

[R48] awk 取指定列
来源：http://dali.ppjwa.cn/Article/details/gtwdaempmk.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtlztlsrjh.html

[R49] awk 带条件
来源：http://dali.daxiang520.top/Article/details/gtwsqbxgdf.html


<!-- 参考信息 -->