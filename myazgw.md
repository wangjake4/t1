代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jyoumei.cn/Article/details/gttkrjzjma.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gthptjzatc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtshvflyme.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtyxggjeuf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gttqxxszdm.html

Go:   len(arr);  len(m)
来源：http://dali.pengpengdd.cyou/Article/details/gtbgpluzko.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gtsurbueyw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqaembed.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gtuujqxipn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangdashe.top/Article/details/gtcgxuccag.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubnoiwgp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.feifeiyinyue.top/Article/details/gteelbipmt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gttkwzwzyn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cqqwz.cn/Article/details/gtnmmrsifu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtiblkfsoa.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gtahzrywus.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yangfankeji.com/Article/details/gtggysfodp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xinyue.icu/Article/details/gtgvncyobc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.andypj.xyz/Article/details/gtdkbwrwth.html

PHP:  if (empty($x)) {}
来源：http://dali.ehwqpu.com/Article/details/gtvykqrutp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gtaccppzun.html

TS:   if (x == null) {}
来源：http://dali.guannengcc.top/Article/details/gtiuueqmou.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtyruzvidy.html

Go:   if x == nil {}
来源：http://dali.gaohongyu789.top/Article/details/gthqoqcgvf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gtblowvxjt.html

C#:   if (x is null) {}
来源：http://dali.yueranfly.top/Article/details/gtkiqsgvsn.html

[P07] 防抖与节流
来源：http://dali.jqgufenzy.top/Article/details/gtlpdiaqsg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zycfv.cn/Article/details/gtqdppsirz.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gtcgklrvat.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtlewpfwmg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtuakyxpph.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtsrwsrefi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sweek.top/Article/details/gtgymceryh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gogol.net.cn/Article/details/gtjwrajntk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gttllhelre.html

[P08] 处理浮点精度问题
来源：http://dali.hywenlv.cn/Article/details/gtsyuezgpi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxinkj.top/Article/details/gtvpnqhrfv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yvedp.cn/Article/details/gtfrfnvbhf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ppjwa.cn/Article/details/gtybzzvxbf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtepbiipav.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pengpengdd.cyou/Article/details/gtgmkikbky.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gthoaoknyw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gtjlcqdpro.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gtfofubszs.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtyqsjxrjd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gotoacloud.top/Article/details/gtagvxdjlg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtivfwnoqv.html

[Q01] 创建表
来源：http://dali.tianlin.xyz/Article/details/gtbwjwjcet.html

CREATE TABLE users (
来源：http://dali.wangdashe.top/Article/details/gtzucrhoda.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfrdhygx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnhwqxsp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jyoumei.cn/Article/details/gtktbyoefn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.andypj.xyz/Article/details/gtyswifgqj.html

);
来源：http://dali.snrcjt.cn/Article/details/gtkuaylout.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gtcxmlftue.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gtdzizrydg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gtziskfzma.html

user_id INT NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtikcrgtbu.html

amount DECIMAL(10, 2),
来源：http://dali.sysykeji.top/Article/details/gtaycfeabr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.iojbl.cn/Article/details/gtuvkcoxyr.html

);
来源：http://dali.pycfn.com/Article/details/gtwwfrlzsk.html

[Q03] 增加列
来源：http://dali.nanxuanxn.top/Article/details/gtcaoxvxpt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.iojbl.cn/Article/details/gtdgpeasem.html

[Q04] 修改列类型
来源：http://dali.yanxiufei.cn/Article/details/gtnzeqoepj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gtyuchlzts.html

[Q05] 重命名列
来源：http://dali.yuanzhike.top/Article/details/gtwuiwrdlq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gtpbynckrm.html

[Q06] 删除列
来源：http://dali.yj202588.top/Article/details/gtmgtuxxet.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gtxsfzzvvh.html

[Q07] 删除表
来源：http://dali.hfpthk.cn/Article/details/gtvufgvqft.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gogol.net.cn/Article/details/gtroymsknw.html

[Q08] 创建普通索引
来源：http://dali.shangyingyoupin.top/Article/details/gtipeloemr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfqhpyli.html

[Q09] 创建唯一索引
来源：http://dali.yuxming.cn/Article/details/gtywnppoll.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gtzlnkswfz.html

[Q10] 插入单行
来源：http://dali.yj202588.top/Article/details/gtfloryhfs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.birdmap.top/Article/details/gtuwfffvuu.html

[Q11] 一次插入多行
来源：http://dali.ppjwa.cn/Article/details/gtfqzcyrtb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtkdelvfbu.html

[Q12] 插入后取自增 ID
来源：http://dali.cucudq.cn/Article/details/gtwuddpswq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.snrcjt.cn/Article/details/gtxyrjjhkr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gtymrmalnv.html

[Q13] 忽略重复插入
来源：http://dali.jiagoushi.top/Article/details/gtngwpxmvl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtrfnyegis.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gtdnqgmutp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gtypvivyda.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gtcjkrceiw.html

[Q15] 查询全部
来源：http://dali.ivvv.top/Article/details/gtkucfvxao.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtyzomeivq.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gtlvddpasm.html

SELECT id, name FROM users;
来源：http://dali.ivvv.top/Article/details/gtenwejjji.html

[Q17] 条件查询
来源：http://dali.yanxiufei.cn/Article/details/gtrzokbxyv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gtrqxocfgu.html

[Q18] 模糊匹配
来源：http://dali.smart0.xyz/Article/details/gtqbdpvvcp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gtmxpuegwp.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gtmhtjeylc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ybcxt.top/Article/details/gtqjvgfsjx.html

[Q20] IN 列表
来源：http://dali.zhixingplan.top/Article/details/gtosffjgvf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jianghu66.top/Article/details/gtnnsmfnbz.html

[Q21] 空值判断
来源：http://dali.sysykeji.top/Article/details/gtlgcpvdlk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nwbrower.top/Article/details/gtcntdrxwq.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjwswaev.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxuanxn.top/Article/details/gtwqzzpdcc.html

[Q23] 分页
来源：http://dali.svipenyu.cn/Article/details/gttivrarji.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gtrapunokq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gtwygapjkn.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtqsbnuvbu.html

[Q25] 只取前 N 条
来源：http://dali.yj20258.top/Article/details/gteuvdhjin.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.316326.xyz/Article/details/gtwhpryjbe.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gtcamptdva.html

SELECT COUNT(*) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtuqspiujf.html

[Q27] 条件计数
来源：http://dali.tanke756.top/Article/details/gteiizscrt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtqsdfpdve.html

[Q28] 求和与平均
来源：http://dali.gogol.net.cn/Article/details/gtntaxlcdg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtlspxebhp.html

[Q29] 最大最小值
来源：http://dali.yuanzhike.top/Article/details/gtgxdfkbte.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtjrbqvtcr.html

[Q30] 分组统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsuchhhc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gteeyrkgnb.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gtplivknjb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.redwolf501.top/Article/details/gtftlasyrj.html

[Q32] 分组拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtacmmqamo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtheqjoyoy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pengpengdd.cyou/Article/details/gtkvworsrx.html

[Q33] 多列分组
来源：http://dali.zhoulong.xyz/Article/details/gtvtmwgfpd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhongyouzk.top/Article/details/gtwcjyzakd.html

[Q34] 每组取第一条
来源：http://dali.yueranfly.top/Article/details/gthfhssuqo.html

SELECT * FROM (
来源：http://dali.zhengqikj.top/Article/details/gtqddjgjoz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cqqwz.cn/Article/details/gtwopzefef.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gtekpbjofm.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gtyuluysel.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gtxawqvnin.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gtsrsqpnkq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtoehdmlin.html

[Q37] 右连接
来源：http://dali.jinqigufen.top/Article/details/gtkiescjqn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgufenzy.top/Article/details/gttwirzkwb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.feifeiyinyue.top/Article/details/gtxkupdgct.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gttuigeykz.html

[Q39] 自连接（查上下级）
来源：http://dali.xinyue.icu/Article/details/gtzbnoengu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guannengcc.top/Article/details/gtkbvukrrf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fengsongda.top/Article/details/gtkvqlimrk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gtmvrxobdu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuxming.cn/Article/details/gtiuodwtiw.html

[Q41] 多表连接
来源：http://dali.iojbl.cn/Article/details/gtoksnaxjp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258888.top/Article/details/gtwujlussx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.havefunace.top/Article/details/gtxnyzbuae.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dianchejie.cn/Article/details/gtlatnkfha.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gtrxdsledk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gthpohymfh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuanzx.com/Article/details/gtiwskjjgt.html

[Q43] 标量子查询
来源：http://dali.gaohongyu789.top/Article/details/gtzpxwztkv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guowangkeji.top/Article/details/gtmuyrehgm.html

[Q44] IN 子查询
来源：http://dali.birdmap.top/Article/details/gtmtanrujp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkkrlxkn.html

[Q45] EXISTS 判断存在
来源：http://dali.sufxvd.cn/Article/details/gtjqleteuy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gttwhmgpkn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhiwuduotai.top/Article/details/gtunppsjdm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gthxmrjumk.html

[Q47] 与平均值比较
来源：http://dali.yonumen.top/Article/details/gtualqxdlo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrekxhqa.html

[Q48] CTE 公用表表达式
来源：http://dali.cqqwz.cn/Article/details/gtphhtbchc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.316326.xyz/Article/details/gthacqyvyt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxqxwjid.html

[Q49] 更新单行
来源：http://dali.0kj1m.cn/Article/details/gteklavuqc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gttrxchqaf.html

[Q50] 批量更新
来源：http://dali.snrcjt.cn/Article/details/gtrfjpsuix.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtbhcnpvvq.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gtinxiqvun.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daxiang520.top/Article/details/gtfjhlsqex.html

[Q52] 删除指定行
来源：http://dali.xylfe.cn/Article/details/gtdvfroihz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtruewmuje.html

[Q53] 按条件删除
来源：http://dali.zhoulong.xyz/Article/details/gtwwayvzwi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgnxgiwm.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtqvlkmair.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gtzakjvnkm.html

[Q55] 排名（并列占位）
来源：http://dali.cheryme.top/Article/details/gtplbvdnlh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtxukvwrhm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gtdjkhpida.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.birdmap.top/Article/details/gtuhamgspo.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gtvwjhyzzj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtiaplnqel.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gtycagsvll.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hammf.cn/Article/details/gtwkjpunvq.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtrnsnvsog.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtpyjnwkxj.html

[Q60] 取上一行 / 下一行
来源：http://dali.jyoumei.cn/Article/details/gteidbqgsr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkcnrntl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtsvpzcbyq.html

[Q61] 移动平均
来源：http://dali.vqdsnc.cn/Article/details/gtgnycjbmt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtfcixbqhy.html

[Q62] 分组占比
来源：http://dali.yuxming.cn/Article/details/gtjesqqjxu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtpzmkklae.html

[Q63] 开启事务
来源：http://dali.sufxvd.cn/Article/details/gtbpjufypv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yangfankeji.com/Article/details/gtoujeugwg.html

[Q64] 提交事务
来源：http://dali.xziqi.cn/Article/details/gtjccugddy.html

COMMIT;
来源：http://dali.cucudq.cn/Article/details/gtmzoirzln.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gtxibzcnnj.html

ROLLBACK;
来源：http://dali.ydzc1.top/Article/details/gttfnadwoq.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzslmpaim.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gotoacloud.top/Article/details/gtkbzxfisj.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyvhkjnt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gtatmkqcam.html

[Q68] 保存点
来源：http://dali.andypj.xyz/Article/details/gtlyjewzbz.html

SAVEPOINT sp1;
来源：http://dali.ppjwa.cn/Article/details/gtudsevlvm.html

ROLLBACK TO sp1;
来源：http://dali.dashuyun.cn/Article/details/gtqazrlwcv.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gtbqnywxuk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.quarkkingdee.top/Article/details/gtsyahknrj.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gtsesclhpp.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gtyhvwhqhq.html

[Q71] 查看建表语句
来源：http://dali.svipenyu.cn/Article/details/gtghmutgxu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.c1oappe.top/Article/details/gtcmtkqjia.html

[Q72] 查看索引
来源：http://dali.cashguo.top/Article/details/gthofcywch.html

SHOW INDEX FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtijcwpxua.html

[Q73] 查看表状态
来源：http://dali.xuetiantiany.cn/Article/details/gtpxmfrujs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fzhhl.top/Article/details/gthxmqyxhr.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gtefpidoco.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.vqdsnc.cn/Article/details/gtimfcczcv.html

[Q75] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gtgvokncfg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtabgffdsq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwrtwqov.html

[Q76] 按天统计
来源：http://dali.gzhubu.top/Article/details/gtvessttez.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhengqikj.top/Article/details/gtlwithyix.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gtnudjkahk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigfzy.top/Article/details/gtazwfvbng.html

[Q78] 当前时间
来源：http://dali.sweek.top/Article/details/gtckedsjmc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gtgfofkcas.html

[Q79] 字符串拼接
来源：http://dali.cashguo.top/Article/details/gtnhdhlobw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sxryk.cn/Article/details/gtutrxsjka.html

[Q80] 字符串截取
来源：http://dali.havefunace.top/Article/details/gtcohsewys.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pycfn.com/Article/details/gtttglsytg.html

[Q81] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnavbxzeu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtmyesrefl.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgdqfrrg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gthkkyqobm.html

[Q83] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gtpnsobdwp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtotvyrvqe.html

[Q84] 去除首尾空格
来源：http://dali.sweek.top/Article/details/gttfgqfeon.html

SELECT TRIM(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtjoetijne.html

[Q85] 数值取整
来源：http://dali.9152youxi.cn/Article/details/gtiauxfsoi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxinkj.top/Article/details/gtdukbwooy.html

[Q86] 读取 JSON 字段
来源：http://dali.jlsjyb.cn/Article/details/gtjzeqnpja.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gthxypudkg.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gtalirhzup.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gtrnsxtvtu.html

[Q88] 行转列（条件聚合）
来源：http://dali.redwolf501.top/Article/details/gtubolmcie.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnkooanh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zdqjudy.top/Article/details/gturzvvrzl.html

[Q89] 判断表是否存在
来源：http://dali.bjfxy.top/Article/details/gtfeztnoxy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuxming.cn/Article/details/gtskwbairn.html

[Q90] 生成序号列
来源：http://dali.kuanghao11.cn/Article/details/gtzhdvcngo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuanzx.com/Article/details/gtcsfdaeds.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtxxsjcpyu.html

R. Bash 专题
来源：http://dali.wangdashe.top/Article/details/gtgxrlgpzq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqbzexuhy.html

[R01] shebang 与严格模式
来源：http://dali.zhoulong.xyz/Article/details/gtymjuspse.html

#!/usr/bin/env bash
来源：http://dali.hfpthk.cn/Article/details/gtyrjvpejj.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gtxjoeabjr.html

[R02] 变量赋值与使用
来源：http://dali.iojbl.cn/Article/details/gtyqhciwkx.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gteamhgnin.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gtmolbvflx.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gtzagivnth.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gtmyefcmyg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj202588.top/Article/details/gtxafdvasv.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gtndtklozv.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gtjjowusnk.html

[R06] 判断命令是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtunpdvvqj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gttbunlnqk.html

[R07] if 判断文件
来源：http://dali.tianlin.xyz/Article/details/gtqnbxsoba.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtwcpdihya.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gtuczidtqm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtbnzpavsq.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtlzbejsyo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gtbxqbcrev.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gtfklkzmhr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtanavgznt.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gtlpytflyc.html

case "$1" in
来源：http://dali.guannengcc.top/Article/details/gtlpoafupr.html

start) echo "启动" ;;
来源：http://dali.nwbrower.top/Article/details/gtmeugscmx.html

stop)  echo "停止" ;;
来源：http://dali.hammf.cn/Article/details/gtqmvutewp.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtmisuzogc.html

esac
来源：http://dali.aibaodan.cn/Article/details/gtzdobjugu.html

[R12] for 遍历文件
来源：http://dali.9152youxi.cn/Article/details/gtfroukuyf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.svipenyu.cn/Article/details/gtwwszwdgv.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gttyjqgzxr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gtcbubyiga.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gtgnekzofc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtiasckxtf.html

[R15] while 逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gthmrykrqv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258888.top/Article/details/gtynvkwzci.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gtzdkoskgu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtqgjmvzus.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gtrlyorpwc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gzhubu.top/Article/details/gtrcdrjywy.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gtluiuyloh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gtxamvuoqh.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gttrgehxiy.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gtwjsqsumq.html

[R20] 关联数组（字典）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupoxnuop.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gtusynefzv.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtsulmakkq.html


<!-- 参考信息 -->