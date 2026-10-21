代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtpbcyakaj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aizwys.cn/Article/details/gtxvantrop.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtoylwamvd.html

Ruby: a == b
来源：http://dali.jinqigufen.top/Article/details/gtgbfvuuxl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgangxyxz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gtanqpeule.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gotoacloud.top/Article/details/gtmxkbctpy.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gtbkzueqni.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xylfe.cn/Article/details/gtvwjvgkqs.html

TS:   if (x == null) {}
来源：http://dali.xylfe.cn/Article/details/gtkclbfgld.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtgnaczhtm.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gtswqtnjor.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenlongwang.top/Article/details/gticlfmmkv.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gtzbxqxwfi.html

[P07] 防抖与节流
来源：http://dali.zhongyouzk.top/Article/details/gtytgxunao.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigfzy.top/Article/details/gtfrsjypsd.html

PHP:  // 手写时间戳比较
来源：http://dali.chenlongwang.top/Article/details/gtoxijqwqt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtfqjnncvg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtdpjgrlhf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.svipenyu.cn/Article/details/gtcdlqpihi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhoulong.xyz/Article/details/gtguapmdks.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.haohaochexian.top/Article/details/gtfcvmpvby.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gterpsyfqi.html

[P08] 处理浮点精度问题
来源：http://dali.cucudq.cn/Article/details/gtwvmmecak.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gtrszzcygb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.vqdsnc.cn/Article/details/gtaswdvvgi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cqqwz.cn/Article/details/gttvxjziey.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtmpzgamdw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pengpengdd.cyou/Article/details/gtkyrzqdjo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gtxejsiojn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jianghu66.top/Article/details/gtoeaopvvs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ehwqpu.com/Article/details/gtvuaefdxd.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtyyupksic.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinghuilouyu.cn/Article/details/gtysimhozf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtddehgvni.html

[Q01] 创建表
来源：http://dali.yongpay.top/Article/details/gtxpeiedik.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gtrqpkxpru.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtjmwzrgft.html

name VARCHAR(50) NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gtaqfzhbah.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yanxiufei.cn/Article/details/gteqfgircg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhiwuduotai.top/Article/details/gtcpqpgygc.html

);
来源：http://dali.9152youxi.cn/Article/details/gtciteabju.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gtxsjrdhmw.html

CREATE TABLE orders (
来源：http://dali.chenlongwang.top/Article/details/gtlundrqgk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlncezdpd.html

user_id INT NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gtrnuffdra.html

amount DECIMAL(10, 2),
来源：http://dali.svipenyu.cn/Article/details/gtehggdrhv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sweek.top/Article/details/gtrhjyhlab.html

);
来源：http://dali.jinqigufen.top/Article/details/gtchzsumis.html

[Q03] 增加列
来源：http://dali.zhoulong.xyz/Article/details/gtjzlrgjue.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gtepzcbgph.html

[Q04] 修改列类型
来源：http://dali.hfpthk.cn/Article/details/gtrrpdnkxn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gtrajwfzgs.html

[Q05] 重命名列
来源：http://dali.wangshuangyany.cn/Article/details/gtveoalisi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gtsamzkykn.html

[Q06] 删除列
来源：http://dali.hammf.cn/Article/details/gtnzcspges.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yonumen.top/Article/details/gtpfzgxurx.html

[Q07] 删除表
来源：http://dali.hfpthk.cn/Article/details/gtdgnegvbl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gtrjasyvrq.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gtrcbtouam.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtlljqlenc.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gtcnzgtrms.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtaypuzkma.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gtwifuwpnd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtwyutbnsf.html

[Q11] 一次插入多行
来源：http://dali.xinyue.icu/Article/details/gtdaycptlo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtaztxlaxg.html

[Q12] 插入后取自增 ID
来源：http://dali.aizwys.cn/Article/details/gtxjbbglve.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gtprgzraiy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.meibo888.top/Article/details/gtaabqolhc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gtracqezay.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gtpenzpyhe.html

[Q14] 存在则更新（upsert）
来源：http://dali.yanxiufei.cn/Article/details/gteifcssfx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gtjywosqbx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daxiang520.top/Article/details/gtdvfycccj.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gtjlsybnek.html

SELECT * FROM users;
来源：http://dali.tanke756.top/Article/details/gtwwkyfmzu.html

[Q16] 查询指定列
来源：http://dali.zhengqikj.top/Article/details/gtgjyositm.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtlnfgkyof.html

[Q17] 条件查询
来源：http://dali.nwbrower.top/Article/details/gtcfkqpyvq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daxiang520.top/Article/details/gtyelwsrlf.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gtodijdqeo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zdqjudy.top/Article/details/gtcchsgdhc.html

[Q19] 范围查询
来源：http://dali.snrcjt.cn/Article/details/gttbmlxzwo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gtaggbjgag.html

[Q20] IN 列表
来源：http://dali.zhoulong.xyz/Article/details/gtmdtmqlcj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.iojbl.cn/Article/details/gtlgtxrgsu.html

[Q21] 空值判断
来源：http://dali.yangfankeji.com/Article/details/gtievaihkn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gtvbnuqwjy.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnumgxxfv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gtjtgxboyq.html

[Q23] 分页
来源：http://dali.yonumen.top/Article/details/gtulcpxuwp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgcypeme.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtlzxxtbio.html

SELECT DISTINCT city FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtvfxrmqjd.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gtljdexnhv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yueranfly.top/Article/details/gtochnnqey.html

[Q26] 计数
来源：http://dali.xziqi.cn/Article/details/gtwzuywqqs.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtkinqwdwl.html

[Q27] 条件计数
来源：http://dali.yangfankeji.com/Article/details/gttttlylsm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtvtdvxzkj.html

[Q28] 求和与平均
来源：http://dali.gaohongyu789.top/Article/details/gteafcmyeb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtlxxlkspy.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gtshsvmvzb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtffacuqia.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gtcjhqhpyo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtmvpymrlu.html

[Q31] 分组后过滤
来源：http://dali.wangdashe.top/Article/details/gtbycdibzf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gttnxlhtgz.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gtltfryulr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtkzskuvav.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gtbcjxogwf.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchzkcixp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gtzmhplfkb.html

[Q34] 每组取第一条
来源：http://dali.ehwqpu.com/Article/details/gtvhvikkyr.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gtgtllbhnn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yueranfly.top/Article/details/gtgucjavsu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtfwasavwo.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gtgpwkofwe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gtqmhanwzz.html

[Q36] 左连接
来源：http://dali.yvedp.cn/Article/details/gtlmjqazdn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtpayakctw.html

[Q37] 右连接
来源：http://dali.chenjidiqi.icu/Article/details/gtgniixnge.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fzhhl.top/Article/details/gtdovpwltg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuanzhike.top/Article/details/gtqlmccuto.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtmkgmnhjx.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gtgougougr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.vqdsnc.cn/Article/details/gtrwwktidw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yueranfly.top/Article/details/gthgzlvtfl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jyoumei.cn/Article/details/gtuimgkncq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuetiantiany.cn/Article/details/gttohppfsw.html

[Q41] 多表连接
来源：http://dali.iojbl.cn/Article/details/gtmplzkpri.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gtfsaxlajn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtgyduostj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtvnpdfncj.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtthwonabz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yueranfly.top/Article/details/gtfiqlbpjv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cqqwz.cn/Article/details/gtgkfxbgqn.html

[Q43] 标量子查询
来源：http://dali.yvedp.cn/Article/details/gtzgztatip.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gtqytgykff.html

[Q44] IN 子查询
来源：http://dali.yongpay.top/Article/details/gtbntuhzlg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jianghu66.top/Article/details/gtfwieuzbp.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gtxcbuxuwt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtbvklwcuw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gtkekovsge.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtnherghun.html

[Q47] 与平均值比较
来源：http://dali.0kj1m.cn/Article/details/gtsorqkllv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gtcujmvlly.html

[Q48] CTE 公用表表达式
来源：http://dali.nwbrower.top/Article/details/gtxicoouhn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jyoumei.cn/Article/details/gthcqdtgvt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gtxnrbqocb.html

[Q49] 更新单行
来源：http://dali.wangshuangyany.cn/Article/details/gtvoditzxc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtjsiecjqi.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gtuxzpyhzw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.iojbl.cn/Article/details/gtjhiiuyco.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtiyxjtzji.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gtxqblyjpg.html

[Q52] 删除指定行
来源：http://dali.tian-w.cn/Article/details/gtxjbwyxry.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtknxylltc.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gtlinpwnns.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtoxunnlcg.html

[Q54] 清空表
来源：http://dali.hywenlv.cn/Article/details/gtklcpnypq.html

TRUNCATE TABLE logs;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpsdycox.html

[Q55] 排名（并列占位）
来源：http://dali.jiagoushi.top/Article/details/gtsspuopsh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtdlkhbwkc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqjgugyr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtwqnmmppq.html

[Q57] 行号
来源：http://dali.iojbl.cn/Article/details/gtgoupavhd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtimpegfke.html

[Q58] 累计求和
来源：http://dali.iojbl.cn/Article/details/gttsvojffp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtzoyrvrej.html

[Q59] 分组内累计
来源：http://dali.svipenyu.cn/Article/details/gtlojejrip.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtxnglhkkr.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gtclhkhgqc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yonumen.top/Article/details/gtgzdufupa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtjwdvbaub.html

[Q61] 移动平均
来源：http://dali.sweek.top/Article/details/gtxynwzdyc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtvculssol.html

[Q62] 分组占比
来源：http://dali.shuidangran.top/Article/details/gtimioheep.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtqubxhvzk.html

[Q63] 开启事务
来源：http://dali.hongshengwenyu.top/Article/details/gtgphmhceh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.0kj1m.cn/Article/details/gtgcqcylxa.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gtfgecqdot.html

COMMIT;
来源：http://dali.hongshengwenyu.top/Article/details/gtpdpcassc.html

[Q65] 回滚事务
来源：http://dali.xuanzx.com/Article/details/gtbvexmfyj.html

ROLLBACK;
来源：http://dali.ehwqpu.com/Article/details/gtfksvecwa.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gtacxtowmo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhixingplan.top/Article/details/gtmfexzxjr.html

[Q67] 设置隔离级别
来源：http://dali.jinqigfzy.top/Article/details/gtsouygnfu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblnmthje.html

[Q68] 保存点
来源：http://dali.gogol.net.cn/Article/details/gtetgaveuc.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtmsfzgfpt.html

ROLLBACK TO sp1;
来源：http://dali.cdnleiting.top/Article/details/gthyxvksbz.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gtawqhvzcl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gtcdplykrs.html

[Q70] 更新统计信息
来源：http://dali.pycfn.com/Article/details/gtmkhjlyjj.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gtyvmwsugu.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gtstrlzdrp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gtmdqynzfj.html

[Q72] 查看索引
来源：http://dali.hywenlv.cn/Article/details/gtngztmlcb.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtqdbqhlpe.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gtsaovhbnm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtggmcaegk.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gtwwiukzyd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gtzkjiztnp.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtahnihnnw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtcjxixxmj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gtrwenlkku.html

[Q76] 按天统计
来源：http://dali.jinqigfzy.top/Article/details/gtlpuxojkt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gthdsfniaf.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gtjrxljplc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xylfe.cn/Article/details/gtafzfxkke.html

[Q78] 当前时间
来源：http://dali.tanke756.top/Article/details/gttylxrpii.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gtfddbazzv.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtodemrmri.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gteqtkpsrg.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gtpsfurstq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtmduradgp.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gthaykppiq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xylfe.cn/Article/details/gtjheejced.html

[Q82] 字符长度与字节长度
来源：http://dali.sysykeji.top/Article/details/gtkxlprewn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtrkqjbaas.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtnxadqvjm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtesfwsgim.html

[Q84] 去除首尾空格
来源：http://dali.hfpthk.cn/Article/details/gtjykmowzq.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemxzsote.html

[Q85] 数值取整
来源：http://dali.chenjidiqi.icu/Article/details/gtaqqithvd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gtrpupsibw.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gtxtqfckav.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ppjwa.cn/Article/details/gtywboalga.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gtfddpofua.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhixingplan.top/Article/details/gtwkjlmdyx.html

[Q88] 行转列（条件聚合）
来源：http://dali.yanxiufei.cn/Article/details/gtflqjbupg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnxiangtu.top/Article/details/gtbfunxdpa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ivvv.top/Article/details/gtrzlivcvx.html

[Q89] 判断表是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanavbmdd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gtdsupfpbx.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gtnamzyyvz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gtidxhvhcl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtxwbfqpzc.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gtusfuovjy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwhgoegbp.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gtapcgtcbu.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gtdfdnelkn.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gtbfphkuox.html

[R02] 变量赋值与使用
来源：http://dali.zhoulong.xyz/Article/details/gtaqygfoix.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gtghcvpyxk.html

[R03] 只读变量
来源：http://dali.yvedp.cn/Article/details/gtfhqossfa.html

readonly PI=3.14
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopxntykd.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gtymxhrbrq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gtsxusdshj.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gtrgzgyspg.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gtubkfnqfi.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gthivosjkq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtvpbikehk.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gtzpxjgvxu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtqfiveqef.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gtqjongrvw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gtazogkiyi.html

[R09] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszeynaqm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gtgdsfndgo.html

[R10] 正则匹配
来源：http://dali.zhongyouzk.top/Article/details/gtvdnlslic.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gtjnbuzrif.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gtorwvkhsy.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gtpftthrko.html

start) echo "启动" ;;
来源：http://dali.yuanzhike.top/Article/details/gtwstrlysz.html

stop)  echo "停止" ;;
来源：http://dali.yvedp.cn/Article/details/gtuzhhwjue.html

*)     echo "未知命令" ;;
来源：http://dali.aibaodan.cn/Article/details/gtthnclfuw.html

esac
来源：http://dali.meibo888.top/Article/details/gtglvolaam.html

[R12] for 遍历文件
来源：http://dali.yuxming.cn/Article/details/gtiffmajeh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgrwfiqt.html

[R13] for 计数循环
来源：http://dali.tanke756.top/Article/details/gtuorrcoqk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtxtzptugd.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gtuuktjzpy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtfctbiwic.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gtkbzeltng.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gtjldmsezm.html

[R16] until 等待条件
来源：http://dali.dianchejie.cn/Article/details/gtkjgghcwv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtpdurcjbm.html

[R17] 数组定义与取值
来源：http://dali.redwolf501.top/Article/details/gtntxjprfn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ppjwa.cn/Article/details/gtabozgcfb.html

[R18] 遍历数组
来源：http://dali.hnxiangtu.top/Article/details/gtzlletybo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gtjckmbcsm.html

[R19] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtkreasilm.html

echo "${#arr[@]}"
来源：http://dali.gogol.net.cn/Article/details/gtmmrchvvl.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gtgcnsthpz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sufxvd.cn/Article/details/gtmmisyatx.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtgqnqpugb.html

echo "${#s}"
来源：http://dali.yuxming.cn/Article/details/gtfirynnws.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtpwsalotb.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gtparscsck.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtdpnzoqcu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnqzz.top/Article/details/gtclwernjf.html

[R24] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtdmyrfwui.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.iojbl.cn/Article/details/gtynjqurfn.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gtkvyqyejl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtqoashpsu.html

[R26] 命令替换
来源：http://dali.yuanzhike.top/Article/details/gtoipinuup.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gthdqkzdth.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gtmippumuu.html


<!-- 参考信息 -->