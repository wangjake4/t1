代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hywenlv.cn/Article/details/gtnpixmpby.html

[Q05] 重命名列
来源：http://dali.nwbrower.top/Article/details/gtkmhjohdv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258888.top/Article/details/gtylumtnti.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gtgesrxsxk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fengsongda.top/Article/details/gtfgdevkwt.html

[Q07] 删除表
来源：http://dali.cdnleiting.top/Article/details/gtsgrkqhrc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtyhfjktbe.html

[Q08] 创建普通索引
来源：http://dali.jinqigfzy.top/Article/details/gtsxtnbrnp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gtylazhicy.html

[Q09] 创建唯一索引
来源：http://dali.bjfxy.top/Article/details/gtkrutzxlu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtyxhuorgy.html

[Q10] 插入单行
来源：http://dali.hysaishi.cn/Article/details/gtyjrqyptu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gtxfyfsgnv.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gtigkzkgcu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjlxjgpp.html

[Q12] 插入后取自增 ID
来源：http://dali.havefunace.top/Article/details/gtyepezqla.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.316326.xyz/Article/details/gtaljfidqs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258888.top/Article/details/gtkscrlnqy.html

[Q13] 忽略重复插入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavjvpmcg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tianlin.xyz/Article/details/gthmlynfpv.html

[Q14] 存在则更新（upsert）
来源：http://dali.nwbrower.top/Article/details/gtodqjmfmf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yongpay.top/Article/details/gtlglfivio.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gtjkdvtemz.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gtuckvbqlz.html

SELECT * FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gteipjbvse.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gtcruwmibu.html

SELECT id, name FROM users;
来源：http://dali.xuanzx.com/Article/details/gtmjxivtgb.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gttvvnhyji.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gtliuasudo.html

[Q18] 模糊匹配
来源：http://dali.zhixingplan.top/Article/details/gtbqjwblcg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.snrcjt.cn/Article/details/gtpgwbjuzg.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gtiurjutkc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gtzycukkys.html

[Q20] IN 列表
来源：http://dali.daxiang520.top/Article/details/gtnlwkcrgj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.316326.xyz/Article/details/gtjktjtvtt.html

[Q21] 空值判断
来源：http://dali.yuanzhike.top/Article/details/gtkdtslqzv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jyoumei.cn/Article/details/gtqniwmhik.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gtzlexohkf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jyoumei.cn/Article/details/gtrtjlakqd.html

[Q23] 分页
来源：http://dali.ybcxt.top/Article/details/gtcpnepwks.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.snrcjt.cn/Article/details/gtmmuvpdqw.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gttmdtzsip.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gteypkxpbc.html

[Q25] 只取前 N 条
来源：http://dali.shangyingyoupin.top/Article/details/gtaewiddga.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gtgtkzglor.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gtfhayorup.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtoajpqcut.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtkwamvatj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cucudq.cn/Article/details/gtzfecnlal.html

[Q28] 求和与平均
来源：http://dali.jiagoushi.top/Article/details/gtyetihpkg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtrrecasam.html

[Q29] 最大最小值
来源：http://dali.hysaishi.cn/Article/details/gtmixssuyl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmayvwcbe.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtzsjbokey.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtyfrryeuh.html

[Q31] 分组后过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtfaaejhav.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cucudq.cn/Article/details/gtterfvzwu.html

[Q32] 分组拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtwafejroa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtmqxopysg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yvedp.cn/Article/details/gtxcpvzprz.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gtvgnkjipn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gthwlootqs.html

[Q34] 每组取第一条
来源：http://dali.gotoacloud.top/Article/details/gtszsibdxv.html

SELECT * FROM (
来源：http://dali.zhoulong.xyz/Article/details/gtzezfpgkq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gtmmrwmmwf.html

) t WHERE rn = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwboqvsra.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtslvzjdqy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtlekmspif.html

[Q36] 左连接
来源：http://dali.jlsjyb.cn/Article/details/gtmgkoemtp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtezmogobk.html

[Q37] 右连接
来源：http://dali.yuanzhike.top/Article/details/gtuxpmjugz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258888.top/Article/details/gtkloreyoz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.quarkkingdee.top/Article/details/gtkqsaiwuc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrkmqkzq.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gtiivatlho.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shuidangran.top/Article/details/gtjwlxufjr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xylfe.cn/Article/details/gtxtvcueju.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gtrtgwvezs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.iojbl.cn/Article/details/gtwbyjcvhn.html

[Q41] 多表连接
来源：http://dali.cheryme.top/Article/details/gtgyalgpks.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hysaishi.cn/Article/details/gthzpdjuds.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gthczthfxs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjojoacmr.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtbyuoblbw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtzhikaewc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtazwzwwkw.html

[Q43] 标量子查询
来源：http://dali.ybcxt.top/Article/details/gtwmxnbajy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtxwfvcttt.html

[Q44] IN 子查询
来源：http://dali.sufxvd.cn/Article/details/gtwkjjupre.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gtcrhpfumd.html

[Q45] EXISTS 判断存在
来源：http://dali.jianghu66.top/Article/details/gtasdpwmiq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtxcjbwydt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gtujsenxuf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtjvrehanl.html

[Q47] 与平均值比较
来源：http://dali.cucudq.cn/Article/details/gtbhkzudhe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gtvtusjxsd.html

[Q48] CTE 公用表表达式
来源：http://dali.ivvv.top/Article/details/gthpgksenx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hywenlv.cn/Article/details/gtcdqbnfpg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhixingplan.top/Article/details/gtrgkxxksc.html

[Q49] 更新单行
来源：http://dali.xinyue.icu/Article/details/gtbmwxsyub.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtnfczaoag.html

[Q50] 批量更新
来源：http://dali.daria6918.cn/Article/details/gtgzhknlqq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtayqxmjhc.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gtvylggdoy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guannengcc.top/Article/details/gtreeeyixr.html

[Q52] 删除指定行
来源：http://dali.gotoacloud.top/Article/details/gtolgqaxre.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtytctifna.html

[Q53] 按条件删除
来源：http://dali.cqqwz.cn/Article/details/gtlziggfjt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gtnnxhtmic.html

[Q54] 清空表
来源：http://dali.cashguo.top/Article/details/gtvlokkknn.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gteozdbgya.html

[Q55] 排名（并列占位）
来源：http://dali.chenlongwang.top/Article/details/gtjjslgtba.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtfzmwqack.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fzhhl.top/Article/details/gthetoscqo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtrrkyxfkg.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gterhmhrgx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gtctvtyjrt.html

[Q58] 累计求和
来源：http://dali.nwbrower.top/Article/details/gtowirphey.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtqyltozgb.html

[Q59] 分组内累计
来源：http://dali.fzhhl.top/Article/details/gtkhivqzkc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtxvxdesmm.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuanzhike.top/Article/details/gtqfrgtbis.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aizwys.cn/Article/details/gthewejfhb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtzpayzbiq.html

[Q61] 移动平均
来源：http://dali.pengpengdd.cyou/Article/details/gtcdkjzrvf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtvzpjsmae.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gtyszkkhrm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtigetaglk.html

[Q63] 开启事务
来源：http://dali.jyoumei.cn/Article/details/gthgzbdkuc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtrgaavlgu.html

[Q64] 提交事务
来源：http://dali.vqdsnc.cn/Article/details/gtzjitowmo.html

COMMIT;
来源：http://dali.hywenlv.cn/Article/details/gtopbxebib.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gtplbtqhvv.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gtewtxbjok.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhtyklop.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yvedp.cn/Article/details/gtfuenuvkh.html

[Q67] 设置隔离级别
来源：http://dali.aizwys.cn/Article/details/gtxtsauryx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yongpay.top/Article/details/gtxdexoflf.html

[Q68] 保存点
来源：http://dali.cucudq.cn/Article/details/gtterhwwqh.html

SAVEPOINT sp1;
来源：http://dali.fzhhl.top/Article/details/gteuwlnbey.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gtcijogksb.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gteilowvsr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtullwobkj.html

[Q70] 更新统计信息
来源：http://dali.tianlin.xyz/Article/details/gtbomtwexb.html

ANALYZE TABLE users;
来源：http://dali.yuanzhike.top/Article/details/gtkzzwvahx.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gtkwgjomug.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gtdctmfxso.html

[Q72] 查看索引
来源：http://dali.yuxming.cn/Article/details/gtdheyhxfe.html

SHOW INDEX FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtqyjanbgm.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gtmjcravdj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ybcxt.top/Article/details/gtifehshlz.html

[Q74] 强制使用索引
来源：http://dali.xziqi.cn/Article/details/gtiqqexphu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gaohongyu789.top/Article/details/gtioqvvlxz.html

[Q75] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtpjzoijyx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgviesdul.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jyoumei.cn/Article/details/gthsgbtccv.html

[Q76] 按天统计
来源：http://dali.yangfankeji.com/Article/details/gthwptyeeo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenlongwang.top/Article/details/gtsflzyqxh.html

[Q77] 时间加减
来源：http://dali.hongshengwenyu.top/Article/details/gtodzbitzz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gtblcuiuug.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gtyzllaeeo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gtxeflfmct.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtmgiapzlg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gtaoiwvvrk.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gtgguklalq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gthqeqbdaq.html

[Q81] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdbmmidl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.316326.xyz/Article/details/gtsecfvnnx.html

[Q82] 字符长度与字节长度
来源：http://dali.andypj.xyz/Article/details/gtusvcfozn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtaegfpmnd.html

[Q83] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtwggazzkx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtpvquzzoz.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gtoiosqjtu.html

SELECT TRIM(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtebxefgou.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtndgehkkp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gtbeuwmgeu.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258888.top/Article/details/gttqbjdcir.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gttxiqgifr.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gtojaqbupb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sysykeji.top/Article/details/gticjraosq.html

[Q88] 行转列（条件聚合）
来源：http://dali.aizwys.cn/Article/details/gtjohriuet.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hfpthk.cn/Article/details/gtwuonozgk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.andypj.xyz/Article/details/gtwecmdmoi.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gtejxxrfdg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtjtwihzuq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gtwcxldpkq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gtpepbhidu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtiwdptumn.html

R. Bash 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxmvhyds.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqhaqdywe.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gtbydlyflg.html

#!/usr/bin/env bash
来源：http://dali.hysaishi.cn/Article/details/gtmpuwykzw.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gttqhzeogm.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gtaqeyivbw.html

name="Tom"; echo "$name"
来源：http://dali.yj20258.top/Article/details/gtecsgvqlm.html

[R03] 只读变量
来源：http://dali.daria6918.cn/Article/details/gtwpnsxzpi.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gtvphbfzyb.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gtokhaccmx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ppjwa.cn/Article/details/gtvwjsyftt.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gteleyijyk.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gtftpbysix.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gtyaustvzp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlibpzljx.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gtalwkhrvo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtzdynbjuq.html

[R08] 数值比较
来源：http://dali.jqgufenzy.top/Article/details/gtotafcyts.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gtayubgeuf.html

[R09] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gtmohunnmj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gtxlclcjkl.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gtijwukdzk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtccjuwevj.html

[R11] case 多分支
来源：http://dali.mhx1999.top/Article/details/gtdchicgue.html

case "$1" in
来源：http://dali.yj202588.top/Article/details/gtfohgfisb.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gtvwuvnzto.html

stop)  echo "停止" ;;
来源：http://dali.xuanzx.com/Article/details/gtytxqxmec.html

*)     echo "未知命令" ;;
来源：http://dali.yvedp.cn/Article/details/gtdmewojgc.html

esac
来源：http://dali.aizwys.cn/Article/details/gtkmtjippe.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gtcsxfwhsl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.snrcjt.cn/Article/details/gtnuchzdmb.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtvnektmkm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtzeqiaaim.html

[R14] C 风格 for
来源：http://dali.fzhhl.top/Article/details/gthkewphue.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtsrnfuzyi.html

[R15] while 逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtlaradscf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zdqjudy.top/Article/details/gtfbtzfcxz.html

[R16] until 等待条件
来源：http://dali.tian-w.cn/Article/details/gtfpjstvbj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtxebfssvs.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gtvsqleqmf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gtmkggewdg.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gtspoimivp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gtvfhybrlx.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtugnbehgh.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gtqgujstvn.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gteuszlbrp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gtadsyflyn.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gtraxedclt.html

echo "${#s}"
来源：http://dali.feifeiyinyue.top/Article/details/gtmetghjnd.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gtuaegcrzt.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gtcgynupvx.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtfefgqolw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnxiangtu.top/Article/details/gtxfvejwyj.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtxhdwlbje.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tian-w.cn/Article/details/gtdivhexwq.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gtlxmveqfi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gtlqeknkfm.html

[R26] 命令替换
来源：http://dali.snrcjt.cn/Article/details/gtquusvmom.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gtzzjgzqut.html

[R27] 算术展开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunubfpbm.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gtweumqmhf.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gtftpnswnl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhixingplan.top/Article/details/gtgopuvkeo.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gtbswkxykt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjpyiopy.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gtlzdxyimx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.mhx1999.top/Article/details/gtffzffadp.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gtqobkfkzq.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gtpmgekhym.html

[R32] 参数个数校验
来源：http://dali.0kj1m.cn/Article/details/gttfxwnmwc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgycxzdqj.html

[R33] 捕获错误并提示行号
来源：http://dali.yvedp.cn/Article/details/gtsrndrdyl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gtfflnhtbf.html

[R34] 退出时清理
来源：http://dali.kuanghao11.cn/Article/details/gtsuvyhytb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtynsoszng.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gtxjxdggge.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gttytsemnt.html

[R36] 并发执行多个任务
来源：http://dali.fzhhl.top/Article/details/gthnsawxqf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gtkxfrutcz.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gtxcdumtas.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gtxdmldvuo.html

[R38] 管道串联
来源：http://dali.kuanghao11.cn/Article/details/gtncftxjif.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gtnvfrhdcr.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gtjlodsnyz.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtyfaqzphg.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gtmpweuiua.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gtwmfdsaes.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gtibwtktnv.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtgalxrivz.html

[R42] 输入重定向
来源：http://dali.pengpengdd.cyou/Article/details/gtgculmuhr.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcesqloze.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gtzzwafqty.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gtngyndyye.html

[R44] 按修改时间查找
来源：http://dali.kuanghao11.cn/Article/details/gtfplhdwij.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gtmyghihlo.html

[R45] 批量删除
来源：http://dali.redwolf501.top/Article/details/gtjaegrqnj.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gtpkuowhrl.html

[R46] 递归替换文件内容
来源：http://dali.daria6918.cn/Article/details/gtdqwdkthw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpfhxjeb.html

[R47] sed 单行替换
来源：http://dali.gzhubu.top/Article/details/gtrnxwhmdu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gtvnrjqcfg.html

[R48] awk 取指定列
来源：http://dali.pengpengdd.cyou/Article/details/gtougpncsd.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtyjmolrzw.html

[R49] awk 带条件
来源：http://dali.xinyue.icu/Article/details/gtqpwrcwlc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gtnbskmreg.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gtudlonhgy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtkutbzuue.html

[R51] 排序去重取前几
来源：http://dali.snrcjt.cn/Article/details/gtcxopeokm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhixingplan.top/Article/details/gthdspiguk.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gtegavqaob.html

wc -l a.txt
来源：http://dali.gogol.net.cn/Article/details/gtoihnmroo.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gttnqfowuc.html


<!-- 参考信息 -->