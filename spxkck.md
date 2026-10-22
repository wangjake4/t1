代发 wailian999

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ixwvlofz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pengpengdd.cyou/Article/details/gt2zuembtnb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2mieifvru.html

[Q01] 创建表
来源：http://dali.yanxiufei.cn/Article/details/gt2gupiewnn.html

CREATE TABLE users (
来源：http://dali.yuanzhike.top/Article/details/gt2xxjxszcl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gt2taexnrvd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gt2vngbnejq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zdqjudy.top/Article/details/gt2eilclrci.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gt2vxfcngrm.html

);
来源：http://dali.fengsongda.top/Article/details/gt2vcpalhkk.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gt2yawxnldt.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnkbljuq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gt2qwdelrcw.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gt2lrrtgfwj.html

amount DECIMAL(10, 2),
来源：http://dali.meibo888.top/Article/details/gt2ncaacvbd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gt2bdvenhbq.html

);
来源：http://dali.chenzaomai.com/Article/details/gt2byqfstag.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gt2ouhpeoyq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gt2cabiwbrx.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gt2mffbushu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gt2npiysbmc.html

[Q05] 重命名列
来源：http://dali.ppjwa.cn/Article/details/gt2ojamlmna.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjdzmoon.html

[Q06] 删除列
来源：http://dali.yj20258888.top/Article/details/gt2kinoteez.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuanzx.com/Article/details/gt2jidgrust.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gt2ekosaxsh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gt2rvugkdyl.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gt2whhiayhz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gt2nxmowgke.html

[Q09] 创建唯一索引
来源：http://dali.zhoulong.xyz/Article/details/gt2bjkmzixu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gt2qtoztmwg.html

[Q10] 插入单行
来源：http://dali.cdnleiting.top/Article/details/gt2tmtiswzi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cdnleiting.top/Article/details/gt2hejundya.html

[Q11] 一次插入多行
来源：http://dali.cdnleiting.top/Article/details/gt2omoqkljx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.meibo888.top/Article/details/gt2nlovqehg.html

[Q12] 插入后取自增 ID
来源：http://dali.9152youxi.cn/Article/details/gt2uwrilrim.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gt2jjrczccq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj202588.top/Article/details/gt2jbacodbr.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ncqhyamj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yonumen.top/Article/details/gt2lnecsook.html

[Q14] 存在则更新（upsert）
来源：http://dali.yanxiufei.cn/Article/details/gt2ywfwfzay.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jyoumei.cn/Article/details/gt2sydzuatn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gt2yugazmmv.html

[Q15] 查询全部
来源：http://dali.daxiang520.top/Article/details/gt2roopjhoe.html

SELECT * FROM users;
来源：http://dali.yonumen.top/Article/details/gt2loyylwhc.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gt2arxaalza.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxlcjjyh.html

[Q17] 条件查询
来源：http://dali.andypj.xyz/Article/details/gt2owshnmvy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2maqpoobr.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gt2mdplselv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hysaishi.cn/Article/details/gt2kazmxtoo.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2asamysdo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tpnnttkm.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gt2plkfekyw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2esksymqz.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gt2ggqrbxue.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhongyouzk.top/Article/details/gt2lzsxtina.html

[Q22] 排序
来源：http://dali.nanxuanxn.top/Article/details/gt2cnqbfeuc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gt2qysyvdfs.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gt2nkxqlebo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shuidangran.top/Article/details/gt2vinehheu.html

[Q24] 去重
来源：http://dali.wangdashe.top/Article/details/gt2nbnotlsy.html

SELECT DISTINCT city FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2vdxyotmu.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gt2nybvkluo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangdashe.top/Article/details/gt2dsusgskb.html

[Q26] 计数
来源：http://dali.gaohongyu789.top/Article/details/gt2aymsuodd.html

SELECT COUNT(*) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2lhfsbqxn.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gt2noifnnkv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2xuemlcbp.html

[Q28] 求和与平均
来源：http://dali.yongpay.top/Article/details/gt2iunrlezm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2yguwdiev.html

[Q29] 最大最小值
来源：http://dali.nwbrower.top/Article/details/gt2nzvcaxlq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfkmmizd.html

[Q30] 分组统计
来源：http://dali.redwolf501.top/Article/details/gt2bxdnvxef.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gt2yeowtxgs.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2uantjusw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gt2lthrheel.html

[Q32] 分组拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2lwqrczzl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2qtbvecle.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iofwsipo.html

[Q33] 多列分组
来源：http://dali.iojbl.cn/Article/details/gt2tpbfxtyn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxinkj.top/Article/details/gt2rzddoxgr.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gt2ojpsiexk.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gt2djsohefv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gt2vpxayzvq.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2qwmlfafv.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gt2mjejbxrd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gt2hnkqtbxc.html

[Q36] 左连接
来源：http://dali.birdmap.top/Article/details/gt2vcrhwrlt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gt2qouxfxil.html

[Q37] 右连接
来源：http://dali.yonumen.top/Article/details/gt2hbwipwmk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yonumen.top/Article/details/gt2ihfspvyw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.0kj1m.cn/Article/details/gt2nxnbqfot.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cucudq.cn/Article/details/gt2cfpxcrsf.html

[Q39] 自连接（查上下级）
来源：http://dali.cqqwz.cn/Article/details/gt2venshfyz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gt2ikriwibp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xinyue.icu/Article/details/gt2clvioxxi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jyoumei.cn/Article/details/gt2syyyswph.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zdqjudy.top/Article/details/gt2nrmquoid.html

[Q41] 多表连接
来源：http://dali.yuanzhike.top/Article/details/gt2vfzuqlwx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gt2ftziuxmc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gt2axncvqvz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tian-w.cn/Article/details/gt2pjbmtigb.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gt2wuzarzoq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daxiang520.top/Article/details/gt2hbrzhqoa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gt2nmbmtyiq.html

[Q43] 标量子查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2oppnmexj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xziqi.cn/Article/details/gt2mrwkwocs.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gt2ojnxswmn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gt2jpgfkloq.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258888.top/Article/details/gt2tyaiooou.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gt2vvsjokzh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.c1oappe.top/Article/details/gt2jznzjfru.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gt2befxdagy.html

[Q47] 与平均值比较
来源：http://dali.zycfv.cn/Article/details/gt2vvlvgsbo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gt2gthkpojo.html

[Q48] CTE 公用表表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwarnthv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gt2miunlkvk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gt2rbcilvpu.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gt2wzfclkjf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gt2qjlfnfyw.html

[Q50] 批量更新
来源：http://dali.jianghu66.top/Article/details/gt2hyfpxeni.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ydzc1.top/Article/details/gt2votrhgbg.html

[Q51] 用子查询更新
来源：http://dali.xziqi.cn/Article/details/gt2kljvpzqh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gt2kknysuxp.html

[Q52] 删除指定行
来源：http://dali.ppjwa.cn/Article/details/gt2rpmwyoor.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gt2lxctvqlh.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gt2cepiogtz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gt2bzpivrlq.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gt2kmyvknjr.html

TRUNCATE TABLE logs;
来源：http://dali.sysykeji.top/Article/details/gt2fpbqjftq.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gt2sgriqzqd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qnnjrvpm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.vqdsnc.cn/Article/details/gt2fsbwsheo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbfsdbth.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nwusvzwq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvhinijv.html

[Q58] 累计求和
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvunpyvd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2jqlpkopf.html

[Q59] 分组内累计
来源：http://dali.vqdsnc.cn/Article/details/gt2vydlqxka.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2qcxjpbdw.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenlongwang.top/Article/details/gt2wrbpmcuz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gt2kpaosynl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmnssnfj.html

[Q61] 移动平均
来源：http://dali.smart0.xyz/Article/details/gt2mxlvvrsg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2alntscry.html

[Q62] 分组占比
来源：http://dali.chenzaomai.com/Article/details/gt2ytezsplj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gt2stkmqisx.html

[Q63] 开启事务
来源：http://dali.zhoulong.xyz/Article/details/gt2trcgsrha.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnqzz.top/Article/details/gt2heixnhlz.html

[Q64] 提交事务
来源：http://dali.jianghu66.top/Article/details/gt2djutjzfw.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gt2inpqbpse.html

[Q65] 回滚事务
来源：http://dali.shuidangran.top/Article/details/gt2akryqsno.html

ROLLBACK;
来源：http://dali.wangshuangyany.cn/Article/details/gt2flvibltg.html

[Q66] 行锁查询
来源：http://dali.zdqjudy.top/Article/details/gt2yllbmwqj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yonumen.top/Article/details/gt2dzdowzev.html

[Q67] 设置隔离级别
来源：http://dali.xinyue.icu/Article/details/gt2huzedfhu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kkjevhvb.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gt2wjfxhgks.html

SAVEPOINT sp1;
来源：http://dali.gaohongyu789.top/Article/details/gt2xxrtrics.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgadfbux.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vpynytjq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gt2rgerynat.html

[Q70] 更新统计信息
来源：http://dali.gaohongyu789.top/Article/details/gt2dbcawmuk.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gt2avizncav.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gt2ucwmfhmv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aizwys.cn/Article/details/gt2euojmvry.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gt2cangdffi.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2xnadbozp.html

[Q73] 查看表状态
来源：http://dali.mhx1999.top/Article/details/gt2umloponi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuxming.cn/Article/details/gt2ghrkcnex.html

[Q74] 强制使用索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbstlfsd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cqqwz.cn/Article/details/gt2mmcdecrk.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gt2cbpvmjps.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2wcfbrrwf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gt2jxxtqvye.html

[Q76] 按天统计
来源：http://dali.jinqigfzy.top/Article/details/gt2lrteqvuw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xylfe.cn/Article/details/gt2cgtrfytt.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gt2zygaynnl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gt2qfbjufrt.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gt2bktpvxur.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gt2yezkqrmi.html

[Q79] 字符串拼接
来源：http://dali.yj20258888.top/Article/details/gt2sjwfenmr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gt2vspozmub.html

[Q80] 字符串截取
来源：http://dali.yuxming.cn/Article/details/gt2jnpnczrm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2czeuzimv.html

[Q81] 字符串替换
来源：http://dali.meibo888.top/Article/details/gt2uiwxyjlk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2chyuxgtg.html

[Q82] 字符长度与字节长度
来源：http://dali.meibo888.top/Article/details/gt2dctsurtq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2cdmeismo.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gt2ffufhher.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2uhcgglng.html

[Q84] 去除首尾空格
来源：http://dali.yj20258888.top/Article/details/gt2yqpgxjzx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2usikmgjs.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gt2lipdbveq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.c1oappe.top/Article/details/gt2fyuufptt.html

[Q86] 读取 JSON 字段
来源：http://dali.xuanzx.com/Article/details/gt2ofscmseg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfnzaqqj.html

[Q87] JSON 字段做条件
来源：http://dali.yangfankeji.com/Article/details/gt2nfmebfey.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhixingplan.top/Article/details/gt2iciwxyry.html

[Q88] 行转列（条件聚合）
来源：http://dali.yangfankeji.com/Article/details/gt2rkolrvgb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ybcxt.top/Article/details/gt2zdeltmel.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gt2sknnmmsv.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gt2gbqbeajt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gt2tzbalodp.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gt2wderybkv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gt2qbfuzgkq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2vsmjijmc.html

R. Bash 专题
来源：http://dali.shzxlz.cn/Article/details/gt2wpvtmqlt.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2naszgvtg.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gt2fufacrfa.html

#!/usr/bin/env bash
来源：http://dali.tianlin.xyz/Article/details/gt2pjxdbvid.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gt2fuxxfrbd.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gt2qrwbucxo.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gt2eclelned.html

[R03] 只读变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wiwkvwwy.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gt2jibosrhe.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gt2nvkgxjal.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gt2sgftqojk.html

[R05] 参数默认值
来源：http://dali.hammf.cn/Article/details/gt2vlsgfpfr.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2vksjjyox.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gt2jumdullg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gt2pfvosjbq.html

[R07] if 判断文件
来源：http://dali.yongpay.top/Article/details/gt2lklegrks.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2alnpxljf.html

[R08] 数值比较
来源：http://dali.meibo888.top/Article/details/gt2afownwkt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yongpay.top/Article/details/gt2tjbqakho.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gt2kzpjzzrt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2jcqjzyfz.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gt2ngizdxsh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xinyue.icu/Article/details/gt2ctdtwnzz.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gt2bebcafis.html

case "$1" in
来源：http://dali.gaohongyu789.top/Article/details/gt2ukpztfzc.html

start) echo "启动" ;;
来源：http://dali.yj202588.top/Article/details/gt2cepsmhru.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2mjkevdrr.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gt2bbvjawem.html

esac
来源：http://dali.ppjwa.cn/Article/details/gt2oxrejdux.html

[R12] for 遍历文件
来源：http://dali.nanxinkj.top/Article/details/gt2bdznxjld.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nztrasjw.html

[R13] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gt2cvmhsoob.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gt2hxufzxin.html

[R14] C 风格 for
来源：http://dali.feifeiyinyue.top/Article/details/gt2kexfrwbx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gt2hffzwwqj.html

[R15] while 逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2ihthfbjo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gt2gafpcnqb.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ziuvyizh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gt2wetrrheh.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gt2yfdpbpkv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gt2kwbxquee.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckahvgrl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258.top/Article/details/gt2uwaebnmh.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gt2nebhgmwu.html

echo "${#arr[@]}"
来源：http://dali.sweek.top/Article/details/gt2optvuyng.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gt2zdphrudz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yueranfly.top/Article/details/gt2yjtmfnji.html

[R21] 字符串长度
来源：http://dali.daxiang520.top/Article/details/gt2izvaxcpv.html

echo "${#s}"
来源：http://dali.shuidangran.top/Article/details/gt2kyuifzik.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gt2iwltsrrn.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2onqueogk.html

[R23] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gt2podhgfsy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gt2sbposvkj.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2nyruafba.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cucudq.cn/Article/details/gt2hmypkkpb.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnxiangtu.top/Article/details/gt2nkgfqajh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gt2nqexnlbe.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2lopkrdrr.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gt2mcjuvnbv.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyyodvmy.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gt2tbosflbp.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gt2ossetgmr.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gt2pddmbatk.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gt2sinwbeii.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhengqikj.top/Article/details/gt2zemmrrvh.html

[R30] 函数返回状态码
来源：http://dali.redwolf501.top/Article/details/gt2ogsszqgr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gt2vfqotnik.html

[R31] 局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwgeqrld.html

f() { local x=1; echo "$x"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zoawzkdb.html

[R32] 参数个数校验
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezpxiuef.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gt2ggmszsro.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlzeyfnl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gt2iynoizny.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gt2lsbtkfov.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ddvzyeen.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gt2drhqrssv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhongyouzk.top/Article/details/gt2vikfosct.html

[R36] 并发执行多个任务
来源：http://dali.zycfv.cn/Article/details/gt2vakuhnyy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.havefunace.top/Article/details/gt2exsrgjuy.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gt2dwzyyayy.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gt2fdpfkmci.html

[R38] 管道串联
来源：http://dali.nanxuanxn.top/Article/details/gt2ywxmxrjn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gt2tcrlyopr.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gt2ezowynyp.html

cmd > out.log 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gt2irzlfjsz.html

[R40] 追加写日志
来源：http://dali.316326.xyz/Article/details/gt2hgxqxvxm.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gt2effngfxz.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gt2ttsoyzjq.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uhcskmmj.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gt2qrwkbzor.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gt2hlcphoqw.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gt2grtahxvr.html


<!-- 参考信息 -->