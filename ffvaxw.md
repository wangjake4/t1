代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhengqikj.top/Article/details/gtquhggxyk.html

[Q05] 重命名列
来源：http://dali.yuxming.cn/Article/details/gtjtvnrued.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gtbxcmxptb.html

[Q06] 删除列
来源：http://dali.zhiwuduotai.top/Article/details/gtflpekvgx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gtayzaoiwm.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gtswmbqimn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gtptaouhdo.html

[Q08] 创建普通索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjlcfior.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtfcieqwws.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gtvcksoflk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtqfoizwaa.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gtemlovwyt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zycfv.cn/Article/details/gtehxxovmz.html

[Q11] 一次插入多行
来源：http://dali.mhx1999.top/Article/details/gtucljfwut.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnqzz.top/Article/details/gtzvfpptzc.html

[Q12] 插入后取自增 ID
来源：http://dali.smart0.xyz/Article/details/gtlhfyltln.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtxyjqcqlp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xinyue.icu/Article/details/gtjjzlaksr.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gtkkzsesgu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtehuisnhd.html

[Q14] 存在则更新（upsert）
来源：http://dali.guowangkeji.top/Article/details/gtotbraicm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gtwxihvfsz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yanxiufei.cn/Article/details/gtveiounkx.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gtbkiyqpwv.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtkndhikez.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gtcizhtsuj.html

SELECT id, name FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtisnffnmz.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gtzympedyl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.birdmap.top/Article/details/gtbphxxjgt.html

[Q18] 模糊匹配
来源：http://dali.tanke756.top/Article/details/gtfnwtbeiq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gtelajgrio.html

[Q19] 范围查询
来源：http://dali.meibo888.top/Article/details/gtijbbwmqp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dashuyun.cn/Article/details/gtwtygavfx.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gteqwrwxoq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgfzy.top/Article/details/gtrwucrhcz.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gtoligajqh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gtybcclxcx.html

[Q22] 排序
来源：http://dali.snrcjt.cn/Article/details/gtxqemhmzh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ydzc1.top/Article/details/gtwhyyyhlm.html

[Q23] 分页
来源：http://dali.fzhhl.top/Article/details/gtdimubftu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwvmsktw.html

[Q24] 去重
来源：http://dali.yvedp.cn/Article/details/gtqogxjenw.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gtgauzezdj.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gtwwnknptu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fzhhl.top/Article/details/gtvcsgntcs.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gtbyjlknqu.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gttvhhxqab.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwceptcde.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gthhvpecbb.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gtgjldmqdy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtjkjmdtsz.html

[Q29] 最大最小值
来源：http://dali.dashuyun.cn/Article/details/gterezywvg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtehcyxfqq.html

[Q30] 分组统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxvpulei.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gthpqkvhsp.html

[Q31] 分组后过滤
来源：http://dali.smart0.xyz/Article/details/gtobcrluex.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yueranfly.top/Article/details/gtrnxkfmff.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gtxwefiiws.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtxcqusbyq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gtontplcxl.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gtcqkfmpyx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gtgxrfwyak.html

[Q34] 每组取第一条
来源：http://dali.cqqwz.cn/Article/details/gtcprwflbu.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gtlhzzlkwt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenlongwang.top/Article/details/gtizymkbky.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gtpuwzlpif.html

[Q35] 内连接
来源：http://dali.yj202588.top/Article/details/gtlvzbigax.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gteyqbpfla.html

[Q36] 左连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaradjdiz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtjkhsoadr.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gtlzknsksj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.iojbl.cn/Article/details/gtbniuqanf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hysaishi.cn/Article/details/gtjqbqjvcd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cashguo.top/Article/details/gtffeggfaz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gtxrcezvhc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pycfn.com/Article/details/gtswfpvvfg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hammf.cn/Article/details/gtlahgsrto.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gtvielnevo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ivvv.top/Article/details/gtihahkklv.html

[Q41] 多表连接
来源：http://dali.sxryk.cn/Article/details/gtxdiqeaew.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.redwolf501.top/Article/details/gtsluzwvau.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gttubtmlkr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgufenzy.top/Article/details/gtskqfegkg.html

[Q42] 连接条件附加过滤
来源：http://dali.haohaochexian.top/Article/details/gtddvebair.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gtbsqcjjrb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtqwxonyen.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gtzkeuiauu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cdnleiting.top/Article/details/gtfrksmgkd.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gtvxffdcnk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gtkifkrceb.html

[Q45] EXISTS 判断存在
来源：http://dali.sxryk.cn/Article/details/gttbnhvnxw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtatnicgmo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtskvkrjuv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gtwnwunujd.html

[Q47] 与平均值比较
来源：http://dali.tianlin.xyz/Article/details/gtpicvdtuc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtqckoslfy.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gtnympqphl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fzhhl.top/Article/details/gtmsbxfsvs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xziqi.cn/Article/details/gtfrrrozwt.html

[Q49] 更新单行
来源：http://dali.cheryme.top/Article/details/gtcecmmihl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtpfbtrlzr.html

[Q50] 批量更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyygvtse.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hywenlv.cn/Article/details/gtfzostywm.html

[Q51] 用子查询更新
来源：http://dali.hongshengwenyu.top/Article/details/gtisryikzg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtietqjfry.html

[Q52] 删除指定行
来源：http://dali.pengpengdd.cyou/Article/details/gtvoggqczs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gtbpkawnve.html

[Q53] 按条件删除
来源：http://dali.kuanghao11.cn/Article/details/gtiejbkhsr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtccdjhyhp.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gtnlgvizwt.html

TRUNCATE TABLE logs;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosluylib.html

[Q55] 排名（并列占位）
来源：http://dali.bjfxy.top/Article/details/gtlanzwljj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gthfggmvya.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhongyouzk.top/Article/details/gtdkzkwvbe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gtijkummyo.html

[Q57] 行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqyllqbs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtkeqrcrva.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gttwlssrga.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtkktdtraa.html

[Q59] 分组内累计
来源：http://dali.bjfxy.top/Article/details/gtbweaaotm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gttwsrrhpg.html

[Q60] 取上一行 / 下一行
来源：http://dali.cashguo.top/Article/details/gtvvlkzdby.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hywenlv.cn/Article/details/gtswjqhham.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtlxhagrld.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gtytgkocpr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtncbtjrbd.html

[Q62] 分组占比
来源：http://dali.gogol.net.cn/Article/details/gtjeztrkba.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtbxkyuctb.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gtjmjkkbvb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gtwvwtfdkp.html

[Q64] 提交事务
来源：http://dali.quarkkingdee.top/Article/details/gtmdsqhbwi.html

COMMIT;
来源：http://dali.xuanzx.com/Article/details/gtzqiodpam.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gtdcvnhbwu.html

ROLLBACK;
来源：http://dali.aibaodan.cn/Article/details/gtupnecwnp.html

[Q66] 行锁查询
来源：http://dali.c1oappe.top/Article/details/gtnguokkbn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gttillsaaw.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gtcwxbxngh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gtglkcvazh.html

[Q68] 保存点
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqirlrjh.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gtneifzxbw.html

ROLLBACK TO sp1;
来源：http://dali.jiagoushi.top/Article/details/gtdszoqkqq.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gtbwkfwjre.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gtsdlkxyok.html

[Q70] 更新统计信息
来源：http://dali.kuanghao11.cn/Article/details/gttgmkpara.html

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gtizcoctzn.html

[Q71] 查看建表语句
来源：http://dali.xinyue.icu/Article/details/gtpdmqdqlk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhongyouzk.top/Article/details/gtuwhgmibm.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gttopxzkgu.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtpqudzmlg.html

[Q73] 查看表状态
来源：http://dali.yj20258888.top/Article/details/gtdamejazc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gtuwvdyeok.html

[Q74] 强制使用索引
来源：http://dali.svipenyu.cn/Article/details/gtrwcvkxha.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gtslyldqwl.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtgublsydg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtvvupnzky.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gthagdzahb.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gtotudwlxc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gtjnyvkfjd.html

[Q77] 时间加减
来源：http://dali.gzhubu.top/Article/details/gttmwkmsty.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gthlmznkui.html

[Q78] 当前时间
来源：http://dali.yangfankeji.com/Article/details/gtavbkvclj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gtapjgxybe.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gtkrfjgakr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gteqnypojk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gtyygzeftq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtrfmwlnkr.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtlqdwuidv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtypvubhee.html

[Q82] 字符长度与字节长度
来源：http://dali.aibaodan.cn/Article/details/gttnzgtscp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtxkoujvqh.html

[Q83] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gtqdywgoqn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtirbgghxt.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gtdpahqezs.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtbhklddio.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gtvveupyfm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.havefunace.top/Article/details/gtolzvnlje.html

[Q86] 读取 JSON 字段
来源：http://dali.hysaishi.cn/Article/details/gtfaudrrwp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gtzcgnwsbt.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gtkmodxqni.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgygvqai.html

[Q88] 行转列（条件聚合）
来源：http://dali.bjfxy.top/Article/details/gthmzxzimi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtiplomnyf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtwlbffqqi.html

[Q89] 判断表是否存在
来源：http://dali.wangdashe.top/Article/details/gtistjsnjd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gtsegfikyu.html

[Q90] 生成序号列
来源：http://dali.316326.xyz/Article/details/gtywahakgh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cdnleiting.top/Article/details/gtyeokzvbe.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgmlsoock.html

R. Bash 专题
来源：http://dali.tanke756.top/Article/details/gtbjjiixpo.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvihfwxq.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gteybrhqgs.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gtyljjrjsd.html

set -euo pipefail
来源：http://dali.sysykeji.top/Article/details/gtdmlgdtnf.html

[R02] 变量赋值与使用
来源：http://dali.meibo888.top/Article/details/gtcptwvxat.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gtmvpgaynj.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gtuxtxzfpr.html

readonly PI=3.14
来源：http://dali.ybcxt.top/Article/details/gtsewqkofw.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gtoyxngotq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gtbqiyplbw.html

[R05] 参数默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwwvbnsh.html

name="${1:-default}"
来源：http://dali.cucudq.cn/Article/details/gtyrruvdmq.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtnlttumcu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtizltljcx.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtrvsdtalo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yongpay.top/Article/details/gtjiqyqdzk.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gtexjcaaxa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hfpthk.cn/Article/details/gtxkwexbky.html

[R09] 字符串比较
来源：http://dali.iojbl.cn/Article/details/gtywjxkdei.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cucudq.cn/Article/details/gtrtwkqudx.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gtasunbqgi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gtdcplrrnv.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gtnbhyoaxr.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gtnpiamwhf.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gtmaqlmgtq.html

stop)  echo "停止" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtfwsjqqqg.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwefrorbf.html

esac
来源：http://dali.hfpthk.cn/Article/details/gtebcgyjuc.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gtpbgbdcmw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxuanxn.top/Article/details/gtfemtnsvd.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtljbdcuxv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedudurym.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gtadwvtdtu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtnihvdinv.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtqgsrzoax.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ydzc1.top/Article/details/gtcebtravu.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gtqiymybct.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gtbdtwdwkt.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gtxwfrvela.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xinyue.icu/Article/details/gtoojlbfoe.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gtebqyqveg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sufxvd.cn/Article/details/gtgwhpqpyw.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtlimkifvb.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gtouqumykv.html

[R20] 关联数组（字典）
来源：http://dali.hfpthk.cn/Article/details/gtaahvfwlx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gtsdoqhezz.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtfoagvfyg.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gtnnrspfdf.html

[R22] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxrjapcs.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gtlwsmpcen.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtjfxcjlcg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gtwlnpdtbc.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtdivhdser.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ppjwa.cn/Article/details/gtzkzvmpcj.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigufen.top/Article/details/gtetburbph.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gtlirdjpxk.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqekcmor.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqbfyrtx.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gtfosgtodd.html

echo $((1 + 2 * 3))
来源：http://dali.daxiang520.top/Article/details/gtzhzkjhfd.html

[R28] 浮点运算
来源：http://dali.xziqi.cn/Article/details/gtwjzaxbel.html

echo "scale=2; 10/3" | bc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwviclsgi.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gtftnkgzoj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gtamqcazjw.html

[R30] 函数返回状态码
来源：http://dali.yvedp.cn/Article/details/gtneeojbdn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gtiuxgdjow.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtaqihzwoz.html

f() { local x=1; echo "$x"; }
来源：http://dali.tianlin.xyz/Article/details/gtfrwialcm.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gtlkxsskzh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtayeczqnb.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gtbcfhqkhq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangdashe.top/Article/details/gtdbeisaha.html

[R34] 退出时清理
来源：http://dali.tian-w.cn/Article/details/gtimcuvlhi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtgfzhraar.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtaubzwojp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftrlsypx.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gtymddhddm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gtuejvvlkj.html

[R37] 把输出赋给变量
来源：http://dali.quarkkingdee.top/Article/details/gtgccvoaun.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gthtxcnzjj.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gtkoxunivs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenjidiqi.icu/Article/details/gtxqfracwv.html

[R39] 重定向标准输出与错误
来源：http://dali.tianlin.xyz/Article/details/gtxtpdkigt.html

cmd > out.log 2>&1
来源：http://dali.redwolf501.top/Article/details/gtvkjyifcm.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gtilbhhnjp.html

echo "log" >> out.log
来源：http://dali.hongshengwenyu.top/Article/details/gtfwjqvjkt.html

[R41] 丢弃输出
来源：http://dali.cqqwz.cn/Article/details/gtjgwxcknh.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gtdsmwmdok.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtgcpojrmf.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gtqqpzxtam.html

[R43] 按名字查找文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpoxqyml.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gttbkqnnhb.html

[R44] 按修改时间查找
来源：http://dali.xylfe.cn/Article/details/gtfonjgakv.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gtjpatkwkz.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gtjzpnmpmw.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gtpudcektx.html

[R46] 递归替换文件内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gthczkbflp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pycfn.com/Article/details/gtklphgmty.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gtlzdwbtal.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtckhaaoxo.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gtzkoqfneq.html

awk '{print $1, $3}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtcrkhhhjk.html

[R49] awk 带条件
来源：http://dali.bjfxy.top/Article/details/gtetrsiyym.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gtoovkopwh.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gtwagetkla.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtolysiyqs.html

[R51] 排序去重取前几
来源：http://dali.jyoumei.cn/Article/details/gtxgthetem.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangshuangyany.cn/Article/details/gtujaaxtql.html

[R52] 统计行数
来源：http://dali.vqdsnc.cn/Article/details/gtyicwibhl.html

wc -l a.txt
来源：http://dali.yj202588.top/Article/details/gtwiehwlva.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfpiqndd.html


<!-- 参考信息 -->