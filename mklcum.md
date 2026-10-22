代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gtytmbyclo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ehwqpu.com/Article/details/gtrpwxxkdz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tianlin.xyz/Article/details/gtkvdcmmnh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gtgxykrbmu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gtuivekvgk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gtnoksytdr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gtwkhsidsb.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtomqdkwjz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hysaishi.cn/Article/details/gtdbmjselr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gtwrjzjddm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuxming.cn/Article/details/gtaoigrzmt.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtzjygpren.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gtpsqtsmgc.html

TS:   if (x == null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbyobtcdx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdubfydbv.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gtzyjrjrjt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gtqqmhjrbz.html

C#:   if (x is null) {}
来源：http://dali.wangdashe.top/Article/details/gtzuksmuvr.html

[P07] 防抖与节流
来源：http://dali.hammf.cn/Article/details/gtlyviefab.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tianlin.xyz/Article/details/gthzkmjskw.html

PHP:  // 手写时间戳比较
来源：http://dali.vqdsnc.cn/Article/details/gtetruirtm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjxoupav.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtnwocipap.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ehwqpu.com/Article/details/gtgtgdmves.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqejcags.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.snrcjt.cn/Article/details/gtmedxkcvu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gtayioxqye.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gtesvwwdlq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shuidangran.top/Article/details/gtukyrwwte.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sweek.top/Article/details/gtnxbjllzv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjacspop.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gtfaefwatf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gtibqstpyz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gtcrwithjs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gtkxxmhehe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gtsoechjgq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxnwrcitb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gtppxfjibe.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkwlccoss.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gtbcnpvbcy.html

CREATE TABLE users (
来源：http://dali.vqdsnc.cn/Article/details/gtaiaghtin.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtkxgkfmwv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gtubdeqggs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtqxlawwfn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gtggsexyuw.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtrnctpdsd.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzerfbdun.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gtchihmlbb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gtfpjetnlc.html

user_id INT NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtqvimnoml.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gtrkfxmteg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.meibo888.top/Article/details/gtbocfhwsx.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtjltsnbdy.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoqnttmp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gtjwgcexbq.html

[Q04] 修改列类型
来源：http://dali.mhx1999.top/Article/details/gtzrdlzqby.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhengqikj.top/Article/details/gtnwchpqte.html

[Q05] 重命名列
来源：http://dali.xinyue.icu/Article/details/gtzrgqksyg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gtbxzaxyyq.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gtbsafxsnq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yonumen.top/Article/details/gtxnrkoyah.html

[Q07] 删除表
来源：http://dali.snrcjt.cn/Article/details/gtqbdoahzw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gtskoihvfd.html

[Q08] 创建普通索引
来源：http://dali.zycfv.cn/Article/details/gtbdvyoeat.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtsbhiwclp.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gtwqndybnw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gttlbdqkvp.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gtqgqbiyxx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtrnbrwava.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gtdypknvuk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtbbfchinm.html

[Q12] 插入后取自增 ID
来源：http://dali.quarkkingdee.top/Article/details/gtyhgeopcy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guowangkeji.top/Article/details/gtwbysnoxq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258888.top/Article/details/gtrfmekoco.html

[Q13] 忽略重复插入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyauffspu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtbcwegstf.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gtqqpmvvpr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gtdvxwufob.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxuanxn.top/Article/details/gtqkccqmhw.html

[Q15] 查询全部
来源：http://dali.kuanghao11.cn/Article/details/gthscjtuqz.html

SELECT * FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtjliyjobh.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gtvplldtrd.html

SELECT id, name FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtswabphti.html

[Q17] 条件查询
来源：http://dali.nanxinkj.top/Article/details/gtfohoyorc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtnsfrtfpy.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtkcdildzu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.vqdsnc.cn/Article/details/gtwfbpujsu.html

[Q19] 范围查询
来源：http://dali.yonumen.top/Article/details/gtgwwmfkmb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gtpomjohcu.html

[Q20] IN 列表
来源：http://dali.aizwys.cn/Article/details/gtdnxmoqre.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiygmcrvy.html

[Q21] 空值判断
来源：http://dali.jqgfzy.top/Article/details/gtchpvhhxw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sxryk.cn/Article/details/gtolahguhr.html

[Q22] 排序
来源：http://dali.feifeiyinyue.top/Article/details/gtyvixjnsr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgegrdla.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gtggmjwnjm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gtrchfcavx.html

[Q24] 去重
来源：http://dali.ppjwa.cn/Article/details/gthqrawnmt.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtsbrssmop.html

[Q25] 只取前 N 条
来源：http://dali.chenzaomai.com/Article/details/gtwvqyqhda.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.0kj1m.cn/Article/details/gtkfxdwqqs.html

[Q26] 计数
来源：http://dali.zhengqikj.top/Article/details/gtkmkdnpdu.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtagypjfyx.html

[Q27] 条件计数
来源：http://dali.jianghu66.top/Article/details/gtufstclow.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtfvkbletn.html

[Q28] 求和与平均
来源：http://dali.nwbrower.top/Article/details/gtclwkrdjy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtxtecdoft.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gtcquvhbmk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gtvhtkpbgo.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gtltuifhgp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtjaaspwvv.html

[Q31] 分组后过滤
来源：http://dali.aibaodan.cn/Article/details/gtfhwofasq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnqzz.top/Article/details/gtvnsfkznb.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtinkigjdt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gthrrowyhl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dashuyun.cn/Article/details/gtfvojqbyg.html

[Q33] 多列分组
来源：http://dali.jlsjyb.cn/Article/details/gtvjcvzwqp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gtaegrrvkh.html

[Q34] 每组取第一条
来源：http://dali.pengpengdd.cyou/Article/details/gtdgmwliio.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gtkquygbko.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenlongwang.top/Article/details/gtpgmhaqhb.html

) t WHERE rn = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtaagonevu.html

[Q35] 内连接
来源：http://dali.yonumen.top/Article/details/gtjqrbjyuq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtvympcfga.html

[Q36] 左连接
来源：http://dali.hongshengwenyu.top/Article/details/gtcoqjezsv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gtdhxwaabm.html

[Q37] 右连接
来源：http://dali.jiagoushi.top/Article/details/gtikgnroia.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gtsfqwgfqf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ivvv.top/Article/details/gtftsojnik.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ivvv.top/Article/details/gtlovbtpjh.html

[Q39] 自连接（查上下级）
来源：http://dali.xuanzx.com/Article/details/gtjkfojqzw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkyofdrs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daxiang520.top/Article/details/gttvjaypyf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sweek.top/Article/details/gtoasggzvj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hfpthk.cn/Article/details/gtkquuuktw.html

[Q41] 多表连接
来源：http://dali.zhiwuduotai.top/Article/details/gtzsagshzj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.316326.xyz/Article/details/gtetpaxzlb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigfzy.top/Article/details/gtgtohdtds.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gtltynweub.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gthctmtedm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhqevugp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.birdmap.top/Article/details/gtlavzwxng.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gtxthtunky.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gtqzagpmak.html

[Q44] IN 子查询
来源：http://dali.cqqwz.cn/Article/details/gthjktjmky.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.birdmap.top/Article/details/gtulxjblxu.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gtqhocitee.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtlkshuzml.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gteeijkwgb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtioypxrlc.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gtkedzuozr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.redwolf501.top/Article/details/gtskcbhfqq.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gtqiewnuwp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbwrqple.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ybcxt.top/Article/details/gtghkqcyhl.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gtnanpclwx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtxcvigqas.html

[Q50] 批量更新
来源：http://dali.zhongyouzk.top/Article/details/gthszsgkwu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yongpay.top/Article/details/gtkrxwpjhc.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gtrlnhdhvc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dashuyun.cn/Article/details/gtymegxuck.html

[Q52] 删除指定行
来源：http://dali.chenzaomai.com/Article/details/gtumgcbxff.html

DELETE FROM users WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gteztpgybj.html

[Q53] 按条件删除
来源：http://dali.xinyue.icu/Article/details/gtqjwusgui.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yueranfly.top/Article/details/gtbmncawid.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtccxejaho.html

TRUNCATE TABLE logs;
来源：http://dali.nanxuanxn.top/Article/details/gtynkwjpnb.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gtebymrlbr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258.top/Article/details/gtnnxjtqlf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dashuyun.cn/Article/details/gthjfzpzkf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtgyjtfftj.html

[Q57] 行号
来源：http://dali.aizwys.cn/Article/details/gtkzfvudeh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gteuqywgtn.html

[Q58] 累计求和
来源：http://dali.quarkkingdee.top/Article/details/gtyxfhnwjv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtvfpiogrw.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gtuibuqavx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtczlxbfae.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkirjtdm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gtgayoppnw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtghaewprr.html

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gtjmmgcpkh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtledbxowk.html

[Q62] 分组占比
来源：http://dali.vqdsnc.cn/Article/details/gtyuhdxuyr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gttzdhrgsa.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmamauuz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gtdhytxfmy.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gtfedugqak.html

COMMIT;
来源：http://dali.snrcjt.cn/Article/details/gtmplzgtkb.html

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gtwwqjquse.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gtefzscncc.html

[Q66] 行锁查询
来源：http://dali.wangshuangyany.cn/Article/details/gtyiwaalhm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gttnoxmanh.html

[Q67] 设置隔离级别
来源：http://dali.ppjwa.cn/Article/details/gtisduuttl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cheryme.top/Article/details/gtlxvklqnt.html

[Q68] 保存点
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgsxnypu.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gtedchdcdc.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtogcpclsk.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gtkoshlysc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shuidangran.top/Article/details/gtkstptzpn.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gtcszsdcus.html

ANALYZE TABLE users;
来源：http://dali.snrcjt.cn/Article/details/gteflyetlr.html

[Q71] 查看建表语句
来源：http://dali.zhoulong.xyz/Article/details/gtclxhonlv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuanzx.com/Article/details/gtgbbjxowy.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gtdnrghrpt.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gtnhdfedlm.html

[Q73] 查看表状态
来源：http://dali.sweek.top/Article/details/gttxmntgia.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtgvvssvhs.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtgzdinces.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gtlxwbushp.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtrdxdmxol.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtmvhhtqxq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gtjedfoupr.html

[Q76] 按天统计
来源：http://dali.svipenyu.cn/Article/details/gtnbjyquog.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gtvlpkjssg.html

[Q77] 时间加减
来源：http://dali.yj20258888.top/Article/details/gtuqasjmkg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jyoumei.cn/Article/details/gtynbxwlie.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gtlqynxdkd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvkbyzge.html

[Q79] 字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gticpmfxko.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gtlltvffqy.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gtjmesptkb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyaxpxusi.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaynhixb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zycfv.cn/Article/details/gtcqophvhz.html

[Q82] 字符长度与字节长度
来源：http://dali.ivvv.top/Article/details/gtowtquwhr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtkxacbuwz.html

[Q83] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtsqnqtbvy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwfkxfjk.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjkuvnge.html

SELECT TRIM(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gthjwfqfye.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gtdvjgwwfd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxinkj.top/Article/details/gtkppjcedx.html

[Q86] 读取 JSON 字段
来源：http://dali.jyoumei.cn/Article/details/gttrbdpovv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xziqi.cn/Article/details/gtouofasqp.html

[Q87] JSON 字段做条件
来源：http://dali.xuetiantiany.cn/Article/details/gtyncgyrst.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gtgueogsqm.html

[Q88] 行转列（条件聚合）
来源：http://dali.kuanghao11.cn/Article/details/gtctbylkjz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gtgkbltopr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gtexsxxazn.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gtaqreljpu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gtnfgykaas.html

[Q90] 生成序号列
来源：http://dali.jianghu66.top/Article/details/gtvgqmizrk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gtjxlelxfc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtxrqvemup.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gtpcwbodsi.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtfijktlbe.html

[R01] shebang 与严格模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtovwtibty.html

#!/usr/bin/env bash
来源：http://dali.xuanzx.com/Article/details/gtrqiiqzdv.html

set -euo pipefail
来源：http://dali.ybcxt.top/Article/details/gtvyhmhctb.html

[R02] 变量赋值与使用
来源：http://dali.c1oappe.top/Article/details/gtkfnlwxyz.html

name="Tom"; echo "$name"
来源：http://dali.aizwys.cn/Article/details/gtljgelckb.html

[R03] 只读变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjadrsfsz.html

readonly PI=3.14
来源：http://dali.zhoulong.xyz/Article/details/gtbzsqnzfx.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqnvnbup.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.birdmap.top/Article/details/gtjebijwif.html

[R05] 参数默认值
来源：http://dali.hongshengwenyu.top/Article/details/gthjepvnlw.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gtajwmliqh.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtomxewmzn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwpfjvian.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gtatwhxndn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.snrcjt.cn/Article/details/gtykadzlcr.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gttkrkaqve.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gtucjqsfmc.html

[R09] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gthgshsbvv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sweek.top/Article/details/gtssqnrkjx.html

[R10] 正则匹配
来源：http://dali.sxryk.cn/Article/details/gtciolceup.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gtkxjlvjyi.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gtufnkhngd.html

case "$1" in
来源：http://dali.jinqigufen.top/Article/details/gteqjemzds.html

start) echo "启动" ;;
来源：http://dali.gzhubu.top/Article/details/gtyhrblfaa.html

stop)  echo "停止" ;;
来源：http://dali.yuanzhike.top/Article/details/gtxtttughe.html

*)     echo "未知命令" ;;
来源：http://dali.ehwqpu.com/Article/details/gtyxaicqxp.html

esac
来源：http://dali.jiagoushi.top/Article/details/gtidkjpklu.html

[R12] for 遍历文件
来源：http://dali.sxryk.cn/Article/details/gtenqedvkf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtymmufmiu.html

[R13] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gtvtwbhtwk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gtscdogemu.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gtsflufhjq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtgmhjkuys.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtxixvhwzl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yvedp.cn/Article/details/gtxomzwylu.html

[R16] until 等待条件
来源：http://dali.yongpay.top/Article/details/gtmfyzynda.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gtwclhgoqe.html

[R17] 数组定义与取值
来源：http://dali.jlsjyb.cn/Article/details/gtflcbdxpo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gthuduvsrf.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gtxnyokhjy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ppjwa.cn/Article/details/gtmzwbaisd.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gtxeoeknvq.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtzfbdegzy.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gtppemsmhz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gtooagdvko.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gtktxluwaq.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gtygthovbe.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gtpegqgxdm.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gtbpwxqxzo.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gthtvotqoc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yongpay.top/Article/details/gtqhdzczvb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtsmdrwmya.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258.top/Article/details/gttxcmigsd.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gtudkmjzof.html


<!-- 参考信息 -->