代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jiagoushi.top/Article/details/gt2tnstgejf.html

);
来源：http://dali.chenzaomai.com/Article/details/gt2bvypwkrw.html

[Q02] 创建带外键的表
来源：http://dali.daria6918.cn/Article/details/gt2estrwwzr.html

CREATE TABLE orders (
来源：http://dali.xinyue.icu/Article/details/gt2nstntmwq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdgukgoh.html

user_id INT NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gt2vnwwgxop.html

amount DECIMAL(10, 2),
来源：http://dali.ybcxt.top/Article/details/gt2jficasta.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ppjwa.cn/Article/details/gt2zsbhaxcg.html

);
来源：http://dali.chenlongwang.top/Article/details/gt2ykqxcfut.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gt2rpvoazsw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gt2vfllwmhc.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gt2oedbsewj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.meibo888.top/Article/details/gt2cftvwavd.html

[Q05] 重命名列
来源：http://dali.smart0.xyz/Article/details/gt2qezjyusv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhxqrztz.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gt2neuqgbtv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhengqikj.top/Article/details/gt2ducaystw.html

[Q07] 删除表
来源：http://dali.jyoumei.cn/Article/details/gt2dblpzehi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.iojbl.cn/Article/details/gt2rvcxtmoe.html

[Q08] 创建普通索引
来源：http://dali.sxryk.cn/Article/details/gt2ayfdyduy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gt2dhdlsrja.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bphuzwpy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnnelxed.html

[Q10] 插入单行
来源：http://dali.daxiang520.top/Article/details/gt2nhsyircu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.316326.xyz/Article/details/gt2awcfekbs.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gt2mhnvwmhf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gt2clkpgtfs.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxtjvtll.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aizwys.cn/Article/details/gt2fdgcqzfz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sysykeji.top/Article/details/gt2mwfvgosz.html

[Q13] 忽略重复插入
来源：http://dali.mhx1999.top/Article/details/gt2wjdhzmbk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vtxuiwqe.html

[Q14] 存在则更新（upsert）
来源：http://dali.havefunace.top/Article/details/gt2sxrwkcye.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hfpthk.cn/Article/details/gt2drmiouqq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gt2hwgsxogo.html

[Q15] 查询全部
来源：http://dali.feifeiyinyue.top/Article/details/gt2qknplhfz.html

SELECT * FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2iitvtvou.html

[Q16] 查询指定列
来源：http://dali.gaohongyu789.top/Article/details/gt2rhdnncbh.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2epwpizfs.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gt2pxjjkipd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2davdjsay.html

[Q18] 模糊匹配
来源：http://dali.yueranfly.top/Article/details/gt2rhdkxlek.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhongyouzk.top/Article/details/gt2vrasikgm.html

[Q19] 范围查询
来源：http://dali.dianchejie.cn/Article/details/gt2fwkkrxpx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gt2iqfdlzht.html

[Q20] IN 列表
来源：http://dali.jiagoushi.top/Article/details/gt2hhkjpiwx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.c1oappe.top/Article/details/gt2sacltfti.html

[Q21] 空值判断
来源：http://dali.fengsongda.top/Article/details/gt2rtfoesnf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.snrcjt.cn/Article/details/gt2pughlrwh.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gt2gfazmcoj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnxiangtu.top/Article/details/gt2npslomxw.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gt2ujzwpoem.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gt2iaojhygz.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gt2aalkoypt.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2fquxdyju.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gt2toytcrpk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gt2lryrmngl.html

[Q26] 计数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozgjiwld.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2djcgfwmn.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gt2oqfmlsnp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2rsfrgpbi.html

[Q28] 求和与平均
来源：http://dali.jyoumei.cn/Article/details/gt2rpkkyikt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2ssymblow.html

[Q29] 最大最小值
来源：http://dali.ppjwa.cn/Article/details/gt2bhlabzyp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wczyuzwh.html

[Q30] 分组统计
来源：http://dali.bjfxy.top/Article/details/gt2codkhbei.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gt2svuaynkq.html

[Q31] 分组后过滤
来源：http://dali.xinyue.icu/Article/details/gt2qcocntxb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gt2sviifaze.html

[Q32] 分组拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gt2vtrnkiro.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gt2uqshyoyz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gt2qnigpbav.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gt2jzplawyc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.birdmap.top/Article/details/gt2ithvkufz.html

[Q34] 每组取第一条
来源：http://dali.yonumen.top/Article/details/gt2gnlpjfjs.html

SELECT * FROM (
来源：http://dali.chenjidiqi.icu/Article/details/gt2eyhkuswl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.kuanghao11.cn/Article/details/gt2koeiajdx.html

) t WHERE rn = 1;
来源：http://dali.yonumen.top/Article/details/gt2ddvvavbf.html

[Q35] 内连接
来源：http://dali.ppjwa.cn/Article/details/gt2bdvffuav.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghfokwhz.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gt2owempyqb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gt2qgdaiove.html

[Q37] 右连接
来源：http://dali.chenzaomai.com/Article/details/gt2akghafdt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hfpthk.cn/Article/details/gt2cbqnimux.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gt2ttkgovun.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.redwolf501.top/Article/details/gt2wnyevhzz.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gt2fhvnhbes.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dashuyun.cn/Article/details/gt2aqrwhtyx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmhiyqtd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gzhubu.top/Article/details/gt2ohoygwdc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gt2ddetundt.html

[Q41] 多表连接
来源：http://dali.cucudq.cn/Article/details/gt2kglvclmc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.redwolf501.top/Article/details/gt2zuyosasr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jyoumei.cn/Article/details/gt2rshnkorz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gt2irvysyha.html

[Q42] 连接条件附加过滤
来源：http://dali.gzhubu.top/Article/details/gt2wiwlekef.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gt2hsxfzddz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cashguo.top/Article/details/gt2dtkimafk.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gt2cgekafwn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258.top/Article/details/gt2lebbgzcx.html

[Q44] IN 子查询
来源：http://dali.dashuyun.cn/Article/details/gt2kazmrbyc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwdcbcvq.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gt2pjbrizoc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gt2geevkmgo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2yibrboqo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gt2ncqerymj.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gt2ybfhediq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gaohongyu789.top/Article/details/gt2mchdfrck.html

[Q48] CTE 公用表表达式
来源：http://dali.yangfankeji.com/Article/details/gt2snrxvscx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxttihok.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gt2ymjvecsz.html

[Q49] 更新单行
来源：http://dali.nanxuanxn.top/Article/details/gt2irvfqhij.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gt2zatdrjgc.html

[Q50] 批量更新
来源：http://dali.fengsongda.top/Article/details/gt2yheemepp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.andypj.xyz/Article/details/gt2aviblocw.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gt2dzzzalaz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shuidangran.top/Article/details/gt2tjdrigix.html

[Q52] 删除指定行
来源：http://dali.dianchejie.cn/Article/details/gt2vcynrnlq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gt2brtovcnf.html

[Q53] 按条件删除
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvwdrewx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gt2ossipqaj.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gt2shoxrvrr.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gt2xomivctc.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gt2pjtxdtom.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gt2wmogysdi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gt2lqgjkghg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gt2qztxmezf.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gt2fbfdpvfo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2dmicrfli.html

[Q58] 累计求和
来源：http://dali.zdqjudy.top/Article/details/gt2qrzggsjb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2qcwkpvrk.html

[Q59] 分组内累计
来源：http://dali.hysaishi.cn/Article/details/gt2vrsokchl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2jqmlkiqt.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gt2lxjjjqth.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.bjfxy.top/Article/details/gt2zfgcboph.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2lkcwozvb.html

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gt2cvukuvcp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2aiutvpbb.html

[Q62] 分组占比
来源：http://dali.0kj1m.cn/Article/details/gt2jmjieiel.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gt2siicidcu.html

[Q63] 开启事务
来源：http://dali.sysykeji.top/Article/details/gt2jdokezjr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258.top/Article/details/gt2zmrmgutn.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gt2ayxxxczc.html

COMMIT;
来源：http://dali.guowangkeji.top/Article/details/gt2kibmhbhj.html

[Q65] 回滚事务
来源：http://dali.yanxiufei.cn/Article/details/gt2jujinjew.html

ROLLBACK;
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvhebptb.html

[Q66] 行锁查询
来源：http://dali.haohaochexian.top/Article/details/gt2ntkjcmar.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gt2esxfcowe.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gt2wfsqpznr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xziqi.cn/Article/details/gt2gawcmwsd.html

[Q68] 保存点
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozvoyevy.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gt2cbcrwwla.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gt2arfzukah.html

[Q69] 查看执行计划
来源：http://dali.daxiang520.top/Article/details/gt2dtggwzsj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xylfe.cn/Article/details/gt2fsqciqpk.html

[Q70] 更新统计信息
来源：http://dali.vqdsnc.cn/Article/details/gt2taaceaem.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gt2yvmacyxp.html

[Q71] 查看建表语句
来源：http://dali.yuanzhike.top/Article/details/gt2uszfzvzd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gt2gverrewl.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gt2ofapjete.html

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2slqfhwox.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gt2vkaujgbw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gt2ntxlozhk.html

[Q74] 强制使用索引
来源：http://dali.gogol.net.cn/Article/details/gt2gqaapyrp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gt2vqafqlyx.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gt2myafiusl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rshmujac.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.bjfxy.top/Article/details/gt2gafvuxzf.html

[Q76] 按天统计
来源：http://dali.yueranfly.top/Article/details/gt2hmmzvhns.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ivvv.top/Article/details/gt2xfrnanei.html

[Q77] 时间加减
来源：http://dali.nanxinkj.top/Article/details/gt2mjhbhawx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gt2jfccwsso.html

[Q78] 当前时间
来源：http://dali.yonumen.top/Article/details/gt2mjkjsckc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yvedp.cn/Article/details/gt2vxvwkwrh.html

[Q79] 字符串拼接
来源：http://dali.tian-w.cn/Article/details/gt2siunwekv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gt2wqzvvbjj.html

[Q80] 字符串截取
来源：http://dali.cqqwz.cn/Article/details/gt2gfixikib.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2fqevxwmi.html

[Q81] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gt2boufgoox.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2cweuykde.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gt2twngqdrz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2ycdujtsh.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2fqtuvfqu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpyjvjxp.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gt2laeblmjh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2talzshxd.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gt2ayqcifmg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ehwqpu.com/Article/details/gt2xazhlnae.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gt2ezbqhwth.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.meibo888.top/Article/details/gt2khhxhfqy.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigfzy.top/Article/details/gt2rpbermve.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gt2wxgkvxme.html

[Q88] 行转列（条件聚合）
来源：http://dali.ehwqpu.com/Article/details/gt2yrzpzjfy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gt2jetsvuad.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2ayjmrmlf.html

[Q89] 判断表是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2fflxactn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenlongwang.top/Article/details/gt2bpuimvtl.html

[Q90] 生成序号列
来源：http://dali.0kj1m.cn/Article/details/gt2vbekxmxm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gt2gkbcgeai.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ipplgqiv.html

R. Bash 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cvaylloj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2fybktunv.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gt2smqxhypm.html

#!/usr/bin/env bash
来源：http://dali.yj20258888.top/Article/details/gt2bpthawxh.html

set -euo pipefail
来源：http://dali.hfpthk.cn/Article/details/gt2ckgnhcgs.html

[R02] 变量赋值与使用
来源：http://dali.svipenyu.cn/Article/details/gt2hxrakypn.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdefsakn.html

[R03] 只读变量
来源：http://dali.tanke756.top/Article/details/gt2mxbaofqm.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gt2ntolxnkr.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gt2rwkpqbfp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gt2ghsrshha.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gt2sorjkpww.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gt2jctjjvps.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gt2tefahzyo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2mqsrxsjy.html

[R07] if 判断文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2clmnmkdv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shzxlz.cn/Article/details/gt2sxzbdtls.html

[R08] 数值比较
来源：http://dali.jqgufenzy.top/Article/details/gt2rbwxopgr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2bqvzwjvh.html

[R09] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gt2ynkpcgqk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.iojbl.cn/Article/details/gt2iyhftnvl.html

[R10] 正则匹配
来源：http://dali.pycfn.com/Article/details/gt2ytruvepx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gt2xlhkoqbn.html

[R11] case 多分支
来源：http://dali.yj20258888.top/Article/details/gt2albmkgwf.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gt2gzympqoo.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gt2brlzvnxu.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gt2znjfcbcg.html

*)     echo "未知命令" ;;
来源：http://dali.daxiang520.top/Article/details/gt2nwpbeckb.html

esac
来源：http://dali.zdqjudy.top/Article/details/gt2vmancmox.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gt2ednoawgw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzyrtkhx.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gt2xtqticso.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gt2cemgddnj.html

[R14] C 风格 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2udqksfwp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gt2auwhohfy.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gt2frycjdcp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pycfn.com/Article/details/gt2lsydwmpk.html

[R16] until 等待条件
来源：http://dali.yuanzhike.top/Article/details/gt2fbifuflf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gt2zigpbufl.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gt2adjtdbru.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kuhnnecb.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gt2eaphfaff.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2jmnzycrc.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2gltaywjf.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gt2qsropszi.html

[R20] 关联数组（字典）
来源：http://dali.smart0.xyz/Article/details/gt2rtjezlkz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gt2kjobgyup.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gt2eogsduwi.html

echo "${#s}"
来源：http://dali.tianlin.xyz/Article/details/gt2qafvwocj.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gt2aapxpsbu.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gt2qkiglupg.html

[R23] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gt2kyrzdxyh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbhopcma.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gt2foxfbxtq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gt2knkuaqpt.html

[R25] 去后缀 / 去前缀
来源：http://dali.yueranfly.top/Article/details/gt2hlxetqaw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gt2qenbzsyj.html

[R26] 命令替换
来源：http://dali.ivvv.top/Article/details/gt2fryzubvd.html

now=$(date +%F); echo "$now"
来源：http://dali.vqdsnc.cn/Article/details/gt2gymspznk.html

[R27] 算术展开
来源：http://dali.hfpthk.cn/Article/details/gt2uynlfyda.html

echo $((1 + 2 * 3))
来源：http://dali.ehwqpu.com/Article/details/gt2fphmulqt.html

[R28] 浮点运算
来源：http://dali.dashuyun.cn/Article/details/gt2wcklioaa.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gt2xzsckiew.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gt2uhfhnzqq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jyoumei.cn/Article/details/gt2nochfful.html

[R30] 函数返回状态码
来源：http://dali.xylfe.cn/Article/details/gt2mwayensp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gt2keevvatv.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gt2mrjrqvfi.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gt2tbmwisbr.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlfnakmt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gt2gdsojcxb.html

[R33] 捕获错误并提示行号
来源：http://dali.nwbrower.top/Article/details/gt2qqaomfsc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.meibo888.top/Article/details/gt2btyfdmwm.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gt2kpynrmak.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmsdecgt.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gt2clgmcedk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cdnleiting.top/Article/details/gt2nhojzmfh.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gt2kdathgpq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gaohongyu789.top/Article/details/gt2gpmxyhwx.html

[R37] 把输出赋给变量
来源：http://dali.xinyue.icu/Article/details/gt2hdshnvub.html

files=$(ls -1)
来源：http://dali.guowangkeji.top/Article/details/gt2rsphrbnb.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gt2frwcilaj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.meibo888.top/Article/details/gt2qwnsfftl.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gt2ccivwqxl.html

cmd > out.log 2>&1
来源：http://dali.jianghu66.top/Article/details/gt2gpqrfyfc.html

[R40] 追加写日志
来源：http://dali.gzhubu.top/Article/details/gt2phdfdimu.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gt2kgjtophz.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gt2deqyjjnb.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gt2xhatmutb.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gt2ssttliws.html

wc -l < a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2iskbuqzr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jskxetsf.html

find . -name "*.log" -type f
来源：http://dali.316326.xyz/Article/details/gt2fdxsbtaq.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gt2atvyxwoa.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gt2tzutjvsx.html

[R45] 批量删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdkwibus.html

find . -name "*.tmp" -delete
来源：http://dali.jianghu66.top/Article/details/gt2fgnlhern.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gt2polpnosm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dashuyun.cn/Article/details/gt2qhyaxxap.html

[R47] sed 单行替换
来源：http://dali.guannengcc.top/Article/details/gt2bblauomt.html


<!-- 参考信息 -->