代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gt2ltfdzxjc.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gt2supgiyyx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gt2kfyxyqnm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cguxsntf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sufxvd.cn/Article/details/gt2kegqkpde.html

C#:   if (x is null) {}
来源：http://dali.smart0.xyz/Article/details/gt2zrylqrir.html

[P07] 防抖与节流
来源：http://dali.gzhubu.top/Article/details/gt2akcosadi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigufen.top/Article/details/gt2ezkssygt.html

PHP:  // 手写时间戳比较
来源：http://dali.jiagoushi.top/Article/details/gt2hnajhxyr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gt2ppclgmte.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gt2byrxhxyh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.havefunace.top/Article/details/gt2rfykxifh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuxming.cn/Article/details/gt2kvzguhvn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gt2tavsnchi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shzxlz.cn/Article/details/gt2qxtnkfab.html

[P08] 处理浮点精度问题
来源：http://dali.daxiang520.top/Article/details/gt2rzodryra.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gt2wkpehagj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2kcijqzkd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenzaomai.com/Article/details/gt2vzyjjgjf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xfrkmzkl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gt2yriwdeuz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gt2hpdjnnjv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jlsjyb.cn/Article/details/gt2khctcdlm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhengqikj.top/Article/details/gt2jjvdljuq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2weteouzb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tanke756.top/Article/details/gt2vvjbjbez.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqhjevsf.html

[Q01] 创建表
来源：http://dali.hnxiangtu.top/Article/details/gt2awtdarbh.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gt2ilbdujmx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gt2zrylflqu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gt2quvsbjje.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pengpengdd.cyou/Article/details/gt2klwthmwr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gt2wptlobti.html

);
来源：http://dali.birdmap.top/Article/details/gt2ojkvhjxz.html

[Q02] 创建带外键的表
来源：http://dali.zhengqikj.top/Article/details/gt2haqaoyto.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gt2crniqiug.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gt2qvpcwcdn.html

user_id INT NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gt2nmimbvne.html

amount DECIMAL(10, 2),
来源：http://dali.nwbrower.top/Article/details/gt2fsdenymc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.quarkkingdee.top/Article/details/gt2bohelsty.html

);
来源：http://dali.svipenyu.cn/Article/details/gt2lngvutjd.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gt2mumfsvlt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ybcxt.top/Article/details/gt2khvlslju.html

[Q04] 修改列类型
来源：http://dali.jiagoushi.top/Article/details/gt2hxqginwv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shzxlz.cn/Article/details/gt2zrlmkyul.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gt2uwjaclok.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.birdmap.top/Article/details/gt2lalfpzqm.html

[Q06] 删除列
来源：http://dali.hammf.cn/Article/details/gt2dsowywmd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.iojbl.cn/Article/details/gt2geocjwok.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gt2jmwyraqt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoectifh.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gt2alttpxwq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gt2dgjsmvzf.html

[Q09] 创建唯一索引
来源：http://dali.xylfe.cn/Article/details/gt2eonvukqd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gt2qdsiqcsm.html

[Q10] 插入单行
来源：http://dali.quarkkingdee.top/Article/details/gt2nwlrvqrn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yonumen.top/Article/details/gt2rjzysdwj.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gt2cggbynhp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.havefunace.top/Article/details/gt2lemlcpne.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gt2kuasqvsj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guowangkeji.top/Article/details/gt2ryvpniiw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xziqi.cn/Article/details/gt2jsnqwekk.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gt2qmfbeugy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gt2zvtgjdcs.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gt2fblhllus.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigfzy.top/Article/details/gt2ogrwwxfv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hysaishi.cn/Article/details/gt2kykkleqk.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gt2tcmjoydn.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kanqbfhu.html

[Q16] 查询指定列
来源：http://dali.chenzaomai.com/Article/details/gt2olhpdqzq.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2ukkyoecv.html

[Q17] 条件查询
来源：http://dali.bjfxy.top/Article/details/gt2lsxtyyuj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2jxgoetzx.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gt2euoyvaoo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.mhx1999.top/Article/details/gt2mnfnrosv.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gt2yaiigojw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhiwuduotai.top/Article/details/gt2cejmduxf.html

[Q20] IN 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmsvoafl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sweek.top/Article/details/gt2kpzggsbm.html

[Q21] 空值判断
来源：http://dali.shzxlz.cn/Article/details/gt2yjfpmehz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gt2glxkjwky.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gt2ynusuwdd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gotoacloud.top/Article/details/gt2kybehpci.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gt2sfakhjzp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gogol.net.cn/Article/details/gt2abqpdjvo.html

[Q24] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gt2awopexzr.html

SELECT DISTINCT city FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2qwrfzpui.html

[Q25] 只取前 N 条
来源：http://dali.dianchejie.cn/Article/details/gt2cvputctr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cucudq.cn/Article/details/gt2mkjdiibb.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gt2ppwwguvs.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2agwixvjc.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjzkgpkr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sweek.top/Article/details/gt2cgtdyfoo.html

[Q28] 求和与平均
来源：http://dali.yanxiufei.cn/Article/details/gt2ffdutppv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2bupihcit.html

[Q29] 最大最小值
来源：http://dali.aizwys.cn/Article/details/gt2nfmqabla.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2amylydpn.html

[Q30] 分组统计
来源：http://dali.shangyingyoupin.top/Article/details/gt2wbioibpg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ylxxiuxu.html

[Q31] 分组后过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vrywmhbl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ikykjsxm.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gt2gmgtqvqd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2kzrzkvmt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gt2pzsdjvtx.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gt2qozdrriq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gt2qfhgzayl.html

[Q34] 每组取第一条
来源：http://dali.zhongyouzk.top/Article/details/gt2syohthrg.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gt2lekkioth.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gt2mddnmlrx.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2vpvdckli.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gt2bufuyszk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gt2isxmvpoz.html

[Q36] 左连接
来源：http://dali.birdmap.top/Article/details/gt2fafushyo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gt2mfuaobvf.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gt2wlalrzdc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xziqi.cn/Article/details/gt2uhxsfukf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhongyouzk.top/Article/details/gt2tyceojag.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.havefunace.top/Article/details/gt2ngmebdlh.html

[Q39] 自连接（查上下级）
来源：http://dali.aizwys.cn/Article/details/gt2bcbcrvho.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cucudq.cn/Article/details/gt2ngxzsbvz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gt2euxspcoq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yonumen.top/Article/details/gt2jrapciyy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fzhhl.top/Article/details/gt2zztdromp.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gt2infmycng.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hywenlv.cn/Article/details/gt2xmdyxtjr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.birdmap.top/Article/details/gt2jbifctga.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhongyouzk.top/Article/details/gt2crwwmlmz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2aysvvaac.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aizwys.cn/Article/details/gt2zmgdiwme.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwuynsto.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogvsnike.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tianlin.xyz/Article/details/gt2fahrrgic.html

[Q44] IN 子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcqjedib.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gt2pqertdtz.html

[Q45] EXISTS 判断存在
来源：http://dali.redwolf501.top/Article/details/gt2rjplkfea.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gt2avhfzbjo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuxming.cn/Article/details/gt2bvbxrjlh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjqrqduw.html

[Q47] 与平均值比较
来源：http://dali.daxiang520.top/Article/details/gt2jzvmjyow.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gt2hoymeovv.html

[Q48] CTE 公用表表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrmcecto.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.quarkkingdee.top/Article/details/gt2qitzjilf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gt2nsfuwbgq.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gt2hcgviwfe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gt2glzwinle.html

[Q50] 批量更新
来源：http://dali.nanxinkj.top/Article/details/gt2nqztpeng.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gotoacloud.top/Article/details/gt2kazerrgy.html

[Q51] 用子查询更新
来源：http://dali.cheryme.top/Article/details/gt2jmmdxgrc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hammf.cn/Article/details/gt2adqsqjyl.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gt2enckjkty.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gt2kzuenbli.html

[Q53] 按条件删除
来源：http://dali.0kj1m.cn/Article/details/gt2ejwxrpwi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gt2nzobdsmp.html

[Q54] 清空表
来源：http://dali.yj202588.top/Article/details/gt2xwjlrfyx.html

TRUNCATE TABLE logs;
来源：http://dali.guannengcc.top/Article/details/gt2ocwdqppn.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gt2crkqtzyg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gt2yjsuzfcd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gt2xrzwphdl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cashguo.top/Article/details/gt2fcpersxb.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gt2fudoryic.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2amczliov.html

[Q58] 累计求和
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxgrzwom.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gt2jxnezrak.html

[Q59] 分组内累计
来源：http://dali.yvedp.cn/Article/details/gt2azuqnmdz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2uyctjiup.html

[Q60] 取上一行 / 下一行
来源：http://dali.guowangkeji.top/Article/details/gt2iqmzrwoi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gt2iqgzigvn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2fomrttvd.html

[Q61] 移动平均
来源：http://dali.ivvv.top/Article/details/gt2wbhaltbw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2prinxbcm.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gt2xbczlmxt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gt2prccjlcq.html

[Q63] 开启事务
来源：http://dali.hnqzz.top/Article/details/gt2vgxnngvh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gt2jcaihkvg.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gt2faoonnof.html

COMMIT;
来源：http://dali.yueranfly.top/Article/details/gt2mhicexim.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gt2bcjewibf.html

ROLLBACK;
来源：http://dali.nanxuanxn.top/Article/details/gt2kpqnotqf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2orcpqefb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sysykeji.top/Article/details/gt2cpgbrnos.html

[Q67] 设置隔离级别
来源：http://dali.gotoacloud.top/Article/details/gt2wowsbfkb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gt2pvmitajc.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gt2fisazbfg.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gt2echrhbfk.html

ROLLBACK TO sp1;
来源：http://dali.havefunace.top/Article/details/gt2gnyvqhfq.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gt2vzrufqsm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gt2ewiljred.html

[Q70] 更新统计信息
来源：http://dali.aibaodan.cn/Article/details/gt2cvfkpuot.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gt2obkfilae.html

[Q71] 查看建表语句
来源：http://dali.gaohongyu789.top/Article/details/gt2odkkemct.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gt2udfpgubr.html

[Q72] 查看索引
来源：http://dali.tanke756.top/Article/details/gt2yftvaecc.html

SHOW INDEX FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2kidkznic.html

[Q73] 查看表状态
来源：http://dali.gzhubu.top/Article/details/gt2mdyzgoyc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.iojbl.cn/Article/details/gt2ajhsyyqb.html

[Q74] 强制使用索引
来源：http://dali.guannengcc.top/Article/details/gt2xifhqbwd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.quarkkingdee.top/Article/details/gt2sykpgdwr.html

[Q75] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptlkfcam.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2jbiqqoki.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnlflxha.html

[Q76] 按天统计
来源：http://dali.mhx1999.top/Article/details/gt2ktyxyuci.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhoulong.xyz/Article/details/gt2icdxrecg.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gt2zagxnwta.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258888.top/Article/details/gt2rrapjlvn.html

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gt2llpveawc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jiagoushi.top/Article/details/gt2iccgkhlr.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gt2gojzmfzp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhoulong.xyz/Article/details/gt2sgmocizk.html

[Q80] 字符串截取
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlrgvhpf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2lsltiwfb.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gt2qhdcezhx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2qnkamzwq.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258888.top/Article/details/gt2phjjnrht.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2rmemekux.html

[Q83] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gt2zwxkhvbz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2quxnfzqk.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gt2avujawwn.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2wozvsygc.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gt2ftcnszht.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fplqqghi.html

[Q86] 读取 JSON 字段
来源：http://dali.kuanghao11.cn/Article/details/gt2zbvxefar.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sysykeji.top/Article/details/gt2yvfygxuh.html

[Q87] JSON 字段做条件
来源：http://dali.xuanzx.com/Article/details/gt2sryrrcwa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gt2hfjbmera.html

[Q88] 行转列（条件聚合）
来源：http://dali.0kj1m.cn/Article/details/gt2rguhmyox.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gt2cdbcugyh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2jsbpnmch.html

[Q89] 判断表是否存在
来源：http://dali.smart0.xyz/Article/details/gt2holhbowj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdufjpam.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2muuewfvt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gt2xtmfello.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ynegimso.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gt2hnthbpch.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2jmertaxj.html

[R01] shebang 与严格模式
来源：http://dali.smart0.xyz/Article/details/gt2jrwrudme.html

#!/usr/bin/env bash
来源：http://dali.ppjwa.cn/Article/details/gt2kseskeed.html

set -euo pipefail
来源：http://dali.cucudq.cn/Article/details/gt2oihhcvok.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gt2rybnuvsh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pstshufb.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gt2zcsaeiks.html

readonly PI=3.14
来源：http://dali.zdqjudy.top/Article/details/gt2daavgtrt.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gt2pmtqppfh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gt2ymvcbqjz.html

[R05] 参数默认值
来源：http://dali.vqdsnc.cn/Article/details/gt2bcylquou.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gt2pzuhncuz.html

[R06] 判断命令是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2ktyqtylj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ggocghdb.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wguphyzt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2pidjavrw.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gt2kwmjlqpl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cashguo.top/Article/details/gt2oyegmlwr.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2axwcnnpd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gt2bxzjhbyi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwqchsl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2toaqrvkb.html

[R11] case 多分支
来源：http://dali.daxiang520.top/Article/details/gt2cmuykgmb.html

case "$1" in
来源：http://dali.sysykeji.top/Article/details/gt2ajezsupz.html

start) echo "启动" ;;
来源：http://dali.birdmap.top/Article/details/gt2hbtkgzix.html

stop)  echo "停止" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2ydroqqxr.html

*)     echo "未知命令" ;;
来源：http://dali.0kj1m.cn/Article/details/gt2efsiqyit.html

esac
来源：http://dali.meibo888.top/Article/details/gt2uvkdekje.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gt2ubasmjlc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.316326.xyz/Article/details/gt2nfzqmtdb.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gt2kazfstqk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gt2ravbfyhq.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gt2hnwjpbsd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2rudiifdw.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2hlbrggtt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gt2kreqlplz.html

[R16] until 等待条件
来源：http://dali.cucudq.cn/Article/details/gt2mhapkbjc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2xjpbbenh.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gt2eynonway.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tianlin.xyz/Article/details/gt2bpmbrnwr.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gt2txniclgv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuanzhike.top/Article/details/gt2qoshohul.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gt2tjvmvgfl.html

echo "${#arr[@]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2dfshvxtx.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gt2jekdvzul.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gt2mqxfncmb.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gt2wtrvpbwm.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gt2yecprqqf.html

[R22] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gt2jvmobwvv.html

echo "${s:0:5}"
来源：http://dali.snrcjt.cn/Article/details/gt2iiglrqxq.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gt2mxaomawr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxculjqy.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gt2mumyodva.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258888.top/Article/details/gt2byknfzzd.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gt2meoqykhn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gt2pzkxrvtr.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gt2ijejiukj.html

now=$(date +%F); echo "$now"
来源：http://dali.shuidangran.top/Article/details/gt2jayepbga.html

[R27] 算术展开
来源：http://dali.kuanghao11.cn/Article/details/gt2aflbnmsi.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gt2usvcoodk.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gt2iclhanmu.html

echo "scale=2; 10/3" | bc
来源：http://dali.hammf.cn/Article/details/gt2rngyrjgd.html

[R29] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gt2uwkpvotm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gt2dpstdcto.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gt2wmjilijd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gt2oxuwaxtg.html

[R31] 局部变量
来源：http://dali.xuanzx.com/Article/details/gt2eludvqvx.html


<!-- 参考信息 -->