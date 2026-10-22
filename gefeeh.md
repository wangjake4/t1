代发 wailian999

);
来源：http://dali.zhixingplan.top/Article/details/gtczxaymnc.html

[Q03] 增加列
来源：http://dali.yj20258.top/Article/details/gtyzxkwumy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxethwiv.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gtunznjgkq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cqqwz.cn/Article/details/gtlpjaveal.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gtslybizln.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ybcxt.top/Article/details/gtqbpymqqw.html

[Q06] 删除列
来源：http://dali.jinghuilouyu.cn/Article/details/gtxauvpoua.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauemmksk.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gthjiqblan.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cheryme.top/Article/details/gtjhzuaums.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gtdlbvdfqo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtfgtvrxjj.html

[Q09] 创建唯一索引
来源：http://dali.hfpthk.cn/Article/details/gtzvxcxodk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtjikjecrk.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyqgddpn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtvgogcfdi.html

[Q11] 一次插入多行
来源：http://dali.andypj.xyz/Article/details/gtlrcajvrd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gtwrmxykqa.html

[Q12] 插入后取自增 ID
来源：http://dali.tian-w.cn/Article/details/gtvsyylpfs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zdqjudy.top/Article/details/gtvqqcrowi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gtriiseuyk.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gtapaabbgb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gtaitqjlzo.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgfzy.top/Article/details/gtntpxamba.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cashguo.top/Article/details/gtadjfitqy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gtumlkzhqg.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gtawlnbdyy.html

SELECT * FROM users;
来源：http://dali.sxryk.cn/Article/details/gtspvmssje.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gtzxwmmgzl.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtwsqiapiw.html

[Q17] 条件查询
来源：http://dali.9152youxi.cn/Article/details/gtkpihgijo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.mhx1999.top/Article/details/gtyhlbphec.html

[Q18] 模糊匹配
来源：http://dali.sysykeji.top/Article/details/gtmvjxsebi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtodbhec.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gtqnfednrv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gtacbbrtqj.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gthnnwwrkl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigufen.top/Article/details/gtlvbwvgmz.html

[Q21] 空值判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbqrmrbp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gtylxakdou.html

[Q22] 排序
来源：http://dali.aizwys.cn/Article/details/gtmxwzafdr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.svipenyu.cn/Article/details/gtfutapzwk.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gtwvsmvyze.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yanxiufei.cn/Article/details/gtbwiaxpqx.html

[Q24] 去重
来源：http://dali.chenlongwang.top/Article/details/gtfbdcnftn.html

SELECT DISTINCT city FROM users;
来源：http://dali.nwbrower.top/Article/details/gtxhitkqek.html

[Q25] 只取前 N 条
来源：http://dali.nanxinkj.top/Article/details/gtpehkvygh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangshuangyany.cn/Article/details/gtdlmtlrob.html

[Q26] 计数
来源：http://dali.yongpay.top/Article/details/gtzorqnteb.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gtifudhmzh.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gtddmaxbbv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtrfeccfby.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gtpcnfwrnn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtxbopsxei.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gtianudiml.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtriqklcwm.html

[Q30] 分组统计
来源：http://dali.shangyingyoupin.top/Article/details/gtofklkdeu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtvzuhtxou.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtnqvreryu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gtgrjcwzrh.html

[Q32] 分组拼接字符串
来源：http://dali.pycfn.com/Article/details/gtmggjckde.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtunjloivx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnqzz.top/Article/details/gtxeyudqaa.html

[Q33] 多列分组
来源：http://dali.hywenlv.cn/Article/details/gtyoqofcgi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shuidangran.top/Article/details/gttozajfdf.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gtkiwnyqpu.html

SELECT * FROM (
来源：http://dali.cheryme.top/Article/details/gtxijcsrqh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenzaomai.com/Article/details/gtvtimepnf.html

) t WHERE rn = 1;
来源：http://dali.jinqigfzy.top/Article/details/gteyxdxunn.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gtwvdgrras.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtwnwoiyfo.html

[Q36] 左连接
来源：http://dali.chenjidiqi.icu/Article/details/gtjoxscdyp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtxunpecwy.html

[Q37] 右连接
来源：http://dali.gotoacloud.top/Article/details/gthkvdwsyq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gtevnmvtja.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gtwdhykjqf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.meibo888.top/Article/details/gtrtsbwjca.html

[Q39] 自连接（查上下级）
来源：http://dali.yvedp.cn/Article/details/gtzhtctdas.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gthjsopbxc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sweek.top/Article/details/gtlmppakns.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtqcjagkgj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yanxiufei.cn/Article/details/gtcyeftzhd.html

[Q41] 多表连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjtkyeqm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gtbtyplyli.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbvritoo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gtyxbyohmq.html

[Q42] 连接条件附加过滤
来源：http://dali.ivvv.top/Article/details/gtagrztfwi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gtvfcpkwtc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzkndotm.html

[Q43] 标量子查询
来源：http://dali.gzhubu.top/Article/details/gtqdqnwjdn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.meibo888.top/Article/details/gtvbetbric.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gtcvfaomhz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gtaacqisle.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gtwkxwitwc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidljlesu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaswpirtp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gtjiglbqup.html

[Q47] 与平均值比较
来源：http://dali.iojbl.cn/Article/details/gtqqxitsks.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdopfazgk.html

[Q48] CTE 公用表表达式
来源：http://dali.fzhhl.top/Article/details/gtxleveefs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gtazlpefoj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gtxvdsymri.html

[Q49] 更新单行
来源：http://dali.hammf.cn/Article/details/gtvxgrbrrn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtuopyeyhj.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gtmurnucpt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtcmdbhznz.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gthjeltaqe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gtkgbhngwp.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gtzukzckko.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtdzjxeimy.html

[Q53] 按条件删除
来源：http://dali.iojbl.cn/Article/details/gttjhhxemm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gtanegytrn.html

[Q54] 清空表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcltlexkc.html

TRUNCATE TABLE logs;
来源：http://dali.aizwys.cn/Article/details/gtogdxzlwb.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gtmwywuztj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtmsapphrl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtkzvlvpdj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtwymppdis.html

[Q57] 行号
来源：http://dali.kuanghao11.cn/Article/details/gtexgshtbo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gtkywhhfbp.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtepdhyxfc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtanqaswmk.html

[Q59] 分组内累计
来源：http://dali.yuxming.cn/Article/details/gteobzthfh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtsuwcrswf.html

[Q60] 取上一行 / 下一行
来源：http://dali.xylfe.cn/Article/details/gtszvvclfr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hammf.cn/Article/details/gtaatucnah.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gttwwtuhbf.html

[Q61] 移动平均
来源：http://dali.yj202588.top/Article/details/gtpcskcycf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrescsbcd.html

[Q62] 分组占比
来源：http://dali.xuetiantiany.cn/Article/details/gtahrycpsw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gthtodksht.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gtdexjgebq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gtmvfylvov.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gtgerclhnq.html

COMMIT;
来源：http://dali.yongpay.top/Article/details/gtzimyomaz.html

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gtuhueoieo.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gtanqllntt.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbivflmm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.smart0.xyz/Article/details/gtxggblhpo.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gtolofzhkx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jyoumei.cn/Article/details/gtyrjxxwqy.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gtxkdsexzs.html

SAVEPOINT sp1;
来源：http://dali.xinyue.icu/Article/details/gtqthhjqgd.html

ROLLBACK TO sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtdosiagmn.html

[Q69] 查看执行计划
来源：http://dali.yuanzhike.top/Article/details/gtkkgnwsbu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gtimkxjdpy.html

[Q70] 更新统计信息
来源：http://dali.ppjwa.cn/Article/details/gtloujkxza.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gtrwullvue.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gtnbsqzvyc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gtyvncrapc.html

[Q72] 查看索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjbewvhl.html

SHOW INDEX FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtcearajac.html

[Q73] 查看表状态
来源：http://dali.hammf.cn/Article/details/gtpzppgzzd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yonumen.top/Article/details/gtipisruws.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gtubntjssv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sysykeji.top/Article/details/gtechmugyo.html

[Q75] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtfljzmlkt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtgdtmkkpj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jlsjyb.cn/Article/details/gttnytxbge.html

[Q76] 按天统计
来源：http://dali.cdnleiting.top/Article/details/gtlerrzeda.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtarpvldul.html

[Q77] 时间加减
来源：http://dali.jyoumei.cn/Article/details/gtngvqifhj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgfzy.top/Article/details/gtfbnkjphs.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gtwoztjnyp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gtsluduzlf.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtgscnusqj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.316326.xyz/Article/details/gtjtilcsbl.html

[Q80] 字符串截取
来源：http://dali.havefunace.top/Article/details/gtumrvvqij.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtagkavetu.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtxohakcah.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xinyue.icu/Article/details/gtbzeyydit.html

[Q82] 字符长度与字节长度
来源：http://dali.xziqi.cn/Article/details/gtpkrwboug.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtfcgrmccb.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtdljirwbs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtpbrtfvly.html

[Q84] 去除首尾空格
来源：http://dali.zhixingplan.top/Article/details/gtryiyyppy.html

SELECT TRIM(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtgcozkkzz.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gtoihysnhp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gtyxybhech.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gtztzygkck.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnqzz.top/Article/details/gtljtvzvyp.html

[Q87] JSON 字段做条件
来源：http://dali.yangfankeji.com/Article/details/gtojcvtxjr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gtxuqxzjlu.html

[Q88] 行转列（条件聚合）
来源：http://dali.dianchejie.cn/Article/details/gtbirmozdp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gogol.net.cn/Article/details/gthguoitjs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gtuuvysfxb.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gtybktdibo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gtuasgbodk.html

[Q90] 生成序号列
来源：http://dali.feifeiyinyue.top/Article/details/gtsvzglqqn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fzhhl.top/Article/details/gtphdfluwm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcofwszrm.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gtqeitwqrr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtlnjvwszy.html

[R01] shebang 与严格模式
来源：http://dali.c1oappe.top/Article/details/gtbqoglhhs.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gtvhkgakie.html

set -euo pipefail
来源：http://dali.yvedp.cn/Article/details/gtrgakgiyp.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtedjzdhrb.html

name="Tom"; echo "$name"
来源：http://dali.jqgfzy.top/Article/details/gtmpnnozfy.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gtacfmhmzu.html

readonly PI=3.14
来源：http://dali.sufxvd.cn/Article/details/gthqzmnsur.html

[R04] 位置参数
来源：http://dali.ydzc1.top/Article/details/gtdtfjkvdw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhseepjw.html

[R05] 参数默认值
来源：http://dali.zycfv.cn/Article/details/gtkestophu.html

name="${1:-default}"
来源：http://dali.dashuyun.cn/Article/details/gtczqdrhqx.html

[R06] 判断命令是否存在
来源：http://dali.nwbrower.top/Article/details/gtasdhvozc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtofjrovko.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gtoilikxox.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gtueormxtn.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gteygxcxwj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cqqwz.cn/Article/details/gtqypquhcm.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gtxljmsffb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gttlqqayez.html

[R10] 正则匹配
来源：http://dali.kuanghao11.cn/Article/details/gtmcucxlie.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sxryk.cn/Article/details/gtsufmvefr.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gtazybgwin.html

case "$1" in
来源：http://dali.xinyue.icu/Article/details/gtuewuanbh.html

start) echo "启动" ;;
来源：http://dali.sysykeji.top/Article/details/gtboazqrdy.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gtufqwyzot.html

*)     echo "未知命令" ;;
来源：http://dali.sysykeji.top/Article/details/gtsmebtglk.html

esac
来源：http://dali.cashguo.top/Article/details/gtwqdnbmkn.html

[R12] for 遍历文件
来源：http://dali.jinqigfzy.top/Article/details/gtymwtudkv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtvmjdbqvd.html

[R13] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gtrnovvkgj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtmgdpxqaa.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gtzwyqjytv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtvrjgiphj.html

[R15] while 逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtgqhdwrfj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258888.top/Article/details/gtldzmimks.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gtzzcpyyop.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gtneltcgfo.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gtqxmywdgm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ivvv.top/Article/details/gtephzrpqm.html

[R18] 遍历数组
来源：http://dali.jyoumei.cn/Article/details/gtsvvtjuyt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gtfnxirdao.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gtnptvhxsi.html

echo "${#arr[@]}"
来源：http://dali.quarkkingdee.top/Article/details/gtlwfbchii.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gtmcnvulsj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gtamyfgfgt.html

[R21] 字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuycmuka.html

echo "${#s}"
来源：http://dali.yvedp.cn/Article/details/gtyiiorlxa.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gtzkomsbpl.html

echo "${s:0:5}"
来源：http://dali.xuanzx.com/Article/details/gtohellnpq.html

[R23] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gtgdvjhoyy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gtqzngtomm.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtvciussot.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtjocqiacb.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gtrqphuqhz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daxiang520.top/Article/details/gtdmuproik.html

[R26] 命令替换
来源：http://dali.smart0.xyz/Article/details/gtafikkpth.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcywbcxkc.html

[R27] 算术展开
来源：http://dali.kuanghao11.cn/Article/details/gtkolofvqg.html

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gtrzwfsicd.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gtkntlpfek.html

echo "scale=2; 10/3" | bc
来源：http://dali.kuanghao11.cn/Article/details/gtbllihuah.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gtsuixdyaw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtkcqmoskg.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtcttmfhdr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gtnaxiezoc.html

[R31] 局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtfyblhvzg.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gtrrcozgjs.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gtyhkcfwol.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtslthmotr.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gtinwlhghg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.kuanghao11.cn/Article/details/gtiepzbcbx.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gtjwwgmrgj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gtnzfeeuzp.html

[R35] 后台执行并等待
来源：http://dali.yanxiufei.cn/Article/details/gtihihjvro.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xinyue.icu/Article/details/gtdfdkgvba.html

[R36] 并发执行多个任务
来源：http://dali.yanxiufei.cn/Article/details/gtpzvcobfa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gtshuindbt.html

[R37] 把输出赋给变量
来源：http://dali.xuetiantiany.cn/Article/details/gtcfrvxkeu.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gtrjwgyruu.html

[R38] 管道串联
来源：http://dali.meibo888.top/Article/details/gthimcnrzo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuanzx.com/Article/details/gtrksrazgt.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gtctvjufme.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gttoxispie.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gtxtjltjbe.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gtsvtudjeh.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gtyffqocik.html

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtsfedhcuy.html

[R42] 输入重定向
来源：http://dali.birdmap.top/Article/details/gtkwqsxyey.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gtzsfvwjps.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gtwwmonbnm.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gtlzacikso.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gtsjqdtfef.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtjiwhevik.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gtldvdaqbb.html

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gtdevysfmo.html

[R46] 递归替换文件内容
来源：http://dali.cheryme.top/Article/details/gtbqipxbcp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gtrsctwhqc.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gtjwusbzbh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtmtyyqeip.html

[R48] awk 取指定列
来源：http://dali.xuetiantiany.cn/Article/details/gtlkghgmso.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtglzemwrj.html

[R49] awk 带条件
来源：http://dali.zhixingplan.top/Article/details/gtfcbkvckl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigfzy.top/Article/details/gtkopdgyxz.html

[R50] awk 求和
来源：http://dali.tian-w.cn/Article/details/gtfieareom.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtkemiskwx.html

[R51] 排序去重取前几
来源：http://dali.hfpthk.cn/Article/details/gthahidtnx.html


<!-- 参考信息 -->