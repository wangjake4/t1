代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gtiiszhstf.html

user_id INT NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtlkoqxiio.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gtpqaohift.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pycfn.com/Article/details/gtjrpwiene.html

);
来源：http://dali.shuidangran.top/Article/details/gtyswlcqqg.html

[Q03] 增加列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxguwguh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gtjehefghw.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdlzcxsl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gtflrlfxqk.html

[Q05] 重命名列
来源：http://dali.quarkkingdee.top/Article/details/gtexgcapsa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gtbeitzsam.html

[Q06] 删除列
来源：http://dali.hnxiangtu.top/Article/details/gtbjpouzzi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yangfankeji.com/Article/details/gtdpfrpsqj.html

[Q07] 删除表
来源：http://dali.nanxinkj.top/Article/details/gtayawghnz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnxiangtu.top/Article/details/gtfowlvcna.html

[Q08] 创建普通索引
来源：http://dali.xziqi.cn/Article/details/gttbuionpd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gtntpnqprg.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gtclvcmshr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gthtculpey.html

[Q10] 插入单行
来源：http://dali.ybcxt.top/Article/details/gtqrvsfmdt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.316326.xyz/Article/details/gtvlyczsqo.html

[Q11] 一次插入多行
来源：http://dali.hongshengwenyu.top/Article/details/gtlhjlmksa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fengsongda.top/Article/details/gthomqyryy.html

[Q12] 插入后取自增 ID
来源：http://dali.yuanzhike.top/Article/details/gtjfwwkhog.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.c1oappe.top/Article/details/gtshpxrnrn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gtueszgmlq.html

[Q13] 忽略重复插入
来源：http://dali.nanxuanxn.top/Article/details/gtdxxlwcep.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtvqfgbqso.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigufen.top/Article/details/gtfjxqtpkg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gtbzbloive.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shangyingyoupin.top/Article/details/gtpropxwws.html

[Q15] 查询全部
来源：http://dali.jyoumei.cn/Article/details/gtabyqqhim.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gttdxltpjo.html

[Q16] 查询指定列
来源：http://dali.jinqigufen.top/Article/details/gtgyurjbse.html

SELECT id, name FROM users;
来源：http://dali.c1oappe.top/Article/details/gtjwwaijmc.html

[Q17] 条件查询
来源：http://dali.dashuyun.cn/Article/details/gtaldgnyxx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtagayyudy.html

[Q18] 模糊匹配
来源：http://dali.cucudq.cn/Article/details/gtlbfqxumy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuetiantiany.cn/Article/details/gtpqybecxo.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gtzkmadvun.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gtswbmkgro.html

[Q20] IN 列表
来源：http://dali.birdmap.top/Article/details/gtxvyzxdgo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxinkj.top/Article/details/gtrsqvfjit.html

[Q21] 空值判断
来源：http://dali.yonumen.top/Article/details/gtemhjrctv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.redwolf501.top/Article/details/gtjevncjca.html

[Q22] 排序
来源：http://dali.daria6918.cn/Article/details/gtktrqntmq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhkjbgta.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gtwmuvrkvd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gtkeylcnim.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gtrdkijrdi.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtjhfznoeh.html

[Q25] 只取前 N 条
来源：http://dali.yanxiufei.cn/Article/details/gtjcxjibkf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gtgexvmean.html

[Q26] 计数
来源：http://dali.hnxiangtu.top/Article/details/gtsouydetv.html

SELECT COUNT(*) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtaudewttp.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gtzypdbrga.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gtgfhtaiuq.html

[Q28] 求和与平均
来源：http://dali.meibo888.top/Article/details/gtuoevmluo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtcvaamyhw.html

[Q29] 最大最小值
来源：http://dali.mhx1999.top/Article/details/gtsxxtcooe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtbjdbdxao.html

[Q30] 分组统计
来源：http://dali.tanke756.top/Article/details/gtkpghyffa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtoiufndzk.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtpmbdkjeu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtcgjilyht.html

[Q32] 分组拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtgpsbxqqe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtuhavmbkk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhixingplan.top/Article/details/gtnobrnipq.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gtikrepuea.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gtqwmsdtbx.html

[Q34] 每组取第一条
来源：http://dali.feifeiyinyue.top/Article/details/gtbvgzqzwi.html

SELECT * FROM (
来源：http://dali.bjfxy.top/Article/details/gtqamtolso.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhengqikj.top/Article/details/gtvintkaie.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gttpntyxhe.html

[Q35] 内连接
来源：http://dali.nwbrower.top/Article/details/gtgdrskejs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gtofvljtdk.html

[Q36] 左连接
来源：http://dali.dashuyun.cn/Article/details/gtequkhcuz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtaaovidhh.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gtvqebrxoc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sxryk.cn/Article/details/gtladusthy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sweek.top/Article/details/gtueucweqv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ydzc1.top/Article/details/gtuyzotiiv.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gtqojzrneo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shuidangran.top/Article/details/gtxgxlzmwq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gtskafzviq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hfpthk.cn/Article/details/gtxlbmanju.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.quarkkingdee.top/Article/details/gtvffvpuhf.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gtiaacdqnm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gtbbttnaes.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gtjxhhnznn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jianghu66.top/Article/details/gtgismcalf.html

[Q42] 连接条件附加过滤
来源：http://dali.hysaishi.cn/Article/details/gtqmyrbmpj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gtbtkuzjmw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gtbiyrgofm.html

[Q43] 标量子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtxyofughz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangshuangyany.cn/Article/details/gtlcneuvnl.html

[Q44] IN 子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtqzbowpch.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.redwolf501.top/Article/details/gtsylgqdim.html

[Q45] EXISTS 判断存在
来源：http://dali.kuanghao11.cn/Article/details/gtszzykixc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkvcpfdq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gtbcjzqhoc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtdrutvxdn.html

[Q47] 与平均值比较
来源：http://dali.dashuyun.cn/Article/details/gtkubbnqlr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gtzrtoxbpl.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gtalywhmvm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pycfn.com/Article/details/gthwmhglzy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258.top/Article/details/gtrsckdezg.html

[Q49] 更新单行
来源：http://dali.cdnleiting.top/Article/details/gtchfgpsmv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gtkcsxgzfi.html

[Q50] 批量更新
来源：http://dali.hfpthk.cn/Article/details/gtxsufpwpl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtjrpgldye.html

[Q51] 用子查询更新
来源：http://dali.gotoacloud.top/Article/details/gtgbzuyfqy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gtjtmfcipr.html

[Q52] 删除指定行
来源：http://dali.gaohongyu789.top/Article/details/gtiipsiuwn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtahgyjxfn.html

[Q53] 按条件删除
来源：http://dali.zhongyouzk.top/Article/details/gtnmegugeh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtowlddzep.html

[Q54] 清空表
来源：http://dali.shanyushiyangtech.top/Article/details/gtxaikhrbs.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gtgfianrep.html

[Q55] 排名（并列占位）
来源：http://dali.xylfe.cn/Article/details/gtwqivkhwr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtspmzhfal.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gthcysdian.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtujkowpqp.html

[Q57] 行号
来源：http://dali.yuanzhike.top/Article/details/gtwnvnhyjc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtjlkjmisv.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujwctfxd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtafxiaimm.html

[Q59] 分组内累计
来源：http://dali.jyoumei.cn/Article/details/gtgmhtegqo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtlupjquli.html

[Q60] 取上一行 / 下一行
来源：http://dali.shangyingyoupin.top/Article/details/gtwvasfmcn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgfzy.top/Article/details/gtrncainpw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzagwchte.html

[Q61] 移动平均
来源：http://dali.zhengqikj.top/Article/details/gtizpxeltf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtsrajluzq.html

[Q62] 分组占比
来源：http://dali.9152youxi.cn/Article/details/gtjfzctlzs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtjamvctfz.html

[Q63] 开启事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqdhwgrk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gtrypkdvky.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gteimuzqhz.html

COMMIT;
来源：http://dali.daxiang520.top/Article/details/gtcwsweubh.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gtyjtddwjx.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gtehmrtpur.html

[Q66] 行锁查询
来源：http://dali.nanxuanxn.top/Article/details/gtqjgteksm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgfzy.top/Article/details/gtauyzkanj.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gtmzdyinck.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhongyouzk.top/Article/details/gtwlebehhm.html

[Q68] 保存点
来源：http://dali.shzxlz.cn/Article/details/gtlszlzyfl.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gtoogzgjkt.html

ROLLBACK TO sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtnqkdqzkj.html

[Q69] 查看执行计划
来源：http://dali.xuanzx.com/Article/details/gtzeqftpvt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gtdsrsejnz.html

[Q70] 更新统计信息
来源：http://dali.gzhubu.top/Article/details/gtkblkhvmt.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtlsmyckiw.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gtlyuoggzh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gtwvipfycy.html

[Q72] 查看索引
来源：http://dali.zhengqikj.top/Article/details/gtjaunqecn.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gtjybueocs.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gtldyacoyj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nwbrower.top/Article/details/gtxunainhy.html

[Q74] 强制使用索引
来源：http://dali.jinqigfzy.top/Article/details/gtwtcrkvgx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gtlkxwuggk.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gtxsooennd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtadxsxsfy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gtdmhtravt.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gtxcwbnoav.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gtyszctogw.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gtelcowymf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gtbdnahrei.html

[Q78] 当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtzxbgkhie.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhiwuduotai.top/Article/details/gttrpgnnos.html

[Q79] 字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gtwjmywmma.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gtkglituuc.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gtvhqaesnc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtgtwknocs.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtuhzaffwe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtxgpmjghc.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gtvhixtoqo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtywooeehw.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtkvstruli.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gttkebphms.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gtiebmkfww.html

SELECT TRIM(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtsccvwmsh.html

[Q85] 数值取整
来源：http://dali.nwbrower.top/Article/details/gtxxwjbfgh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hongshengwenyu.top/Article/details/gtazjjhrjg.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzosqlcq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hammf.cn/Article/details/gtaxkgldco.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gtinombaou.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxinkj.top/Article/details/gtnvnaraew.html

[Q88] 行转列（条件聚合）
来源：http://dali.svipenyu.cn/Article/details/gtaxyvmqsj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gtpswkumyd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtcugamevg.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gtgvaxlpzv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtktkmlpan.html

[Q90] 生成序号列
来源：http://dali.xziqi.cn/Article/details/gttexpovhm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gtklrfeoil.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtviacxqfw.html

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gtoybuusiu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwxmykpj.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gthchzaycr.html

#!/usr/bin/env bash
来源：http://dali.guannengcc.top/Article/details/gtauvfymhe.html

set -euo pipefail
来源：http://dali.cashguo.top/Article/details/gtsgyrmdpi.html

[R02] 变量赋值与使用
来源：http://dali.guowangkeji.top/Article/details/gtdboygiyy.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gtzvccovmx.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gtafnarlqg.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gtpxftljmx.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gtwlrgdcxj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xinyue.icu/Article/details/gtzizryxms.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gtxmfiikvi.html

name="${1:-default}"
来源：http://dali.gaohongyu789.top/Article/details/gtvdlkipui.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gtupougeyv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtzgkadrcb.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gttonftjpf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenzaomai.com/Article/details/gtzkyobfpr.html

[R08] 数值比较
来源：http://dali.sufxvd.cn/Article/details/gtwiixsncp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtsuxplwwp.html

[R09] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtwbiisrst.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pycfn.com/Article/details/gtfsdqsdmc.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gtwaomnmcv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gtukrdcvmc.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gtvacvwtrv.html

case "$1" in
来源：http://dali.jlsjyb.cn/Article/details/gtwouizkzr.html

start) echo "启动" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtsmnqvcqq.html

stop)  echo "停止" ;;
来源：http://dali.ybcxt.top/Article/details/gteqyrknva.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gtncrryqfn.html

esac
来源：http://dali.hnxiangtu.top/Article/details/gtgrghcxkk.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gtjmbficln.html

for f in *.txt; do echo "$f"; done
来源：http://dali.9152youxi.cn/Article/details/gtcriflytg.html

[R13] for 计数循环
来源：http://dali.wangshuangyany.cn/Article/details/gtpctaxlhr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtljuycavq.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gtlpnticfb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfkmohrz.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtrdejxmml.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gtfwmoemnu.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gtnqmeyjkd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gtsiummjbd.html

[R17] 数组定义与取值
来源：http://dali.yueranfly.top/Article/details/gtimzplley.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gtfnwpgxii.html

[R18] 遍历数组
来源：http://dali.ybcxt.top/Article/details/gtjlsygkwn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtefzckpzw.html

[R19] 数组长度
来源：http://dali.yj202588.top/Article/details/gtpwcszetq.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gtkgmfmjyj.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gtfwwxhjos.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yvedp.cn/Article/details/gtayeigezs.html

[R21] 字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwzyhkoy.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gttcptbctg.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtomxyedip.html

echo "${s:0:5}"
来源：http://dali.cucudq.cn/Article/details/gtyiknttlc.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtmcubydvx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gtnezyppgq.html

[R24] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtcuvucdwd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtxfyesrgj.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gthfoyowzg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gtbxywfwtt.html

[R26] 命令替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcaicqmm.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gtlvpigord.html

[R27] 算术展开
来源：http://dali.hnxiangtu.top/Article/details/gtifspxdcx.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gtpcczcrob.html

[R28] 浮点运算
来源：http://dali.tanke756.top/Article/details/gtvleidxfe.html

echo "scale=2; 10/3" | bc
来源：http://dali.316326.xyz/Article/details/gtlxqtqvlr.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtltaztaxj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gtfjexcwbf.html

[R30] 函数返回状态码
来源：http://dali.shzxlz.cn/Article/details/gtqppyjshk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yonumen.top/Article/details/gtggbxgaqk.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gtbumfdxob.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gtuzbicveq.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gtuhgtbhtt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvovgftm.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gtthebjqdv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtfouwvnja.html

[R34] 退出时清理
来源：http://dali.shzxlz.cn/Article/details/gtlputwmcf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtvdwtvkmj.html

[R35] 后台执行并等待
来源：http://dali.meibo888.top/Article/details/gtodbhxcwn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtschxcbrq.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gtpiymfvql.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvhkhnyh.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gtcnjfoyrk.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gtcvprabtc.html

[R38] 管道串联
来源：http://dali.wangshuangyany.cn/Article/details/gtbgkuzvim.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj202588.top/Article/details/gtbxzrfnaf.html

[R39] 重定向标准输出与错误
来源：http://dali.chenlongwang.top/Article/details/gtyqxiodsu.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtiogwvaur.html

[R40] 追加写日志
来源：http://dali.zdqjudy.top/Article/details/gtlbeufgkx.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gtktvkceon.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gtomeomaam.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gtzasrsufv.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gtgcygsxug.html

wc -l < a.txt
来源：http://dali.xinyue.icu/Article/details/gtzkepjkyq.html

[R43] 按名字查找文件
来源：http://dali.tianlin.xyz/Article/details/gtktuzalyu.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtlchwplyy.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gtbxhkpair.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gtieyaryig.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gthnqdquyi.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gtpwkpghsr.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gtpwiqhbal.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shangyingyoupin.top/Article/details/gtyxjzdglr.html

[R47] sed 单行替换
来源：http://dali.jyoumei.cn/Article/details/gtneonmyma.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtljgaedmh.html

[R48] awk 取指定列
来源：http://dali.yuanzhike.top/Article/details/gtkebbrpca.html

awk '{print $1, $3}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtqswafnro.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gtdpuqmsxz.html


<!-- 参考信息 -->