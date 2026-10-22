代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hysaishi.cn/Article/details/gt2ikrhbqfs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gt2qgzycymo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gt2dvayyhok.html

PHP:  if (empty($x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2lmusiwpu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.c1oappe.top/Article/details/gt2fobiohqp.html

TS:   if (x == null) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2qingthje.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gt2jyvtfxvd.html

Go:   if x == nil {}
来源：http://dali.fzhhl.top/Article/details/gt2vnbauxnk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gt2tuzhlmnd.html

C#:   if (x is null) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2vqkubmdx.html

[P07] 防抖与节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cddkytfa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gt2mykowphx.html

PHP:  // 手写时间戳比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvsnsvrx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gt2somfjfty.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gt2czwwcfdp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zdqjudy.top/Article/details/gt2zgluubqz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gotoacloud.top/Article/details/gt2hiwjqmxh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258.top/Article/details/gt2wpqjmxlk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shuidangran.top/Article/details/gt2wrqzzfpj.html

[P08] 处理浮点精度问题
来源：http://dali.chenjidiqi.icu/Article/details/gt2icrcessq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sufxvd.cn/Article/details/gt2oyhwuhbb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gt2kvrgtvjs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xziqi.cn/Article/details/gt2lqvnmwtk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gt2ogsoxsnn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gt2cybxzteq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gt2sdekgohl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2upoyhfrh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.birdmap.top/Article/details/gt2ootjfbcy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2pwjqzxun.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gt2eyopifig.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2bnyfiday.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gt2puguhwzi.html

CREATE TABLE users (
来源：http://dali.dashuyun.cn/Article/details/gt2xxsjshnd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gt2hicarwhf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj202588.top/Article/details/gt2kkpvallm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangshuangyany.cn/Article/details/gt2dlmdnwni.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xinyue.icu/Article/details/gt2mjxolryc.html

);
来源：http://dali.zhixingplan.top/Article/details/gt2ivnnoabb.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gt2feixwpqh.html

CREATE TABLE orders (
来源：http://dali.sysykeji.top/Article/details/gt2vkosoiax.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gt2yyreoglf.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gt2nzveymbl.html

amount DECIMAL(10, 2),
来源：http://dali.gaohongyu789.top/Article/details/gt2vblnnkwl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.smart0.xyz/Article/details/gt2kvjwiquv.html

);
来源：http://dali.cashguo.top/Article/details/gt2aqhqhjju.html

[Q03] 增加列
来源：http://dali.zhengqikj.top/Article/details/gt2csmpbzgp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gt2atviukmj.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gt2gjjjvwry.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cucudq.cn/Article/details/gt2zqzkqnnl.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gt2bvrwwoog.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhongyouzk.top/Article/details/gt2icrnqiyf.html

[Q06] 删除列
来源：http://dali.fengsongda.top/Article/details/gt2vmmlpato.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigufen.top/Article/details/gt2dkiejlag.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gt2uxyqgfwr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gt2hevwvogr.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2oukpojgy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gt2itoffhxy.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gt2lfsftaow.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzkwknm.html

[Q10] 插入单行
来源：http://dali.gotoacloud.top/Article/details/gt2kfsyapdw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hywenlv.cn/Article/details/gt2uonqufbq.html

[Q11] 一次插入多行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fflyssta.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gt2ismwszgi.html

[Q12] 插入后取自增 ID
来源：http://dali.havefunace.top/Article/details/gt2tvmnirlg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gt2qgdpwfap.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuetiantiany.cn/Article/details/gt2seguemqq.html

[Q13] 忽略重复插入
来源：http://dali.cqqwz.cn/Article/details/gt2vnbzioms.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guowangkeji.top/Article/details/gt2adzbpfgo.html

[Q14] 存在则更新（upsert）
来源：http://dali.gotoacloud.top/Article/details/gt2ghmntoot.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxuanxn.top/Article/details/gt2kmeuewpe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hfpthk.cn/Article/details/gt2zfnqrawz.html

[Q15] 查询全部
来源：http://dali.tianlin.xyz/Article/details/gt2mpwlvzuz.html

SELECT * FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2dlkrvybx.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gt2rwzghdkm.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2mqdmafck.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gt2zwrckxnx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ydzc1.top/Article/details/gt2nsiuqrjn.html

[Q18] 模糊匹配
来源：http://dali.haohaochexian.top/Article/details/gt2rhvxkxrs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gt2qdgmhkgz.html

[Q19] 范围查询
来源：http://dali.hammf.cn/Article/details/gt2siltamgw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ovtmmxvu.html

[Q20] IN 列表
来源：http://dali.iojbl.cn/Article/details/gt2twfebizn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2oapcbiwn.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gt2klocnxqg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gt2ckbpmfcj.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gt2zcwyadnx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tanke756.top/Article/details/gt2kvfaikre.html

[Q23] 分页
来源：http://dali.xinyue.icu/Article/details/gt2fyklsire.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ivvv.top/Article/details/gt2hvoksqln.html

[Q24] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwsoodzi.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2xyydzsee.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqrwqwzu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.redwolf501.top/Article/details/gt2zehmuynp.html

[Q26] 计数
来源：http://dali.xylfe.cn/Article/details/gt2zpuqdjds.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpguwtjp.html

[Q27] 条件计数
来源：http://dali.chenlongwang.top/Article/details/gt2oomesccr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2zeousjvz.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gt2zyyvihzr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2axpevnlo.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gt2zuytpztm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2tltneaij.html

[Q30] 分组统计
来源：http://dali.nwbrower.top/Article/details/gt2aksbgbep.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gt2mddgquls.html

[Q31] 分组后过滤
来源：http://dali.yueranfly.top/Article/details/gt2asihwkcq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.birdmap.top/Article/details/gt2ogzdsuze.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aflmlzcw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gt2ktpbvqbx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gt2otkyznwn.html

[Q33] 多列分组
来源：http://dali.redwolf501.top/Article/details/gt2zfphphqq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cashguo.top/Article/details/gt2uqsmbvld.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gt2umdopztn.html

SELECT * FROM (
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkmqcvqh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangshuangyany.cn/Article/details/gt2kyfyzppd.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gt2zpqygale.html

[Q35] 内连接
来源：http://dali.aibaodan.cn/Article/details/gt2pvwvbfra.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gt2tinjihlr.html

[Q36] 左连接
来源：http://dali.316326.xyz/Article/details/gt2cgxvdevp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gt2lyoabwqd.html

[Q37] 右连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2efxbidaa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gt2qmtrdzdi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlvisqlr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gt2afpujkdt.html

[Q39] 自连接（查上下级）
来源：http://dali.daria6918.cn/Article/details/gt2epgrbaxt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258.top/Article/details/gt2lanbjsfl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gt2xmkekgnz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnqzz.top/Article/details/gt2xbnwnebt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hfpthk.cn/Article/details/gt2lcdwzycx.html

[Q41] 多表连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2lercghyz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.9152youxi.cn/Article/details/gt2zjsxfnak.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gt2sqrovyqr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gt2trqusrlw.html

[Q42] 连接条件附加过滤
来源：http://dali.redwolf501.top/Article/details/gt2krzunjqr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yonumen.top/Article/details/gt2yxmrnckk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ybcxt.top/Article/details/gt2acfnffmw.html

[Q43] 标量子查询
来源：http://dali.yueranfly.top/Article/details/gt2gwyxbzxa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gt2iouxpzej.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gt2cdfwhxwm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jianghu66.top/Article/details/gt2mbnqjhqr.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gt2obbfkbmy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gt2usythnvf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yangfankeji.com/Article/details/gt2cgbvpqfj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gt2gmjgobge.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gt2viadvbqw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj202588.top/Article/details/gt2yxtpyhvh.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cndyjkyc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hammf.cn/Article/details/gt2jasphucb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hywenlv.cn/Article/details/gt2fknlnfrw.html

[Q49] 更新单行
来源：http://dali.c1oappe.top/Article/details/gt2lfzylxhu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqnbtwmn.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gt2nshetuuq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.andypj.xyz/Article/details/gt2fdyaxbbi.html

[Q51] 用子查询更新
来源：http://dali.jqgufenzy.top/Article/details/gt2hdxkwetg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2uxcdwibl.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gt2hbceqmco.html

DELETE FROM users WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2nfbhhlzp.html

[Q53] 按条件删除
来源：http://dali.feifeiyinyue.top/Article/details/gt2emegcdhf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daria6918.cn/Article/details/gt2phbddewv.html

[Q54] 清空表
来源：http://dali.smart0.xyz/Article/details/gt2vvtirajc.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gfhgqjbz.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gt2fsmmehzo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpnzuhsf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daxiang520.top/Article/details/gt2wbucsidj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gt2ptqmkfms.html

[Q57] 行号
来源：http://dali.cheryme.top/Article/details/gt2zzjaukoz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gt2ndtarhir.html

[Q58] 累计求和
来源：http://dali.0kj1m.cn/Article/details/gt2xgqeaett.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2odnlhfsa.html

[Q59] 分组内累计
来源：http://dali.hfpthk.cn/Article/details/gt2nosknhdg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2ccquklgz.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gt2wfkauhpm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gt2nenuupgv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2pemmgoel.html

[Q61] 移动平均
来源：http://dali.ppjwa.cn/Article/details/gt2cgitykkv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2jqupxlld.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gt2zkrohvib.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gt2slazbzhb.html

[Q63] 开启事务
来源：http://dali.zhengqikj.top/Article/details/gt2gnuiuwmp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gt2paykfktk.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gt2xijicdxq.html

COMMIT;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzhwdvxt.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gt2lnhhnott.html

ROLLBACK;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2igkusvpd.html

[Q66] 行锁查询
来源：http://dali.jianghu66.top/Article/details/gt2nwcxsaam.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dashuyun.cn/Article/details/gt2mtjxxqjv.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gt2wxtoaojn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fyuqgqdr.html

[Q68] 保存点
来源：http://dali.nanxinkj.top/Article/details/gt2hliczenl.html

SAVEPOINT sp1;
来源：http://dali.havefunace.top/Article/details/gt2weqlbnjt.html

ROLLBACK TO sp1;
来源：http://dali.birdmap.top/Article/details/gt2tdsvwcer.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gt2pfqsvywm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shuidangran.top/Article/details/gt2rrdlmhvp.html

[Q70] 更新统计信息
来源：http://dali.vqdsnc.cn/Article/details/gt2jhikofnb.html

ANALYZE TABLE users;
来源：http://dali.iojbl.cn/Article/details/gt2molfigaq.html

[Q71] 查看建表语句
来源：http://dali.kuanghao11.cn/Article/details/gt2kdjcjzxn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yvedp.cn/Article/details/gt2qbjxoezs.html

[Q72] 查看索引
来源：http://dali.meibo888.top/Article/details/gt2urrcnlzn.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2uigmukbp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2psueyddb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sweek.top/Article/details/gt2cqlejvju.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gt2fygyqliq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zdqjudy.top/Article/details/gt2ksnzidtf.html

[Q75] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gt2jndfpxut.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2azzorkck.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gt2podkbxuk.html

[Q76] 按天统计
来源：http://dali.ybcxt.top/Article/details/gt2rznyuqto.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gt2iiawiaxy.html

[Q77] 时间加减
来源：http://dali.ybcxt.top/Article/details/gt2gemflpxq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gt2xkippbry.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfpbvcma.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cucudq.cn/Article/details/gt2mgovpdkw.html

[Q79] 字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwqqgoau.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jlsjyb.cn/Article/details/gt2kwxczaol.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gt2hvgdabmr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2mkmaenst.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gt2htvlggrm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cheryme.top/Article/details/gt2bdajgcew.html

[Q82] 字符长度与字节长度
来源：http://dali.hywenlv.cn/Article/details/gt2rkerhftp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2oeywxyhn.html

[Q83] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gt2rctvdngw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zbejonsu.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gt2qukxuxym.html

SELECT TRIM(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2ukozseue.html

[Q85] 数值取整
来源：http://dali.yj20258.top/Article/details/gt2hcefwopg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guowangkeji.top/Article/details/gt2kwktvfgg.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gt2ziiyzpti.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gt2twlfxxbe.html

[Q87] JSON 字段做条件
来源：http://dali.c1oappe.top/Article/details/gt2ckswjhrm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gt2wskxmiio.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gt2ekkaicki.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tanke756.top/Article/details/gt2ikxpkfzk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egibtewx.html

[Q89] 判断表是否存在
来源：http://dali.guannengcc.top/Article/details/gt2ixkvtkff.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndejediq.html

[Q90] 生成序号列
来源：http://dali.tianlin.xyz/Article/details/gt2dxzgifyz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.bjfxy.top/Article/details/gt2tnyyyjww.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2sdxmxtdm.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gt2oppxyisu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2eddllswg.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gt2gqdgxitc.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gt2fxhednrw.html

set -euo pipefail
来源：http://dali.hnqzz.top/Article/details/gt2iqajcfja.html

[R02] 变量赋值与使用
来源：http://dali.zycfv.cn/Article/details/gt2dixfdgjq.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gt2vbawsrxd.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gt2flvszyjq.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gt2pdifzvgx.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2regmlpzp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gt2nzjngooy.html

[R05] 参数默认值
来源：http://dali.tanke756.top/Article/details/gt2mcwngcyz.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gt2xcklwamt.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gt2kkuwpgoi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2tvigeasg.html

[R07] if 判断文件
来源：http://dali.cucudq.cn/Article/details/gt2aosfrbhy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gt2dmuulxag.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gt2mnhywavw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yohedmmp.html

[R09] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gt2sxfiwvtc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sxryk.cn/Article/details/gt2wqjrjjqq.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gt2zyazkhwa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gt2fhosmiej.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gt2oxxydsvf.html

case "$1" in
来源：http://dali.pengpengdd.cyou/Article/details/gt2eyiwcsar.html

start) echo "启动" ;;
来源：http://dali.shuidangran.top/Article/details/gt2itpfdnhx.html

stop)  echo "停止" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gt2uvewmwhj.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2oajrsoyh.html

esac
来源：http://dali.yj20258888.top/Article/details/gt2corbltle.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxpzjajy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aibaodan.cn/Article/details/gt2qzjisnxc.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gt2sseszlal.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gt2iewsuwbi.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gt2ixlvnfas.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gt2lxhmnnel.html

[R15] while 逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2pfqmefno.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yonumen.top/Article/details/gt2qsvdkxkv.html

[R16] until 等待条件
来源：http://dali.yonumen.top/Article/details/gt2hxrfjrvm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gt2sgukitug.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gt2ojmuugzm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrrosjxu.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gt2nyuqkbqf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bqohxtik.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqabiotp.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gt2xpscujym.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gt2iqcllxlv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuanzx.com/Article/details/gt2rishycun.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gt2lqopbfsk.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gt2pymdeeyi.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gt2niioijdg.html

echo "${s:0:5}"
来源：http://dali.ehwqpu.com/Article/details/gt2rdlvpenr.html

[R23] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbbmaols.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gt2iksyzcuz.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gt2jmhbilqj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dashuyun.cn/Article/details/gt2bvytzsga.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gt2pbiuphuu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gt2ixaygpuq.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gt2zgudpvkx.html

now=$(date +%F); echo "$now"
来源：http://dali.guowangkeji.top/Article/details/gt2znssccpf.html

[R27] 算术展开
来源：http://dali.kuanghao11.cn/Article/details/gt2ihiojeaf.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gt2ljdvpkps.html

[R28] 浮点运算
来源：http://dali.zhixingplan.top/Article/details/gt2mzkqerfh.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gt2qadjjrif.html

[R29] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gt2tkvknvww.html


<!-- 参考信息 -->