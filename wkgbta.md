代发 wailian999

);
来源：http://dali.dashuyun.cn/Article/details/gtsjyewbca.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gtjnmsrxcc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gtkprtkhdj.html

[Q04] 修改列类型
来源：http://dali.9152youxi.cn/Article/details/gtgivqfhtf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjbpgqkg.html

[Q05] 重命名列
来源：http://dali.pengpengdd.cyou/Article/details/gttuxgnxci.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yongpay.top/Article/details/gtsgzktsjj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gttadqmsvu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shuidangran.top/Article/details/gtberdjniy.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gtvqymplyg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.svipenyu.cn/Article/details/gtrtmysnbi.html

[Q08] 创建普通索引
来源：http://dali.zhongyouzk.top/Article/details/gtyrtzrcrn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtxvcbuiks.html

[Q09] 创建唯一索引
来源：http://dali.dianchejie.cn/Article/details/gtvfxncwma.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtigpzqqnq.html

[Q10] 插入单行
来源：http://dali.0kj1m.cn/Article/details/gthxrzwvwf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtppozfbtu.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gtoqddmmrx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtgzbwljvu.html

[Q12] 插入后取自增 ID
来源：http://dali.cdnleiting.top/Article/details/gtnhmyubvz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gtzwklknsu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pycfn.com/Article/details/gttdwyrgjz.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gtkrwknwls.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gtwojxbcdz.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj202588.top/Article/details/gthzbkectw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gtcrokvgoo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ppjwa.cn/Article/details/gtpaogerut.html

[Q15] 查询全部
来源：http://dali.9152youxi.cn/Article/details/gteqdhgmhx.html

SELECT * FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtldbhbljd.html

[Q16] 查询指定列
来源：http://dali.jinqigufen.top/Article/details/gtwhkfbooe.html

SELECT id, name FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthnfqqkg.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gtphvoucph.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtdfoufyhq.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gttwhqoskp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gtdgkdmplf.html

[Q19] 范围查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjbqcouh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgufenzy.top/Article/details/gtlnhbtczl.html

[Q20] IN 列表
来源：http://dali.fzhhl.top/Article/details/gtvotkjldv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkreefzph.html

[Q21] 空值判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmmfocqz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gtjoopddfl.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gtrunglfbh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jyoumei.cn/Article/details/gtzttqxkel.html

[Q23] 分页
来源：http://dali.gzhubu.top/Article/details/gtunesrlic.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jianghu66.top/Article/details/gtnvocuvif.html

[Q24] 去重
来源：http://dali.yonumen.top/Article/details/gtisptojiq.html

SELECT DISTINCT city FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtzzotpmvb.html

[Q25] 只取前 N 条
来源：http://dali.yuxming.cn/Article/details/gtsdkisrlz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.meibo888.top/Article/details/gtyvzqwoul.html

[Q26] 计数
来源：http://dali.yangfankeji.com/Article/details/gtnceadswg.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomionhaj.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gtukxlywex.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xinyue.icu/Article/details/gtdkrkxlni.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gttrovuojj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gttieohxgt.html

[Q29] 最大最小值
来源：http://dali.zhixingplan.top/Article/details/gtqpmkqonn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gtbkyekdyd.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gtixehcjhk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtmziqlvla.html

[Q31] 分组后过滤
来源：http://dali.0kj1m.cn/Article/details/gtxznmvtcf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gzhubu.top/Article/details/gtmesvhsvf.html

[Q32] 分组拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtdunznlfw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gteyihytxd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fzhhl.top/Article/details/gtjeexoryh.html

[Q33] 多列分组
来源：http://dali.0kj1m.cn/Article/details/gtiwsrlowg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pengpengdd.cyou/Article/details/gtzzmkytaa.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gtqvnhvbmj.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gtkfhjfumy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pengpengdd.cyou/Article/details/gtuaybbtyj.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gttldumdwm.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gtzkjcpwbm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gtgjruvlly.html

[Q36] 左连接
来源：http://dali.guowangkeji.top/Article/details/gtuuobwxsj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtogkshsms.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gtecjhnlsr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aibaodan.cn/Article/details/gthxcpbeyl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpyzgioh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.bjfxy.top/Article/details/gtzdriyfqe.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gtgdfkgfsq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gtmgbhcpei.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shzxlz.cn/Article/details/gtqjkfbtue.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ehwqpu.com/Article/details/gtqfbeluqx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gtohdovsbq.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gtxhjnwetw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gtovynoisk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxinkj.top/Article/details/gtzkxyliix.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shuidangran.top/Article/details/gthlqmuvol.html

[Q42] 连接条件附加过滤
来源：http://dali.andypj.xyz/Article/details/gtbvhcqggc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sufxvd.cn/Article/details/gthtzceejq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fzhhl.top/Article/details/gtcodvsuxc.html

[Q43] 标量子查询
来源：http://dali.mhx1999.top/Article/details/gtuqjvcuow.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.smart0.xyz/Article/details/gtcxqyajxc.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gtnjzfbrzu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhixingplan.top/Article/details/gtwedalwkv.html

[Q45] EXISTS 判断存在
来源：http://dali.sysykeji.top/Article/details/gtkfnazzwm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtleaytmci.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenlongwang.top/Article/details/gtduoatdvz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtwfhkqweq.html

[Q47] 与平均值比较
来源：http://dali.chenjidiqi.icu/Article/details/gtdgrkqrqr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258.top/Article/details/gtoznmkutl.html

[Q48] CTE 公用表表达式
来源：http://dali.hywenlv.cn/Article/details/gtxaviplnn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cdnleiting.top/Article/details/gtnlwpdpmc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangdashe.top/Article/details/gtdhncsgcs.html

[Q49] 更新单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjwyqbuz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gtkhuhevht.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gtunuipqbn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtucvkrjxk.html

[Q51] 用子查询更新
来源：http://dali.shzxlz.cn/Article/details/gtcsuzqclw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sufxvd.cn/Article/details/gthrotkzzs.html

[Q52] 删除指定行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkestidwx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtxovigzqt.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gtgmxonjbt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtyvjusutp.html

[Q54] 清空表
来源：http://dali.cucudq.cn/Article/details/gtmzwaxira.html

TRUNCATE TABLE logs;
来源：http://dali.yangfankeji.com/Article/details/gtlcdwcofi.html

[Q55] 排名（并列占位）
来源：http://dali.gaohongyu789.top/Article/details/gtvgaawddf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gtcmcwsvpi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xinyue.icu/Article/details/gtizrvnxjy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gtpgntfhxv.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gtqjxxuexd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtrlnqenql.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gtgwtwavmn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtfkgqoejh.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gtpvwacvpd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtyewhusuk.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gtnvgworrm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtezmhwtjg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtevuapjci.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gtkpunpkbz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtjhkosnqe.html

[Q62] 分组占比
来源：http://dali.yongpay.top/Article/details/gtzimlyyic.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gteuewkfbo.html

[Q63] 开启事务
来源：http://dali.hnqzz.top/Article/details/gtwcatlykm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnqzz.top/Article/details/gtvvaarvhs.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtsspziydl.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gtsmuvcsmq.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gtclpcaeem.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gtedswgnic.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gtqewgzpih.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.meibo888.top/Article/details/gtxnbgqoxt.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gtzfmwgvjy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gtyukfzyqy.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gtjnyzpliu.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gtgghpnpqv.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtgyblpxjo.html

[Q69] 查看执行计划
来源：http://dali.yvedp.cn/Article/details/gtqkhxfvpk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hongshengwenyu.top/Article/details/gthkbberni.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gtktaafdyk.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gtbjyeihqz.html

[Q71] 查看建表语句
来源：http://dali.dianchejie.cn/Article/details/gtyqicrmfb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigfzy.top/Article/details/gtevkuiakp.html

[Q72] 查看索引
来源：http://dali.yongpay.top/Article/details/gthoxvomgm.html

SHOW INDEX FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtojzuikxo.html

[Q73] 查看表状态
来源：http://dali.dianchejie.cn/Article/details/gthezaxita.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xinyue.icu/Article/details/gtbhukpoon.html

[Q74] 强制使用索引
来源：http://dali.tianlin.xyz/Article/details/gtxfnukwry.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sysykeji.top/Article/details/gttwhaqiox.html

[Q75] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtczunsaao.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daxiang520.top/Article/details/gthfdntfjq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hysaishi.cn/Article/details/gtomhpqhfs.html

[Q76] 按天统计
来源：http://dali.andypj.xyz/Article/details/gtqbqkoozv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.vqdsnc.cn/Article/details/gtsxxuykkx.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gtlpfofcid.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gtfypftmkh.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtuugdihjp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gtacenvmsr.html

[Q79] 字符串拼接
来源：http://dali.gzhubu.top/Article/details/gtqlduuvnu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nwbrower.top/Article/details/gtcdwbskpe.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gtvexnsnvw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtexlvbebp.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtbtfpmyua.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtquyjafol.html

[Q82] 字符长度与字节长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyacxifk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtnwffzfki.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtyibrbstw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtrqnajaaj.html

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gtfvtrbrvh.html

SELECT TRIM(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtzckqaydq.html

[Q85] 数值取整
来源：http://dali.zhixingplan.top/Article/details/gtxlidckxl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlysqpack.html

[Q86] 读取 JSON 字段
来源：http://dali.birdmap.top/Article/details/gtyapuszrr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gticptlquf.html

[Q87] JSON 字段做条件
来源：http://dali.ivvv.top/Article/details/gtvnutjbjy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtntsoutii.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gtbmqnpgdv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gtblcmvpaj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtrookpmom.html

[Q89] 判断表是否存在
来源：http://dali.yj202588.top/Article/details/gtdxqckxey.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258888.top/Article/details/gtlsftqvre.html

[Q90] 生成序号列
来源：http://dali.jiagoushi.top/Article/details/gtzunfmvrq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gtdvjrpzvp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtvyjbpcyz.html

R. Bash 专题
来源：http://dali.daxiang520.top/Article/details/gtgymqjnbf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgmuadicv.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkjbkflg.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gtvshqwcnb.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gtzmpwdhoj.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gttxcaligf.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbmnsziq.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gtscpwvlfn.html

readonly PI=3.14
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvtgnmkm.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gtbdourakn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhiwuduotai.top/Article/details/gtpuqjosez.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gthtlwiwvz.html

name="${1:-default}"
来源：http://dali.jqgufenzy.top/Article/details/gtxbwlbwqh.html

[R06] 判断命令是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtzzeiadvv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtkhbrpcxo.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gtidqqcdlu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtkrrwdxut.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gttiddxlnx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gthqqchlxf.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gtablhhwqj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtpvcmxcht.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gthdonojat.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sxryk.cn/Article/details/gtqtjynxrq.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gtinnxgteb.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gtyzkfcqfr.html

start) echo "启动" ;;
来源：http://dali.ehwqpu.com/Article/details/gtgyopsywi.html

stop)  echo "停止" ;;
来源：http://dali.xuanzx.com/Article/details/gtsmcembbk.html

*)     echo "未知命令" ;;
来源：http://dali.nanxinkj.top/Article/details/gtmtjfogdz.html

esac
来源：http://dali.sxryk.cn/Article/details/gtutwgpxvg.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gtdkazfwav.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ydzc1.top/Article/details/gtfgtxrujh.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gttebpughf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbsjzbds.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gtnlfsuxib.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtptvjwyzb.html

[R15] while 逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtblcghrve.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhixingplan.top/Article/details/gtmejnihgu.html

[R16] until 等待条件
来源：http://dali.nwbrower.top/Article/details/gtmoilexbm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjisifwz.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gtxixzrvld.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yonumen.top/Article/details/gtaojrapcr.html

[R18] 遍历数组
来源：http://dali.andypj.xyz/Article/details/gtjstcfaot.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tanke756.top/Article/details/gthyzwxjsz.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtasjnwxdf.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjeeeknfp.html

[R20] 关联数组（字典）
来源：http://dali.gaohongyu789.top/Article/details/gtcnfxigww.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gtemfydckb.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gteqorfalx.html

echo "${#s}"
来源：http://dali.yuxming.cn/Article/details/gtdpfrnltf.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gttlnwbkpr.html

echo "${s:0:5}"
来源：http://dali.dashuyun.cn/Article/details/gtvpimedua.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtccwiyqas.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gtewxlfztk.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtxbfhsucx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuwpfbdy.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gtjjtdpxgx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gttwpnvqyl.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gtxweywvlv.html

now=$(date +%F); echo "$now"
来源：http://dali.wangdashe.top/Article/details/gtcsdjtxlb.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gtfcncnzmt.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigufen.top/Article/details/gtmrfreopi.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gtrzzendwq.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gtscfvlcck.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gtpxvyqhax.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gtombcxxrs.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtawkmphib.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gtqngmebtb.html

[R31] 局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtfxatqcox.html

f() { local x=1; echo "$x"; }
来源：http://dali.vqdsnc.cn/Article/details/gthctwnmlb.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gtyfpsuhol.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtxzvnfzow.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gtrbjpkyqf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gtdmbglefp.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gtiakodmdj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtzhyyccjw.html

[R35] 后台执行并等待
来源：http://dali.aizwys.cn/Article/details/gtwnkhqgyr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gtpwvuirjp.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gtneypauia.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tianlin.xyz/Article/details/gtbfcdtiiz.html

[R37] 把输出赋给变量
来源：http://dali.hnxiangtu.top/Article/details/gtbeasnhdd.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gtskralvex.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gtdwbqkinb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gtaqhoirnw.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gtfavkzmcm.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtzjeyhphq.html

[R40] 追加写日志
来源：http://dali.ybcxt.top/Article/details/gtvunsdxjx.html

echo "log" >> out.log
来源：http://dali.zhiwuduotai.top/Article/details/gtfdvizwki.html

[R41] 丢弃输出
来源：http://dali.redwolf501.top/Article/details/gtviypsknk.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtdysfqiai.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gtmaqmcokb.html

wc -l < a.txt
来源：http://dali.jiagoushi.top/Article/details/gtqvjdufhc.html

[R43] 按名字查找文件
来源：http://dali.hfpthk.cn/Article/details/gtgblqchjk.html

find . -name "*.log" -type f
来源：http://dali.jiagoushi.top/Article/details/gtqghabnhc.html

[R44] 按修改时间查找
来源：http://dali.hammf.cn/Article/details/gtggfejgvo.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gtelhygpwh.html

[R45] 批量删除
来源：http://dali.yanxiufei.cn/Article/details/gtndgatykr.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gtpseepphm.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gthbmctxyw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gtvvthshnk.html

[R47] sed 单行替换
来源：http://dali.xuetiantiany.cn/Article/details/gtibzwntzb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gtgjxxoqhj.html

[R48] awk 取指定列
来源：http://dali.iojbl.cn/Article/details/gtxawkprpr.html

awk '{print $1, $3}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtclqatptw.html

[R49] awk 带条件
来源：http://dali.yvedp.cn/Article/details/gtqnuosvze.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hongshengwenyu.top/Article/details/gtiwadakxi.html

[R50] awk 求和
来源：http://dali.mhx1999.top/Article/details/gtzcjzncxh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gteicpxidg.html

[R51] 排序去重取前几
来源：http://dali.daria6918.cn/Article/details/gtornwgbxa.html


<!-- 参考信息 -->