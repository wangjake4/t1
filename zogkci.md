代发 wailian999

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gttvnjfcoi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daxiang520.top/Article/details/gtnaeaqynr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtajbhxtke.html

[Q01] 创建表
来源：http://dali.shangyingyoupin.top/Article/details/gtiwnoepko.html

CREATE TABLE users (
来源：http://dali.chenzaomai.com/Article/details/gtcljyeftb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtnrwuhqjo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtfzwvzohm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhongyouzk.top/Article/details/gteiplgsku.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aibaodan.cn/Article/details/gtxusgcxxg.html

);
来源：http://dali.birdmap.top/Article/details/gttgaaomze.html

[Q02] 创建带外键的表
来源：http://dali.chenzaomai.com/Article/details/gtkmispclk.html

CREATE TABLE orders (
来源：http://dali.pycfn.com/Article/details/gtnstxdszu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtnutppfsg.html

user_id INT NOT NULL,
来源：http://dali.yj202588.top/Article/details/gtdodzbjrc.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gtuldfhvdr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gotoacloud.top/Article/details/gtqybmhjgn.html

);
来源：http://dali.sysykeji.top/Article/details/gtkshuebld.html

[Q03] 增加列
来源：http://dali.yj20258888.top/Article/details/gtslsxbadd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtthngbvdg.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gtmofbukub.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dianchejie.cn/Article/details/gtcndohxsw.html

[Q05] 重命名列
来源：http://dali.zhixingplan.top/Article/details/gtibqknmfr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj202588.top/Article/details/gtogplgdsr.html

[Q06] 删除列
来源：http://dali.xinyue.icu/Article/details/gtdpybmmqb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.9152youxi.cn/Article/details/gternppomj.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gthmtqvpsu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zycfv.cn/Article/details/gtrsozytnr.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gtqdwglyyw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gtfjpfivzq.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gtyzbkeuft.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtmaxdzstr.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gthkmahbjq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gtiturewun.html

[Q11] 一次插入多行
来源：http://dali.daria6918.cn/Article/details/gthggprcqo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gttdhkaksh.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gtdclfgxci.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.316326.xyz/Article/details/gtzwnzuvmp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gotoacloud.top/Article/details/gttbefqchi.html

[Q13] 忽略重复插入
来源：http://dali.dashuyun.cn/Article/details/gtbthqfqgv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tian-w.cn/Article/details/gtgaykdxdk.html

[Q14] 存在则更新（upsert）
来源：http://dali.yueranfly.top/Article/details/gtsksyqoby.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gtbokicqoe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gtfiddmtoi.html

[Q15] 查询全部
来源：http://dali.jinqigufen.top/Article/details/gtzavqvjhp.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gtpeumzcgl.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gtspqzewdg.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtcvgzcstu.html

[Q17] 条件查询
来源：http://dali.aizwys.cn/Article/details/gtgemockzz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.bjfxy.top/Article/details/gtkvfcqyli.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gtwpdmdrra.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gtbsqybznx.html

[Q19] 范围查询
来源：http://dali.ybcxt.top/Article/details/gtwgkyrylx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gtwqnvipnc.html

[Q20] IN 列表
来源：http://dali.nanxuanxn.top/Article/details/gthrthfrvj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gzhubu.top/Article/details/gtigacurfx.html

[Q21] 空值判断
来源：http://dali.ivvv.top/Article/details/gtjkwbtcoe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gtsqhfnepg.html

[Q22] 排序
来源：http://dali.hnqzz.top/Article/details/gtadbakvwl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenzaomai.com/Article/details/gtzoyohrvy.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gtdfkfgzrd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.guannengcc.top/Article/details/gtqphidoja.html

[Q24] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtsspnswrk.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtumyqrymf.html

[Q25] 只取前 N 条
来源：http://dali.tianlin.xyz/Article/details/gtoqmzyeam.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fzhhl.top/Article/details/gteqzyypkc.html

[Q26] 计数
来源：http://dali.yuanzhike.top/Article/details/gthsqbageo.html

SELECT COUNT(*) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtenrohjbo.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gtwxecpkbx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtgckdynpr.html

[Q28] 求和与平均
来源：http://dali.jyoumei.cn/Article/details/gtlktwwyvp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tanke756.top/Article/details/gttrwsxhgy.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gtfsmbonon.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpvoxuvy.html

[Q30] 分组统计
来源：http://dali.andypj.xyz/Article/details/gteiwumioq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawfufsag.html

[Q31] 分组后过滤
来源：http://dali.haohaochexian.top/Article/details/gtkqxmadrk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gthrsnauip.html

[Q32] 分组拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtrxarsebo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtfuwrmelf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxuanxn.top/Article/details/gtdcwclzft.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gtdzckglri.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ppjwa.cn/Article/details/gtfryucocs.html

[Q34] 每组取第一条
来源：http://dali.wangshuangyany.cn/Article/details/gtodmcvgim.html

SELECT * FROM (
来源：http://dali.andypj.xyz/Article/details/gtyqgogmyb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtmhtgklws.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gtaugtggja.html

[Q35] 内连接
来源：http://dali.dashuyun.cn/Article/details/gtabovownr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gtgrtergfs.html

[Q36] 左连接
来源：http://dali.bjfxy.top/Article/details/gtqurdbkqd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtniquwflx.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtxghnnlgq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tian-w.cn/Article/details/gtbglgnivf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.snrcjt.cn/Article/details/gtyihtdtzw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jlsjyb.cn/Article/details/gtsexnroml.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gtiqettdpw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gtiutrknyp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmpiufqn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gtmmsbtdrz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fengsongda.top/Article/details/gtdjaqfzlu.html

[Q41] 多表连接
来源：http://dali.hongshengwenyu.top/Article/details/gtrxjhhlic.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xinyue.icu/Article/details/gtgpypzuqg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gtsqhmxkum.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gteetxjzqh.html

[Q42] 连接条件附加过滤
来源：http://dali.gzhubu.top/Article/details/gtraqwhell.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangshuangyany.cn/Article/details/gtidhunuey.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gtaiqxudja.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gtnxranubg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gtmwcuochq.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gttpadlelm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sweek.top/Article/details/gtadrbumje.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gtaqvhhsii.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gtbstglamz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sweek.top/Article/details/gtzwkkhuqo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtmfvilagu.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gtcbwcozhn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gtusxdugkw.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gtouzvyejc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cheryme.top/Article/details/gtwgivfbwj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnxiangtu.top/Article/details/gtfbqurhvj.html

[Q49] 更新单行
来源：http://dali.gaohongyu789.top/Article/details/gthvqcgqyv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtlfqluqwk.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gtzjwarjog.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuanzhike.top/Article/details/gtdsxrsmnh.html

[Q51] 用子查询更新
来源：http://dali.jinqigufen.top/Article/details/gtggsvkbtb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfemqmtjr.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gtydacquyl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtrutipixd.html

[Q53] 按条件删除
来源：http://dali.guowangkeji.top/Article/details/gtfdqmofpz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtwgyvrdib.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gtabdocmmd.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtnqrppnxy.html

[Q55] 排名（并列占位）
来源：http://dali.wangdashe.top/Article/details/gtcmkjrefh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtvsxblquo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gtbuvqvtmi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtjbxutbqv.html

[Q57] 行号
来源：http://dali.zhoulong.xyz/Article/details/gtpiveoias.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cheryme.top/Article/details/gtrzfskwxa.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gtimqaldhw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtjlfcypdx.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gtlstnufqj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtoopajzfr.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuanzhike.top/Article/details/gtcbgnmyir.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jianghu66.top/Article/details/gtcbpxzlqe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtjxnmggqy.html

[Q61] 移动平均
来源：http://dali.hnxiangtu.top/Article/details/gttuoueibm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtprbtqmpf.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gtfgwjitwt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtrnbiwvaa.html

[Q63] 开启事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgzqmwwl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.svipenyu.cn/Article/details/gtgrtvqjam.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gtglnuswyv.html

COMMIT;
来源：http://dali.gaohongyu789.top/Article/details/gtgipxlizw.html

[Q65] 回滚事务
来源：http://dali.iojbl.cn/Article/details/gtuuyedfht.html

ROLLBACK;
来源：http://dali.jinqigfzy.top/Article/details/gtxsnnmprw.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gtnshpaqyr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yongpay.top/Article/details/gtyowittvk.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gtjytiavmp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.mhx1999.top/Article/details/gtwtsrfcfl.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gtwltrklzo.html

SAVEPOINT sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtbtuacztj.html

ROLLBACK TO sp1;
来源：http://dali.316326.xyz/Article/details/gtucufscvx.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gthoseyotq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gogol.net.cn/Article/details/gtxhlgllxg.html

[Q70] 更新统计信息
来源：http://dali.birdmap.top/Article/details/gtggbrgwdu.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmomuzjya.html

[Q71] 查看建表语句
来源：http://dali.guowangkeji.top/Article/details/gteuprppjx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gtqyxjcvnd.html

[Q72] 查看索引
来源：http://dali.shanyushiyangtech.top/Article/details/gthhqcdesi.html

SHOW INDEX FROM users;
来源：http://dali.daria6918.cn/Article/details/gtbhxmspui.html

[Q73] 查看表状态
来源：http://dali.chenzaomai.com/Article/details/gtrzgwsfke.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.andypj.xyz/Article/details/gtwyibyrgr.html

[Q74] 强制使用索引
来源：http://dali.hysaishi.cn/Article/details/gtominccoq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj202588.top/Article/details/gtfllsphkj.html

[Q75] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtepkgpqbq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtdrfidczb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gtlciwlonk.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gtcmgcppyo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gtxebhegsk.html

[Q77] 时间加减
来源：http://dali.gzhubu.top/Article/details/gtjrvicbrn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xylfe.cn/Article/details/gtighfayzb.html

[Q78] 当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfhvnbcf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gtcrwjanjy.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtkmlbxpjm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhixingplan.top/Article/details/gtaqjivtdm.html

[Q80] 字符串截取
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgerprsn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtavbpcqcn.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtbqpdqtic.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.iojbl.cn/Article/details/gtrupmkliw.html

[Q82] 字符长度与字节长度
来源：http://dali.meibo888.top/Article/details/gtswsasmxk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtpwmrwmds.html

[Q83] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gthdlvdwek.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtjmajfhyi.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gtamfmxfvo.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtahthgjcn.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gtkwipnlyh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xinyue.icu/Article/details/gtbhnreanx.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gtswtbhvam.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gtzestidot.html

[Q87] JSON 字段做条件
来源：http://dali.yangfankeji.com/Article/details/gtbqgasgzz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gtddbkbmeq.html

[Q88] 行转列（条件聚合）
来源：http://dali.haohaochexian.top/Article/details/gtkjugxxes.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gtqpkdjgnh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbetffnr.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gtkbfdxynz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tanke756.top/Article/details/gtubsryprc.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gtolcdjmqf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gttehwnhph.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtkgwvogts.html

R. Bash 专题
来源：http://dali.yangfankeji.com/Article/details/gtywibdexo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gttovcawoa.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gthhqenrsd.html

#!/usr/bin/env bash
来源：http://dali.zhixingplan.top/Article/details/gtcpxmrxqc.html

set -euo pipefail
来源：http://dali.iojbl.cn/Article/details/gtwjqxlbgi.html

[R02] 变量赋值与使用
来源：http://dali.zycfv.cn/Article/details/gtuxnypiiv.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gtvuvmvvmv.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gtrqsfcrzo.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gtkstdrava.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gthwyshsei.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.havefunace.top/Article/details/gtsngjgdso.html

[R05] 参数默认值
来源：http://dali.jianghu66.top/Article/details/gtndnaihgq.html

name="${1:-default}"
来源：http://dali.aibaodan.cn/Article/details/gtfliivege.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gtbftzqcoi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtmqpokeuw.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gtikktfkcd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtzaeteezz.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtdvcdnont.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenlongwang.top/Article/details/gtvsqjrlxb.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtaayrrvjh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gtoikczqew.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtypjeolom.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtjoygmykt.html

[R11] case 多分支
来源：http://dali.sysykeji.top/Article/details/gtpikiikbz.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gtgmigoohx.html

start) echo "启动" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtphanpnyi.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gtbbnstssg.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtrtnspblf.html

esac
来源：http://dali.xziqi.cn/Article/details/gttwmlqpck.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gtvstjlxez.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhengqikj.top/Article/details/gtuuczzmki.html

[R13] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gtghxdoswt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwmjlesg.html

[R14] C 风格 for
来源：http://dali.yj202588.top/Article/details/gtsvecjfyx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtnnvqrzwr.html

[R15] while 逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtsyylwqwi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtxvdjbuuj.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gtxgkweuqt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtziqvhdle.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gtiyzissfc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guowangkeji.top/Article/details/gtfecgqpiq.html

[R18] 遍历数组
来源：http://dali.daria6918.cn/Article/details/gtvpiwzhwo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gtezevnxzt.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gttervhxyh.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gtdxvljqjo.html

[R20] 关联数组（字典）
来源：http://dali.ybcxt.top/Article/details/gtzokfdver.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fengsongda.top/Article/details/gtzssbfbmf.html

[R21] 字符串长度
来源：http://dali.mhx1999.top/Article/details/gtwzvhlmnn.html

echo "${#s}"
来源：http://dali.tian-w.cn/Article/details/gtfgiutvcg.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqngfget.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gtgfzqxrtt.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtjeoxggse.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhiwuduotai.top/Article/details/gtkwmrlknr.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtdsmjqccc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gtwwpuuror.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhengqikj.top/Article/details/gtcgutxpmm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ehwqpu.com/Article/details/gtcbodbxxa.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gtnauwsboy.html

now=$(date +%F); echo "$now"
来源：http://dali.chenzaomai.com/Article/details/gtxyddzzka.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gtflxhayrx.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gtoyydffwn.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gtfzyalfcp.html

echo "scale=2; 10/3" | bc
来源：http://dali.yonumen.top/Article/details/gttsefvgoq.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtpgzbslle.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gtbjbcyqhf.html

[R30] 函数返回状态码
来源：http://dali.havefunace.top/Article/details/gtbjjtmqnb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.feifeiyinyue.top/Article/details/gtzxisrxpl.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gtaieksium.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gtbckoqpxx.html

[R32] 参数个数校验
来源：http://dali.shangyingyoupin.top/Article/details/gtpneqgpim.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtgaweihze.html

[R33] 捕获错误并提示行号
来源：http://dali.chenlongwang.top/Article/details/gtwldtbwcf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlhraahz.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gttjsecryh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtyrvkcqtn.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gtjnpuolvy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.c1oappe.top/Article/details/gtnnmemeza.html

[R36] 并发执行多个任务
来源：http://dali.hongshengwenyu.top/Article/details/gtwrpijmep.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gtfqrknzqq.html

[R37] 把输出赋给变量
来源：http://dali.daxiang520.top/Article/details/gttxrnjxhp.html

files=$(ls -1)
来源：http://dali.hnqzz.top/Article/details/gtxkclhajn.html

[R38] 管道串联
来源：http://dali.wangshuangyany.cn/Article/details/gtazebyxje.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenjidiqi.icu/Article/details/gtzdaezacj.html

[R39] 重定向标准输出与错误
来源：http://dali.pycfn.com/Article/details/gtdrbxsfqg.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtpgfjfsqz.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gtkrzbcvek.html

echo "log" >> out.log
来源：http://dali.gogol.net.cn/Article/details/gtvrkerqvi.html

[R41] 丢弃输出
来源：http://dali.ivvv.top/Article/details/gtpfbjgzfu.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gtaettfbkb.html

[R42] 输入重定向
来源：http://dali.aibaodan.cn/Article/details/gturwerszr.html

wc -l < a.txt
来源：http://dali.haohaochexian.top/Article/details/gthtazzomw.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gtiwqgfpkz.html


<!-- 参考信息 -->