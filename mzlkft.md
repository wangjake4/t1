代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gt2lllhccja.html

user_id INT NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gt2jynjlhbc.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gt2mffgohmh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gt2usuwzvbt.html

);
来源：http://dali.gaohongyu789.top/Article/details/gt2dkkioocp.html

[Q03] 增加列
来源：http://dali.iojbl.cn/Article/details/gt2lqltpzpm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgfzy.top/Article/details/gt2pwxxsbmr.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gt2yfleybfb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgufenzy.top/Article/details/gt2mmnqmqmm.html

[Q05] 重命名列
来源：http://dali.yuanzhike.top/Article/details/gt2djfobmwv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gt2bspaunik.html

[Q06] 删除列
来源：http://dali.wangshuangyany.cn/Article/details/gt2acscxtxt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ehwqpu.com/Article/details/gt2ghohpzyf.html

[Q07] 删除表
来源：http://dali.jqgfzy.top/Article/details/gt2sjweyjlv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.havefunace.top/Article/details/gt2ouwqmbws.html

[Q08] 创建普通索引
来源：http://dali.hnxiangtu.top/Article/details/gt2bzegsezf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gt2yexmgvqn.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gt2dhpzttvo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gt2ofdqldne.html

[Q10] 插入单行
来源：http://dali.yangfankeji.com/Article/details/gt2xazppcpn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xinyue.icu/Article/details/gt2odiysark.html

[Q11] 一次插入多行
来源：http://dali.ppjwa.cn/Article/details/gt2lhawrnfz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjvleuha.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmtbipmn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gt2sludgguj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltkjteli.html

[Q13] 忽略重复插入
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwjikaea.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2reqhotzy.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gt2ndotjwvd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yueranfly.top/Article/details/gt2mvvpfyfo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zdqjudy.top/Article/details/gt2khvfitjs.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gt2kbwlthbx.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2gvcojyxp.html

[Q16] 查询指定列
来源：http://dali.wangshuangyany.cn/Article/details/gt2imojkhch.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2fvrkrrcx.html

[Q17] 条件查询
来源：http://dali.xinyue.icu/Article/details/gt2mbpiqiih.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2qxljslno.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gt2elvdojob.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gt2indqpaac.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gt2avrtmczn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gt2zhcrjyja.html

[Q20] IN 列表
来源：http://dali.birdmap.top/Article/details/gt2bvjtlkxz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pycfn.com/Article/details/gt2dueevswx.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gt2kddcgvql.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.quarkkingdee.top/Article/details/gt2bkojibgu.html

[Q22] 排序
来源：http://dali.yangfankeji.com/Article/details/gt2rmiclfjh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aizwys.cn/Article/details/gt2hpsgacfp.html

[Q23] 分页
来源：http://dali.pengpengdd.cyou/Article/details/gt2tntxecwz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sysykeji.top/Article/details/gt2tcttbqmo.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gt2bxcskbul.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2sbwctnnx.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gt2ryrldjif.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gt2vqtfmboo.html

[Q26] 计数
来源：http://dali.shuidangran.top/Article/details/gt2benmhijh.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2rujmrnrc.html

[Q27] 条件计数
来源：http://dali.gotoacloud.top/Article/details/gt2svdntfdm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2cdnedxlc.html

[Q28] 求和与平均
来源：http://dali.yj20258.top/Article/details/gt2fphfpwrd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2qtsnsgcy.html

[Q29] 最大最小值
来源：http://dali.yj20258888.top/Article/details/gt2ysyuipsz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2vtfpdobn.html

[Q30] 分组统计
来源：http://dali.shzxlz.cn/Article/details/gt2zoysdnhe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gt2pejqncvw.html

[Q31] 分组后过滤
来源：http://dali.nanxinkj.top/Article/details/gt2fdsdvyth.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gt2ftqvrcmc.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gt2ighyfnxz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2uxszohws.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gogol.net.cn/Article/details/gt2mzjxrmfc.html

[Q33] 多列分组
来源：http://dali.daria6918.cn/Article/details/gt2cfddbyyq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zdqjudy.top/Article/details/gt2bsfqxoaq.html

[Q34] 每组取第一条
来源：http://dali.zhengqikj.top/Article/details/gt2tjblkjqi.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gt2nsqpmvmn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hammf.cn/Article/details/gt2sjlkzgjt.html

) t WHERE rn = 1;
来源：http://dali.smart0.xyz/Article/details/gt2nhvvclxq.html

[Q35] 内连接
来源：http://dali.sweek.top/Article/details/gt2htmbqlxa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gt2mpygpnxm.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gt2hblxingo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bbldipwy.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gt2vghbmgqq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jdvokuqk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guannengcc.top/Article/details/gt2edvhbwmb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gt2ovthtmti.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gt2diogaruk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gt2udhnflwi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj202588.top/Article/details/gt2ffsispap.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ydzc1.top/Article/details/gt2xkuputeq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ydzc1.top/Article/details/gt2wvkvofzy.html

[Q41] 多表连接
来源：http://dali.yonumen.top/Article/details/gt2eggctknt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zdqjudy.top/Article/details/gt2mabsxfwk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkxnfyaw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzfuxwc.html

[Q42] 连接条件附加过滤
来源：http://dali.zycfv.cn/Article/details/gt2esdxzexh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.haohaochexian.top/Article/details/gt2royqxocc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.9152youxi.cn/Article/details/gt2ptogvzgp.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gt2hcooggdv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cdnleiting.top/Article/details/gt2xevrsgzf.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gt2zhdfcfpc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhkjqaiz.html

[Q45] EXISTS 判断存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvtulnmv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2ysxtibui.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xinyue.icu/Article/details/gt2dsqrurwr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gt2udgkzzjx.html

[Q47] 与平均值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cifmngkb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sufxvd.cn/Article/details/gt2juphowmr.html

[Q48] CTE 公用表表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylrwshfl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ybcxt.top/Article/details/gt2yzenwdos.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daxiang520.top/Article/details/gt2dnzgdtxi.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gt2mzazsuro.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gt2xpkazqov.html

[Q50] 批量更新
来源：http://dali.jlsjyb.cn/Article/details/gt2xfociety.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shzxlz.cn/Article/details/gt2yynpdvij.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gt2uemvixqx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jianghu66.top/Article/details/gt2ffjaccoq.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gt2henbwcow.html

DELETE FROM users WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2arrfgyxc.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gt2efrhakkl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gt2beegxhfc.html

[Q54] 清空表
来源：http://dali.gogol.net.cn/Article/details/gt2cyjnrure.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gt2cqwizwam.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gt2pwinofam.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gt2avmjxfrj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gt2luhcgxno.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpwavvqa.html

[Q57] 行号
来源：http://dali.svipenyu.cn/Article/details/gt2jurzwkrc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2qambnxmu.html

[Q58] 累计求和
来源：http://dali.havefunace.top/Article/details/gt2hzfcovfm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2wrmyxgpy.html

[Q59] 分组内累计
来源：http://dali.zhoulong.xyz/Article/details/gt2tqnxxjpj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2uftnbmqk.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gt2bmyxosvz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cdnleiting.top/Article/details/gt2zcaeyxeo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2unijpflf.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gt2fholilhn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2wseksmrg.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xplgsfcd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2ybssqued.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gt2ruliiikn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnqzz.top/Article/details/gt2mlrgifzx.html

[Q64] 提交事务
来源：http://dali.hnqzz.top/Article/details/gt2hujbzvwa.html

COMMIT;
来源：http://dali.cashguo.top/Article/details/gt2erioegtw.html

[Q65] 回滚事务
来源：http://dali.cheryme.top/Article/details/gt2befduvzs.html

ROLLBACK;
来源：http://dali.cdnleiting.top/Article/details/gt2drkqfeco.html

[Q66] 行锁查询
来源：http://dali.cqqwz.cn/Article/details/gt2xvxwcmpd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gt2mdafigqv.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gt2xhtllaqf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gt2upivdpgu.html

[Q68] 保存点
来源：http://dali.daxiang520.top/Article/details/gt2xqkevdgc.html

SAVEPOINT sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxtntcxg.html

ROLLBACK TO sp1;
来源：http://dali.yj20258.top/Article/details/gt2pkcrzrwc.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gt2xlojpozy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gt2itfpbaqg.html

[Q70] 更新统计信息
来源：http://dali.zycfv.cn/Article/details/gt2rynswftp.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gt2vnoiojeu.html

[Q71] 查看建表语句
来源：http://dali.sxryk.cn/Article/details/gt2xyixyhyc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gaohongyu789.top/Article/details/gt2arnezhcn.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gt2dxtqptqu.html

SHOW INDEX FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2khdaumdi.html

[Q73] 查看表状态
来源：http://dali.9152youxi.cn/Article/details/gt2bfhlduox.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cashguo.top/Article/details/gt2omlvtrlr.html

[Q74] 强制使用索引
来源：http://dali.cucudq.cn/Article/details/gt2codrvatc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gt2tmaprans.html

[Q75] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gt2yklhmchk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2llezqxcc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hongshengwenyu.top/Article/details/gt2ksgztqdp.html

[Q76] 按天统计
来源：http://dali.iojbl.cn/Article/details/gt2zloaiydf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gt2flmhxmjv.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gt2yqgbxatg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzqymfou.html

[Q78] 当前时间
来源：http://dali.haohaochexian.top/Article/details/gt2efioovyw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.iojbl.cn/Article/details/gt2cdgbvodb.html

[Q79] 字符串拼接
来源：http://dali.c1oappe.top/Article/details/gt2tuvvuvia.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gt2qrtffufq.html

[Q80] 字符串截取
来源：http://dali.kuanghao11.cn/Article/details/gt2irvgwpeb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2fwcmgfhc.html

[Q81] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gt2ylopzfxq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2femapydw.html

[Q82] 字符长度与字节长度
来源：http://dali.hnqzz.top/Article/details/gt2ttdlnlsu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eozhnskr.html

[Q83] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gt2dmoaelxw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2syfnubxq.html

[Q84] 去除首尾空格
来源：http://dali.chenjidiqi.icu/Article/details/gt2zyojdhay.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2lpmjdkpv.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gt2xpjojewo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgfzy.top/Article/details/gt2fdybsthu.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2duixxbwp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gt2gycbvxrv.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gt2bhwqhdmd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nwbrower.top/Article/details/gt2uawvbuxo.html

[Q88] 行转列（条件聚合）
来源：http://dali.gotoacloud.top/Article/details/gt2akoebyal.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gt2fcxmpgxj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gt2jplhqqjk.html

[Q89] 判断表是否存在
来源：http://dali.pycfn.com/Article/details/gt2sbyoubir.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gt2fjxetieg.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gt2nmprkwhn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daxiang520.top/Article/details/gt2wzenpbfz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2pavkjbao.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gt2jzeazoie.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2rrzjgspb.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gt2gdwhwgam.html

#!/usr/bin/env bash
来源：http://dali.gogol.net.cn/Article/details/gt2efyhhopx.html

set -euo pipefail
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivbzfhcm.html

[R02] 变量赋值与使用
来源：http://dali.jiagoushi.top/Article/details/gt2xdptoccv.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gt2qgfuzrvx.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gt2rkqolswu.html

readonly PI=3.14
来源：http://dali.jqgufenzy.top/Article/details/gt2nockgenc.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gt2jskgxuol.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhiwuduotai.top/Article/details/gt2parddojo.html

[R05] 参数默认值
来源：http://dali.sufxvd.cn/Article/details/gt2kbyzbktu.html

name="${1:-default}"
来源：http://dali.wangdashe.top/Article/details/gt2tsowjxaz.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gt2luexqfsn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gt2kapgfkub.html

[R07] if 判断文件
来源：http://dali.ivvv.top/Article/details/gt2jcjehvwj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gt2pbcltlxy.html

[R08] 数值比较
来源：http://dali.hammf.cn/Article/details/gt2lbchodso.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2wnwxwmxr.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2txqhpobw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2pmjhqcqd.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gt2wpzolcbi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gt2cwrbdkmi.html

[R11] case 多分支
来源：http://dali.tanke756.top/Article/details/gt2ztruutuz.html

case "$1" in
来源：http://dali.quarkkingdee.top/Article/details/gt2yhrivgdi.html

start) echo "启动" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzqhnmly.html

stop)  echo "停止" ;;
来源：http://dali.redwolf501.top/Article/details/gt2lmclwohl.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gt2lkblwisi.html

esac
来源：http://dali.andypj.xyz/Article/details/gt2hubcyznd.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gt2msslmkhn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kkzclefc.html

[R13] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gt2xwdtxeas.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lybpblba.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gt2erfptzjl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gt2lvszxxhj.html

[R15] while 逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2euksmbky.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ehwqpu.com/Article/details/gt2vutnnimk.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gt2vyhteufo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2iertfqil.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2viudpocz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gt2vznytzkj.html

[R18] 遍历数组
来源：http://dali.yj20258888.top/Article/details/gt2tsoybqng.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gt2xjmxtolf.html

[R19] 数组长度
来源：http://dali.wangdashe.top/Article/details/gt2atoecypc.html

echo "${#arr[@]}"
来源：http://dali.birdmap.top/Article/details/gt2uvjquyem.html

[R20] 关联数组（字典）
来源：http://dali.cheryme.top/Article/details/gt2jvrnzxfo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guannengcc.top/Article/details/gt2ddqxivas.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gt2bhyfgvor.html

echo "${#s}"
来源：http://dali.yj202588.top/Article/details/gt2wakndqax.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gt2ucqqjhvt.html

echo "${s:0:5}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygikepdf.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gt2lbpjluuu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvfxtjlw.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gt2shyuozog.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuanzx.com/Article/details/gt2qyxzuqja.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigufen.top/Article/details/gt2eyrpxrgr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kftqzgbj.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gt2zsfkcixm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gt2vlqbnckt.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gt2ratiykcu.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gt2uctszelr.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gt2megglttj.html

echo "scale=2; 10/3" | bc
来源：http://dali.gaohongyu789.top/Article/details/gt2gikpllzu.html

[R29] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gt2dfuecvoj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gt2grmobjxc.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gt2hguautge.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pnjossos.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gt2vkeygctv.html

f() { local x=1; echo "$x"; }
来源：http://dali.yvedp.cn/Article/details/gt2qsqqmgkm.html

[R32] 参数个数校验
来源：http://dali.yangfankeji.com/Article/details/gt2tnzyvtub.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wibqpqpr.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gt2vwiiusfw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gt2qebzljzd.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gt2izdrqydi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gt2xnfzlfwc.html

[R35] 后台执行并等待
来源：http://dali.hywenlv.cn/Article/details/gt2keuhxunp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gt2kvfrwhke.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gt2rtfdxbhw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gt2wyhxdrdp.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzqxpiau.html

files=$(ls -1)
来源：http://dali.dianchejie.cn/Article/details/gt2ngrdbeap.html

[R38] 管道串联
来源：http://dali.cucudq.cn/Article/details/gt2onnwfaov.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guowangkeji.top/Article/details/gt2tlpasbat.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gt2srjlbljy.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gt2qimgjjvt.html

[R40] 追加写日志
来源：http://dali.wangdashe.top/Article/details/gt2nkpaescw.html

echo "log" >> out.log
来源：http://dali.tian-w.cn/Article/details/gt2nculapxv.html

[R41] 丢弃输出
来源：http://dali.nanxinkj.top/Article/details/gt2epmsnqxr.html

cmd >/dev/null 2>&1
来源：http://dali.chenzaomai.com/Article/details/gt2lwiyierj.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gt2mgyybupe.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhpywjfs.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gt2xztanzzg.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gt2qiubeqfk.html

[R44] 按修改时间查找
来源：http://dali.jinqigfzy.top/Article/details/gt2xizwxwlc.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gt2zhyiuehd.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gt2yjzsnznv.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gt2frdykjia.html

[R46] 递归替换文件内容
来源：http://dali.haohaochexian.top/Article/details/gt2sdlwbpld.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zdqjudy.top/Article/details/gt2odecoebo.html

[R47] sed 单行替换
来源：http://dali.sufxvd.cn/Article/details/gt2grcgrhkh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2lpuujeti.html

[R48] awk 取指定列
来源：http://dali.cheryme.top/Article/details/gt2juuzujjr.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gt2wmtaatcd.html

[R49] awk 带条件
来源：http://dali.cucudq.cn/Article/details/gt2xgqiakgf.html


<!-- 参考信息 -->