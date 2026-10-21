代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtrgewfqro.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gtqkbboldo.html

Ruby: x.length;  x.size
来源：http://dali.yueranfly.top/Article/details/gtmepkezpt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtcamiqomc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guannengcc.top/Article/details/gtojjikrvp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gtuemskliq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ydzc1.top/Article/details/gtxkmlxsry.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gtbwaibdsd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtrzhbltav.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gtfiihifem.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtefhhwszq.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtxjttlbup.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj202588.top/Article/details/gtecgflatm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pycfn.com/Article/details/gtkspdrvpu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gtjjqkjovi.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gtbucgtoke.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.quarkkingdee.top/Article/details/gtxuvqxvbg.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gtfgtqivmx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtehxlqduz.html

Go:   if x == nil {}
来源：http://dali.sysykeji.top/Article/details/gthsanlgij.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj202588.top/Article/details/gtiwlsuedb.html

C#:   if (x is null) {}
来源：http://dali.quarkkingdee.top/Article/details/gtuuqfuudn.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gtqczenbzz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gtrtfjyijc.html

PHP:  // 手写时间戳比较
来源：http://dali.iojbl.cn/Article/details/gtibsurwku.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtedyozijb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtvcfcjcey.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hysaishi.cn/Article/details/gtwxsyifig.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ppjwa.cn/Article/details/gtkadjvgty.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gtqfcdvwyf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gtrglzznjz.html

[P08] 处理浮点精度问题
来源：http://dali.yongpay.top/Article/details/gthbkoasay.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gotoacloud.top/Article/details/gtkmwgxshh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gtsceohrkq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.316326.xyz/Article/details/gtwbphodzx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtcqrnswgs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.9152youxi.cn/Article/details/gtqwfazzar.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gogol.net.cn/Article/details/gtujymemcq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sysykeji.top/Article/details/gtgmslcicj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xinyue.icu/Article/details/gtnzccyudu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtrvayiohf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tian-w.cn/Article/details/gtkfhewwlb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxljllnkm.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gtpcrexbdb.html

CREATE TABLE users (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvwsxbda.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtztpxypzs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtgldcsypx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258888.top/Article/details/gtfevmjijs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shuidangran.top/Article/details/gtviwmnbgr.html

);
来源：http://dali.meibo888.top/Article/details/gthfwcendw.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gtjxgatwod.html

CREATE TABLE orders (
来源：http://dali.9152youxi.cn/Article/details/gtbiowlqni.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gtzrysawtg.html

user_id INT NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkhhqzzk.html

amount DECIMAL(10, 2),
来源：http://dali.wangshuangyany.cn/Article/details/gtwckcovhu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gtzwvwaukh.html

);
来源：http://dali.yj20258888.top/Article/details/gtxhgzwodl.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gtpaizikxa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gtecvpyuke.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gtjqgmnqet.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aizwys.cn/Article/details/gtjwsguavf.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gtbcoptyig.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gtckqnukvc.html

[Q06] 删除列
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhkzvkqy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gaohongyu789.top/Article/details/gtmbkqlebi.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gtedkbkysb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gtbmppeqte.html

[Q08] 创建普通索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyeyrpgk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtsaofldhc.html

[Q09] 创建唯一索引
来源：http://dali.zdqjudy.top/Article/details/gtmbzixaue.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtvxrhwxzj.html

[Q10] 插入单行
来源：http://dali.yonumen.top/Article/details/gtwemxgauj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gtuqgwsdhx.html

[Q11] 一次插入多行
来源：http://dali.yvedp.cn/Article/details/gtdxslgwlp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtbuyiudka.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlmvrfze.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhiwuduotai.top/Article/details/gtombkqyth.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gttjhipgxa.html

[Q13] 忽略重复插入
来源：http://dali.pengpengdd.cyou/Article/details/gtbppwdtba.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtkqhxwdbv.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gthwszbums.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.quarkkingdee.top/Article/details/gtepwykefe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jianghu66.top/Article/details/gtqphocwtn.html

[Q15] 查询全部
来源：http://dali.jyoumei.cn/Article/details/gtmhburmru.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtcndpcvxj.html

[Q16] 查询指定列
来源：http://dali.kuanghao11.cn/Article/details/gtkuckqydh.html

SELECT id, name FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtzmrqrxoi.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gttrmonpab.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gtpbgporze.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gteectkwfb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yvedp.cn/Article/details/gtfkzcqpvo.html

[Q19] 范围查询
来源：http://dali.xylfe.cn/Article/details/gtjoamgcqk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gtrtmonqte.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gtiyegfrzg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gtskgwmixb.html

[Q21] 空值判断
来源：http://dali.xylfe.cn/Article/details/gtxhobyvei.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.meibo888.top/Article/details/gtrlihmnac.html

[Q22] 排序
来源：http://dali.gotoacloud.top/Article/details/gtxqxkqgrq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gthjxjswuk.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gtrrybzwsw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.redwolf501.top/Article/details/gtnamfyrku.html

[Q24] 去重
来源：http://dali.snrcjt.cn/Article/details/gtgfnubszg.html

SELECT DISTINCT city FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gthbzzcpep.html

[Q25] 只取前 N 条
来源：http://dali.xuanzx.com/Article/details/gtaniecxup.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuanzx.com/Article/details/gtklhyaxty.html

[Q26] 计数
来源：http://dali.sufxvd.cn/Article/details/gtbvpndlbg.html

SELECT COUNT(*) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtxilfzzyx.html

[Q27] 条件计数
来源：http://dali.jlsjyb.cn/Article/details/gthnonhike.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtnegsoevj.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gtcerjdnwd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtxkxluxne.html

[Q29] 最大最小值
来源：http://dali.dashuyun.cn/Article/details/gtdjgnaxwd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtahuvzzqy.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gtzntveofr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtziqzljma.html

[Q31] 分组后过滤
来源：http://dali.cashguo.top/Article/details/gtlhtflsuk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guannengcc.top/Article/details/gtfoimowaq.html

[Q32] 分组拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtdqicqrpu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtccguotkx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gaohongyu789.top/Article/details/gtkfjclono.html

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gtoxrjxkya.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gtwcjuvknb.html

[Q34] 每组取第一条
来源：http://dali.aibaodan.cn/Article/details/gtiqdcffcd.html

SELECT * FROM (
来源：http://dali.jyoumei.cn/Article/details/gtpaaarjbe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258.top/Article/details/gtqzfgnzdn.html

) t WHERE rn = 1;
来源：http://dali.meibo888.top/Article/details/gtfgnfekqo.html

[Q35] 内连接
来源：http://dali.guowangkeji.top/Article/details/gtpblgejxp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtuyxtngql.html

[Q36] 左连接
来源：http://dali.cucudq.cn/Article/details/gtihlovjor.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gttvhwieyl.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gttjycilax.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphtnadsv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgfzy.top/Article/details/gtysldomah.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fengsongda.top/Article/details/gtpvfenepf.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigfzy.top/Article/details/gtdygtknmt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gtlljoalkr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.mhx1999.top/Article/details/gttsxvpzze.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangdashe.top/Article/details/gtxjgmrbyq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuxming.cn/Article/details/gtlvmzlqnv.html

[Q41] 多表连接
来源：http://dali.kuanghao11.cn/Article/details/gtmibniaau.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtqmdirlod.html

JOIN users u ON u.id = o.user_id
来源：http://dali.c1oappe.top/Article/details/gtyxscwsgk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtutjglwwr.html

[Q42] 连接条件附加过滤
来源：http://dali.dashuyun.cn/Article/details/gthmkpqaye.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhoulong.xyz/Article/details/gtmnhbhohk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gtmcqclxdm.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gtgjxlqrgk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sweek.top/Article/details/gtnhheexjt.html

[Q44] IN 子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbeljbqqe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daxiang520.top/Article/details/gtoxswejco.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gtyevqzkkg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtxrmatgif.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hammf.cn/Article/details/gtavyouwok.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtotedvrcg.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gtpejahscr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yangfankeji.com/Article/details/gtcnnuvavp.html

[Q48] CTE 公用表表达式
来源：http://dali.svipenyu.cn/Article/details/gtdtipagch.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.snrcjt.cn/Article/details/gtmvxwjukv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.havefunace.top/Article/details/gthenhvlme.html

[Q49] 更新单行
来源：http://dali.jlsjyb.cn/Article/details/gtblttzshw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtyfscepcf.html

[Q50] 批量更新
来源：http://dali.chenlongwang.top/Article/details/gtftrvykaj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gtyqzcxlul.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gtdfgmlfkg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtmzpqfmxf.html

[Q52] 删除指定行
来源：http://dali.sxryk.cn/Article/details/gtjakyqctc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtgzijkqfp.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqfcrjma.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtmwgxisxu.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gthhevigrd.html

TRUNCATE TABLE logs;
来源：http://dali.chenzaomai.com/Article/details/gtreasccql.html

[Q55] 排名（并列占位）
来源：http://dali.kuanghao11.cn/Article/details/gtwxteepll.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtkcevzlwq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.kuanghao11.cn/Article/details/gtnbxwctfa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gthpqazpgx.html

[Q57] 行号
来源：http://dali.birdmap.top/Article/details/gtdpyagyxl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.c1oappe.top/Article/details/gtkneoxazs.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gtfadblkzs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtbaielwgu.html

[Q59] 分组内累计
来源：http://dali.bjfxy.top/Article/details/gticvfpiwe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtseekifiq.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnxiangtu.top/Article/details/gthnwsblom.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhoulong.xyz/Article/details/gtijsjaxyd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtbvzrtwgh.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gtkdfbmcqv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtlmwukvtx.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gtytmmzqcv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtqzjntcly.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gtcsbydfbq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gtdvsbiugy.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gtjyxhwxtg.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gtuclhnakd.html

[Q65] 回滚事务
来源：http://dali.yonumen.top/Article/details/gtehfgnmzs.html

ROLLBACK;
来源：http://dali.yonumen.top/Article/details/gtuvilyfjd.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gtxsljjmxh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cashguo.top/Article/details/gtsxdlmpiv.html

[Q67] 设置隔离级别
来源：http://dali.hongshengwenyu.top/Article/details/gtcjtylknw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258888.top/Article/details/gtozjduhii.html

[Q68] 保存点
来源：http://dali.xziqi.cn/Article/details/gtaflhdjmt.html

SAVEPOINT sp1;
来源：http://dali.xinyue.icu/Article/details/gthndydfke.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gtddbzwqxj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gtnxjkjdlo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xylfe.cn/Article/details/gtpukgvqsl.html

[Q70] 更新统计信息
来源：http://dali.andypj.xyz/Article/details/gtdofsgeup.html

ANALYZE TABLE users;
来源：http://dali.gogol.net.cn/Article/details/gtltltyrnx.html

[Q71] 查看建表语句
来源：http://dali.hfpthk.cn/Article/details/gtoqwcyafy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gtmbatiimj.html

[Q72] 查看索引
来源：http://dali.tian-w.cn/Article/details/gtrmlhlivr.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtqauyetps.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gtajzkjcmh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.vqdsnc.cn/Article/details/gtmjifpymz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gtayqpuhkz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.feifeiyinyue.top/Article/details/gtbqqinszy.html

[Q75] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtcpwoxmyk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtnfomlwyh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gtkonprsrw.html

[Q76] 按天统计
来源：http://dali.dianchejie.cn/Article/details/gtzbhkinau.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj202588.top/Article/details/gtewnjxfib.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gtrtmrlqrl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotwwclku.html

[Q78] 当前时间
来源：http://dali.zhengqikj.top/Article/details/gtvibekayp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gtouoiyfhy.html

[Q79] 字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gtrifjacyi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gtzcggqend.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gteppliuhw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtzqsazbzi.html

[Q81] 字符串替换
来源：http://dali.yj202588.top/Article/details/gtthpxybqv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangdashe.top/Article/details/gtfauzjqrb.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gtybgrdcbr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtxhrrrqly.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtlkpfnsrj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzryxibw.html

[Q84] 去除首尾空格
来源：http://dali.daxiang520.top/Article/details/gtybyjzexw.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwufcogya.html

[Q85] 数值取整
来源：http://dali.jyoumei.cn/Article/details/gtclzgpdmk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gtsanjkeok.html

[Q86] 读取 JSON 字段
来源：http://dali.shangyingyoupin.top/Article/details/gtlvgqsvea.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gtxccjpwdn.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gtktgheoqq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmenjnard.html

[Q88] 行转列（条件聚合）
来源：http://dali.ivvv.top/Article/details/gtaiaasgvd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jlsjyb.cn/Article/details/gtejhtgpnx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gthezaelwf.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gtyaethsci.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.iojbl.cn/Article/details/gtenridojf.html

[Q90] 生成序号列
来源：http://dali.cdnleiting.top/Article/details/gtjvykmvgn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gtzuvidxie.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthnbvvakm.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtuqwzqhwn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmnvkybcj.html

[R01] shebang 与严格模式
来源：http://dali.yonumen.top/Article/details/gtmukqfepr.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gtadswdstz.html

set -euo pipefail
来源：http://dali.c1oappe.top/Article/details/gtfidzgzhy.html

[R02] 变量赋值与使用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnodqchqe.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gtbxbareja.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gtojwhqzed.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gtzrpdoetr.html

[R04] 位置参数
来源：http://dali.aibaodan.cn/Article/details/gttgqwpubm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xinyue.icu/Article/details/gthebprzom.html

[R05] 参数默认值
来源：http://dali.tianlin.xyz/Article/details/gtdyxvegad.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gtgqttlhrj.html

[R06] 判断命令是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtspccngls.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gthqaknwuj.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpqtfoxr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtdbdpuecq.html

[R08] 数值比较
来源：http://dali.shuidangran.top/Article/details/gtiswpsuxu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangdashe.top/Article/details/gtkbshpzkl.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gtxfpecmaq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gthceypudc.html

[R10] 正则匹配
来源：http://dali.shzxlz.cn/Article/details/gttfwslhdn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gttiuagxhh.html

[R11] case 多分支
来源：http://dali.9152youxi.cn/Article/details/gtgiukszdl.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvzceeto.html

start) echo "启动" ;;
来源：http://dali.hfpthk.cn/Article/details/gtkjvvhexp.html

stop)  echo "停止" ;;
来源：http://dali.hammf.cn/Article/details/gtcezlniyh.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtavuzkbec.html

esac
来源：http://dali.xziqi.cn/Article/details/gttztnhdhr.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtbbrvxjka.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gtxqedssgb.html

[R13] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gtmuzzvtcb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtdikrcslq.html

[R14] C 风格 for
来源：http://dali.feifeiyinyue.top/Article/details/gtaqkjzksw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gtcmnxpmhz.html

[R15] while 逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gttqhybqry.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gtjsjntzyd.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gtlqmcrlxi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtsidhqgic.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikibzjbg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gtihfoehfl.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtfdeadofs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xziqi.cn/Article/details/gtluwibkxv.html

[R19] 数组长度
来源：http://dali.ybcxt.top/Article/details/gthydnypvn.html

echo "${#arr[@]}"
来源：http://dali.nwbrower.top/Article/details/gtxxvxajxa.html

[R20] 关联数组（字典）
来源：http://dali.yj20258.top/Article/details/gtcyxhlxlc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gtzggfrotx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtownqamxk.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gtrkfcrgjr.html

[R22] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtecvnqqfb.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gtwvuoaqmj.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtsdxhyrfl.html


<!-- 参考信息 -->