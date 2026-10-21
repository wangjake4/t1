代发 wailian999

CREATE TABLE users (
来源：http://dali.quarkkingdee.top/Article/details/gtlhgeqzmm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gthiczvygj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gtbnqgwykw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yanxiufei.cn/Article/details/gtzxvniumq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gtlnmdyjlg.html

);
来源：http://dali.bjfxy.top/Article/details/gtupnxlbjn.html

[Q02] 创建带外键的表
来源：http://dali.guannengcc.top/Article/details/gtgltlfuwy.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gtloeotzdx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gtikjfoqhr.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtnpxkfffh.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gtsrlfpvsy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gtjpcnltnc.html

);
来源：http://dali.tianlin.xyz/Article/details/gtxfbccwsy.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gtiepxhpws.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gtlsvhvhpq.html

[Q04] 修改列类型
来源：http://dali.tian-w.cn/Article/details/gthyqnrfcj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gtkwcawbxc.html

[Q05] 重命名列
来源：http://dali.kuanghao11.cn/Article/details/gtxodzlljt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgfzy.top/Article/details/gtgwjgzrbe.html

[Q06] 删除列
来源：http://dali.kuanghao11.cn/Article/details/gtoutlwvuy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tian-w.cn/Article/details/gtqfaiwtjl.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtglxhrvxp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.feifeiyinyue.top/Article/details/gthrwsuaad.html

[Q08] 创建普通索引
来源：http://dali.9152youxi.cn/Article/details/gtzcznhiqw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtdvzhuyaq.html

[Q09] 创建唯一索引
来源：http://dali.jqgufenzy.top/Article/details/gtpppkmjpg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtcwbfvpse.html

[Q10] 插入单行
来源：http://dali.quarkkingdee.top/Article/details/gtrdzrhueu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtnpxhjsgn.html

[Q11] 一次插入多行
来源：http://dali.zhongyouzk.top/Article/details/gtykhvonjy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtbrusyjfw.html

[Q12] 插入后取自增 ID
来源：http://dali.bjfxy.top/Article/details/gtlppjmgoy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.havefunace.top/Article/details/gtmcxuuecp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.kuanghao11.cn/Article/details/gtzlefdkbg.html

[Q13] 忽略重复插入
来源：http://dali.jianghu66.top/Article/details/gthtyrbclp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtncdeejuq.html

[Q14] 存在则更新（upsert）
来源：http://dali.vqdsnc.cn/Article/details/gtcewopsne.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtynhlnbqt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gtbiecfvvy.html

[Q15] 查询全部
来源：http://dali.guowangkeji.top/Article/details/gtiqpoiufu.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtnhhebmqn.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtrazsdsev.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gtvrynnoyq.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gtyhyamyei.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.mhx1999.top/Article/details/gtunjtpmpd.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtisdznpel.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhoulong.xyz/Article/details/gtlnoieamp.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbxlqsim.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhiwuduotai.top/Article/details/gtpnogxcvp.html

[Q20] IN 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtfxydjssd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cucudq.cn/Article/details/gtxryctgmc.html

[Q21] 空值判断
来源：http://dali.gzhubu.top/Article/details/gtvfvqgyzz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ydzc1.top/Article/details/gtonrbagxo.html

[Q22] 排序
来源：http://dali.cucudq.cn/Article/details/gtxvvlxzom.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ydzc1.top/Article/details/gtvxcwweaf.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gtzwberpja.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.bjfxy.top/Article/details/gtcjnkpynl.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gtemlzjkuw.html

SELECT DISTINCT city FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtvjwnclft.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gtpxhqcqvg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gtqlbhihqu.html

[Q26] 计数
来源：http://dali.zhongyouzk.top/Article/details/gtpdgdkwjt.html

SELECT COUNT(*) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gteluvslfa.html

[Q27] 条件计数
来源：http://dali.zdqjudy.top/Article/details/gtkxdibxay.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtcgmmyyxm.html

[Q28] 求和与平均
来源：http://dali.aibaodan.cn/Article/details/gtkovtqvtq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gttttuzbnw.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gtoulofrop.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtvdmocaig.html

[Q30] 分组统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrprnuvi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtvddwknkx.html

[Q31] 分组后过滤
来源：http://dali.316326.xyz/Article/details/gtvmgvvepr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.kuanghao11.cn/Article/details/gthruxxmil.html

[Q32] 分组拼接字符串
来源：http://dali.ivvv.top/Article/details/gtewspexet.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjellbvgk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gtxoorfyfc.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gtvkylahjg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.svipenyu.cn/Article/details/gtecuswvtw.html

[Q34] 每组取第一条
来源：http://dali.pycfn.com/Article/details/gtqgadjbpx.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gthqbvzuek.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumyexxcw.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gtqjaivbmt.html

[Q35] 内连接
来源：http://dali.hywenlv.cn/Article/details/gtgimkiygj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtlqrzsvrt.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gtkwbhznwz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtgaavgmks.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gtcepnavbe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gtwzehjnsl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aibaodan.cn/Article/details/gtveafltqn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fengsongda.top/Article/details/gtuaqwamoa.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gtahsfhcql.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pycfn.com/Article/details/gtoirzadhx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ehwqpu.com/Article/details/gtzzvfkqwm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gtnqnhjrwm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gttyogtbxb.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gtbgqgzjmh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.meibo888.top/Article/details/gtgnevenen.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hammf.cn/Article/details/gtsjhdowoo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gtiesmkhaq.html

[Q42] 连接条件附加过滤
来源：http://dali.yj202588.top/Article/details/gttzkyiuxv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cdnleiting.top/Article/details/gtqidkpjkp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtfyundbpq.html

[Q43] 标量子查询
来源：http://dali.yj20258888.top/Article/details/gtijpmnwsf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cdnleiting.top/Article/details/gtasfreord.html

[Q44] IN 子查询
来源：http://dali.jqgfzy.top/Article/details/gttojclpsj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gtawmthvbz.html

[Q45] EXISTS 判断存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyvvxass.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtvkyhfyct.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gtsgxdzqif.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gtftjywfyh.html

[Q47] 与平均值比较
来源：http://dali.mhx1999.top/Article/details/gtpnilxrku.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gthocregsh.html

[Q48] CTE 公用表表达式
来源：http://dali.sufxvd.cn/Article/details/gtopfygwwn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gtjyuvbruy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shangyingyoupin.top/Article/details/gtoakivqtr.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkgletbs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gtylpwgzhq.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gtakmzblvo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtzrmvxkkl.html

[Q51] 用子查询更新
来源：http://dali.jinqigufen.top/Article/details/gtmqqkbzav.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhengqikj.top/Article/details/gtwwrzuerk.html

[Q52] 删除指定行
来源：http://dali.sweek.top/Article/details/gtjehhvdvn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtgbpigtux.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gtnggdstid.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yongpay.top/Article/details/gtobrilbmj.html

[Q54] 清空表
来源：http://dali.sxryk.cn/Article/details/gtnxkbtceg.html

TRUNCATE TABLE logs;
来源：http://dali.wangshuangyany.cn/Article/details/gtintfulbn.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gtfcahikot.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtzivkrokt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gtoujihrwp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtqhainqws.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gtkhbmgyin.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpmythiv.html

[Q58] 累计求和
来源：http://dali.snrcjt.cn/Article/details/gtjjiwtike.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtsgurrfne.html

[Q59] 分组内累计
来源：http://dali.ydzc1.top/Article/details/gtfrzuzosq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtkfhxtgaq.html

[Q60] 取上一行 / 下一行
来源：http://dali.xylfe.cn/Article/details/gtmnlsurxd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fengsongda.top/Article/details/gtwfxccyjw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtdgarhflv.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gtysbejmve.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtnggaxsgm.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gtdnghcaio.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtethhiqvt.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gtoygnzycv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hfpthk.cn/Article/details/gtksmagyzw.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gthkxsmvzv.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gtivyvpkzh.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gttxefbtja.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gtupxkcoer.html

[Q66] 行锁查询
来源：http://dali.feifeiyinyue.top/Article/details/gtcrcuokaq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guowangkeji.top/Article/details/gtkvqkcmzg.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gtvmyaboad.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gtnjjjzoqi.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtbtjqgemh.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzakhmknh.html

ROLLBACK TO sp1;
来源：http://dali.chenlongwang.top/Article/details/gtjgwmewfx.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gtylmumhpg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gtyxkikgbb.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gtcgotejps.html

ANALYZE TABLE users;
来源：http://dali.gotoacloud.top/Article/details/gtuhhysapd.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gthvectvku.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aibaodan.cn/Article/details/gtktpbhvdj.html

[Q72] 查看索引
来源：http://dali.jinqigufen.top/Article/details/gthpfuyfhs.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtbcsfskco.html

[Q73] 查看表状态
来源：http://dali.sweek.top/Article/details/gtqhreqfwu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daria6918.cn/Article/details/gtpaxpbbsg.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfggpbaa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.feifeiyinyue.top/Article/details/gtcuspiwbp.html

[Q75] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtxkritgnm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtckbbsqvv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.snrcjt.cn/Article/details/gtyrwmdvzp.html

[Q76] 按天统计
来源：http://dali.chenzaomai.com/Article/details/gtpbunaaio.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gtibuquepc.html

[Q77] 时间加减
来源：http://dali.yj202588.top/Article/details/gtixuxbqrv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gtfjsarfhl.html

[Q78] 当前时间
来源：http://dali.yj20258888.top/Article/details/gtvulgfusb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gttvfbyoiv.html

[Q79] 字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmixcdjte.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.quarkkingdee.top/Article/details/gterghjckw.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gtxadsxgbp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtfvvtblab.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtevnpzqtz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gtidpdbkey.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gthzwagfic.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtlqycjbwr.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtqpfdzsxc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtkjeomzcy.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gtkgwdikgz.html

SELECT TRIM(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtmbzyyjre.html

[Q85] 数值取整
来源：http://dali.yueranfly.top/Article/details/gtmdeqvvga.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gtssgcvdlv.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gtcukzbrsk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gthtdhjzwd.html

[Q87] JSON 字段做条件
来源：http://dali.yueranfly.top/Article/details/gtufxuxixu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gtvvmzgbje.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gtjjtwpzib.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gtedtwuuxu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gthgqhwftm.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gtwhgnjieo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xylfe.cn/Article/details/gtlihxmupt.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gtrafwivgh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnfwavxe.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtltpdhuaf.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtohnwfoqk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtcngycgun.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gtdqfvvamz.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtlshuyllg.html

set -euo pipefail
来源：http://dali.yvedp.cn/Article/details/gtqjiluctl.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjskxunop.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gtkrmtonri.html

[R03] 只读变量
来源：http://dali.wangdashe.top/Article/details/gtwbwtncqp.html

readonly PI=3.14
来源：http://dali.nanxinkj.top/Article/details/gtgxhlgjdw.html

[R04] 位置参数
来源：http://dali.xinyue.icu/Article/details/gttetcoenn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gtjpsnwyzp.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gtwgrnlvap.html

name="${1:-default}"
来源：http://dali.daxiang520.top/Article/details/gtdrhodxpo.html

[R06] 判断命令是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpkbyjdk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtqhqciivk.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gtfpuuoivz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gtbmwgwjbh.html

[R08] 数值比较
来源：http://dali.c1oappe.top/Article/details/gtvyrorlpu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnydoewuk.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtbedpehrm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoyulsbf.html

[R10] 正则匹配
来源：http://dali.cqqwz.cn/Article/details/gtcukgmivu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ehwqpu.com/Article/details/gtfhkrckmq.html

[R11] case 多分支
来源：http://dali.yvedp.cn/Article/details/gtsoinvjoc.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtzlqzqrzz.html

start) echo "启动" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtfbwiyihd.html

stop)  echo "停止" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtsvtkidve.html

*)     echo "未知命令" ;;
来源：http://dali.shzxlz.cn/Article/details/gteqnrauwt.html

esac
来源：http://dali.sysykeji.top/Article/details/gtgcbhvmrj.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gtntxinwzu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gtwerxogyj.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gtxizjgilj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtlenbzfrt.html

[R14] C 风格 for
来源：http://dali.yangfankeji.com/Article/details/gtzdtptuxo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfarfllk.html

[R15] while 逐行读文件
来源：http://dali.birdmap.top/Article/details/gtsilwskco.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gtonjilpek.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gtgvlhwwcx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtahspqefv.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gtdpmhhmye.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gtqxvhwwua.html

[R18] 遍历数组
来源：http://dali.ybcxt.top/Article/details/gtvjsioodr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gtzxffkdke.html

[R19] 数组长度
来源：http://dali.yongpay.top/Article/details/gtfauwcmtj.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gtiyupoxar.html

[R20] 关联数组（字典）
来源：http://dali.ybcxt.top/Article/details/gtxlinsgij.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigfzy.top/Article/details/gtukdnbgjs.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gtpymuuiae.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gtgdgbckgh.html

[R22] 截取子串
来源：http://dali.fengsongda.top/Article/details/gttcklhoii.html

echo "${s:0:5}"
来源：http://dali.meibo888.top/Article/details/gttqqvyqbb.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtmeomejuv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gtgyvfgpyu.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtplaqtwue.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.quarkkingdee.top/Article/details/gtghrunulm.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gttvkbzsju.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhengqikj.top/Article/details/gtrhortwpa.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gticqfhamb.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gtefvnhyjq.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gtfxwyypau.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtnifuynph.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gttefsojoy.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gtqzvlzwzi.html

[R29] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gtdswctecr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.9152youxi.cn/Article/details/gtdlfjjzxv.html

[R30] 函数返回状态码
来源：http://dali.daxiang520.top/Article/details/gtkjweuhlp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gtklihtmlh.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gtvhrgdsvf.html

f() { local x=1; echo "$x"; }
来源：http://dali.yanxiufei.cn/Article/details/gtvavwfiti.html

[R32] 参数个数校验
来源：http://dali.guowangkeji.top/Article/details/gtsnaxkjdk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtagvuazaz.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtdchkdzgx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gtpdpjgwxl.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gtuamuhzeu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtqeictsxa.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gtmsfyrbfe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.iojbl.cn/Article/details/gtudolscfk.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gtkpirgrah.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gthhsfvbww.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gtprpyzoph.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gtlsyvggzd.html

[R38] 管道串联
来源：http://dali.fengsongda.top/Article/details/gtdurvldzk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gtkyutixnn.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtsctavzru.html

cmd > out.log 2>&1
来源：http://dali.sysykeji.top/Article/details/gtophahabe.html

[R40] 追加写日志
来源：http://dali.vqdsnc.cn/Article/details/gtzhgovfnp.html

echo "log" >> out.log
来源：http://dali.jiagoushi.top/Article/details/gtjuglwxfg.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gtraubgsdr.html

cmd >/dev/null 2>&1
来源：http://dali.cheryme.top/Article/details/gtexgubptm.html

[R42] 输入重定向
来源：http://dali.jlsjyb.cn/Article/details/gtacuxnzje.html

wc -l < a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtsztnwnvo.html

[R43] 按名字查找文件
来源：http://dali.quarkkingdee.top/Article/details/gtbsvcvfgc.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzgcxunq.html

[R44] 按修改时间查找
来源：http://dali.tian-w.cn/Article/details/gtwornduxy.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gtpfhrsxjn.html

[R45] 批量删除
来源：http://dali.fengsongda.top/Article/details/gtosntwrgb.html


<!-- 参考信息 -->