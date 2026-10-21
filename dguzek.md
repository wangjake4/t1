代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gtmcponjkx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtjvpqzmzp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtqhbrdvuv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfqspshg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtjtizawdc.html

Go:   len(arr);  len(m)
来源：http://dali.c1oappe.top/Article/details/gtsdxrchby.html

Ruby: x.length;  x.size
来源：http://dali.shzxlz.cn/Article/details/gtarzttbbd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zycfv.cn/Article/details/gthgwqozad.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigfzy.top/Article/details/gtrvmnobwv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ydzc1.top/Article/details/gtzviyaunb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gtjrdgfaeh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gtfaebpbuw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gtomijinwh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gtbjsdpwck.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkabkfev.html

Ruby: a == b
来源：http://dali.hammf.cn/Article/details/gtlrlehzmm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.smart0.xyz/Article/details/gtwuqrsedg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.svipenyu.cn/Article/details/gtiyyimmlo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yvedp.cn/Article/details/gtdsmweskq.html

PHP:  if (empty($x)) {}
来源：http://dali.pycfn.com/Article/details/gtleoerune.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aibaodan.cn/Article/details/gthstoroes.html

TS:   if (x == null) {}
来源：http://dali.gzhubu.top/Article/details/gtownhfkul.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gtuoexfujy.html

Go:   if x == nil {}
来源：http://dali.jqgufenzy.top/Article/details/gthjhprclj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gttgusozvy.html

C#:   if (x is null) {}
来源：http://dali.zdqjudy.top/Article/details/gtkclepdlt.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gtrguulefr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cucudq.cn/Article/details/gtwwwgvbkk.html

PHP:  // 手写时间戳比较
来源：http://dali.jiagoushi.top/Article/details/gtmuajbbzw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtejnglfok.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtoicozryp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxnniqjj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.kuanghao11.cn/Article/details/gtuaqfxbaw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guannengcc.top/Article/details/gtnbdbhdcz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gtctrbjwcz.html

[P08] 处理浮点精度问题
来源：http://dali.tanke756.top/Article/details/gtwvymzefk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cheryme.top/Article/details/gtezyhmofa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtaaqgfzpu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhongyouzk.top/Article/details/gtquefxguc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gtlegnfbxh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.haohaochexian.top/Article/details/gtbmtsnako.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hywenlv.cn/Article/details/gtnknohdkm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gzhubu.top/Article/details/gtkjjosvss.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xinyue.icu/Article/details/gttjocfnoq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnokrxodc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovxupdtd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtndkoxpdt.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gtxzayidsi.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gtojwrirgn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtqygvhfop.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtjrasapev.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shangyingyoupin.top/Article/details/gthlwtkbmu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmckioqrc.html

);
来源：http://dali.jinqigfzy.top/Article/details/gteaihcgdv.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gtoxrcixfm.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtumudhisg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtlkjczufy.html

user_id INT NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtyjbxqovx.html

amount DECIMAL(10, 2),
来源：http://dali.gogol.net.cn/Article/details/gthazwsauo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuifkggky.html

);
来源：http://dali.fzhhl.top/Article/details/gtfxtlamqe.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gtujkrwxli.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yangfankeji.com/Article/details/gtsicephuf.html

[Q04] 修改列类型
来源：http://dali.sxryk.cn/Article/details/gtttaiyfeo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gtrwdzcaet.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gtlwtiaung.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xziqi.cn/Article/details/gtkclmykrm.html

[Q06] 删除列
来源：http://dali.birdmap.top/Article/details/gtmmjpgbve.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gtgpmyhzxu.html

[Q07] 删除表
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxrtrfmr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ehwqpu.com/Article/details/gtfznvkjaw.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gtgggmylup.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtmjpoiszn.html

[Q09] 创建唯一索引
来源：http://dali.yuanzhike.top/Article/details/gtstrblrud.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbfbkkxr.html

[Q10] 插入单行
来源：http://dali.yj20258.top/Article/details/gtvaeedoct.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yonumen.top/Article/details/gtqgunbtbo.html

[Q11] 一次插入多行
来源：http://dali.zhoulong.xyz/Article/details/gtknhkhcsw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.redwolf501.top/Article/details/gthwmpgdfd.html

[Q12] 插入后取自增 ID
来源：http://dali.tanke756.top/Article/details/gtbitufxxg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hfpthk.cn/Article/details/gtsoodqrro.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangkeji.top/Article/details/gterfwvdku.html

[Q13] 忽略重复插入
来源：http://dali.meibo888.top/Article/details/gtjdcwbuny.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtzjznaisf.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunuzbsns.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtbjoprwok.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cdnleiting.top/Article/details/gtuqfpnypf.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gtylgagcqu.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtksgeskan.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gteiovkixt.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gtwlqyskfe.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gtebdqzwya.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tianlin.xyz/Article/details/gtdpidjymc.html

[Q18] 模糊匹配
来源：http://dali.quarkkingdee.top/Article/details/gtkuiioeqv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgufenzy.top/Article/details/gtfpusutpn.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gthrroyhux.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tian-w.cn/Article/details/gtmghhapzq.html

[Q20] IN 列表
来源：http://dali.ivvv.top/Article/details/gtvtramvkk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jyoumei.cn/Article/details/gtayxbmitb.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gtofujmblk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258.top/Article/details/gtdnrpsyxg.html

[Q22] 排序
来源：http://dali.xylfe.cn/Article/details/gtcuwwdgjv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tianlin.xyz/Article/details/gtdnsihpzm.html

[Q23] 分页
来源：http://dali.xziqi.cn/Article/details/gtmfcgvuvc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtdxcknlfr.html

[Q24] 去重
来源：http://dali.smart0.xyz/Article/details/gtlizzjiyr.html

SELECT DISTINCT city FROM users;
来源：http://dali.pycfn.com/Article/details/gtnepzompp.html

[Q25] 只取前 N 条
来源：http://dali.redwolf501.top/Article/details/gtwphollzw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gtgrdkhrfd.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gtkdngykuf.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtpizyvfsw.html

[Q27] 条件计数
来源：http://dali.jyoumei.cn/Article/details/gtfwomxxrh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkziinlye.html

[Q28] 求和与平均
来源：http://dali.jyoumei.cn/Article/details/gtiokcogwe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gttyyyyepo.html

[Q29] 最大最小值
来源：http://dali.zhengqikj.top/Article/details/gtcbnvjprq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqgoctzt.html

[Q30] 分组统计
来源：http://dali.sysykeji.top/Article/details/gtknrbyjqn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtxsmzxxaa.html

[Q31] 分组后过滤
来源：http://dali.0kj1m.cn/Article/details/gtwmatidwb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ivvv.top/Article/details/gtnjoaobhb.html

[Q32] 分组拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtirwfpfxw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtobnhaaeb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gtrelneawa.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gtzqvemhhq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gtjmjbetvl.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrldqvin.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gtgghgmjgd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hfpthk.cn/Article/details/gtfdkqevrp.html

) t WHERE rn = 1;
来源：http://dali.yongpay.top/Article/details/gtagijmwyw.html

[Q35] 内连接
来源：http://dali.316326.xyz/Article/details/gtkjlybrjd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtsyhikzaf.html

[Q36] 左连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkdwsbql.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtfkxtwhez.html

[Q37] 右连接
来源：http://dali.yuxming.cn/Article/details/gtjrvsrdms.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gtmmuwlyiz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gtxmjcupkz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhixingplan.top/Article/details/gtylaxgspt.html

[Q39] 自连接（查上下级）
来源：http://dali.hysaishi.cn/Article/details/gtqhjqyplm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yonumen.top/Article/details/gtuotynzrr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daxiang520.top/Article/details/gtvyzwwizd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cheryme.top/Article/details/gtjrfrbmer.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhengqikj.top/Article/details/gtytlxllti.html

[Q41] 多表连接
来源：http://dali.zhixingplan.top/Article/details/gthrvqpaax.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yueranfly.top/Article/details/gtyqulpmqf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gteyyripwe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gtiwczorcj.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gtmuapejes.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aibaodan.cn/Article/details/gtvbaakcpq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohqlxnla.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gtmufznhcm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gtpoziqjba.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gtoivcngqe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgufenzy.top/Article/details/gtnkgguzfz.html

[Q45] EXISTS 判断存在
来源：http://dali.bjfxy.top/Article/details/gttkvivklo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtjdmazljv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daxiang520.top/Article/details/gtoulsigiv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtnhojapzg.html

[Q47] 与平均值比较
来源：http://dali.yanxiufei.cn/Article/details/gtqvcegckg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuanzx.com/Article/details/gtckrljbie.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gtebsbexsi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gtupbgcupv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cashguo.top/Article/details/gtqpubiafw.html

[Q49] 更新单行
来源：http://dali.jiagoushi.top/Article/details/gtkohdfeix.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtottmwuji.html

[Q50] 批量更新
来源：http://dali.shuidangran.top/Article/details/gtwvfpguzw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gtglkgzkav.html

[Q51] 用子查询更新
来源：http://dali.hammf.cn/Article/details/gtzbmlyxcr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmdoorox.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gtjlwvhhcf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtqeaezrae.html

[Q53] 按条件删除
来源：http://dali.yj20258.top/Article/details/gthomulegv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtgedxwjfa.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtaxsooncv.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gtmfyxthxt.html

[Q55] 排名（并列占位）
来源：http://dali.sxryk.cn/Article/details/gtyqvjaxch.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gtzwsqssbf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gotoacloud.top/Article/details/gtfixjssea.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zycfv.cn/Article/details/gtrrmwdnkv.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gtpjegnhho.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtazdwflid.html

[Q58] 累计求和
来源：http://dali.0kj1m.cn/Article/details/gtfvqdkoff.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtxfudtgki.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gttepeyger.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtnvrknxlg.html

[Q60] 取上一行 / 下一行
来源：http://dali.dianchejie.cn/Article/details/gtbgwnnuhh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hywenlv.cn/Article/details/gtjuqbtykg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.meibo888.top/Article/details/gtecixsejx.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gtwodrhlhs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtsortgffy.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gtfielrbbv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtmhqesyfr.html

[Q63] 开启事务
来源：http://dali.hfpthk.cn/Article/details/gtndqdkcye.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aibaodan.cn/Article/details/gtiudjlpvy.html

[Q64] 提交事务
来源：http://dali.gotoacloud.top/Article/details/gtolujwdku.html

COMMIT;
来源：http://dali.cheryme.top/Article/details/gtlydlplhu.html

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gthlvqbhyz.html

ROLLBACK;
来源：http://dali.zhiwuduotai.top/Article/details/gtrfaxerfi.html

[Q66] 行锁查询
来源：http://dali.yanxiufei.cn/Article/details/gtvpeqsoai.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.feifeiyinyue.top/Article/details/gtlqhivlux.html

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gtnvjgkoke.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gtakptyqnb.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gtxaosiggr.html

SAVEPOINT sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtbytzvzbq.html

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gtclonbeop.html

[Q69] 查看执行计划
来源：http://dali.0kj1m.cn/Article/details/gteqeethpd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gtbaofeqvn.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gtbzhmpqwy.html

ANALYZE TABLE users;
来源：http://dali.yueranfly.top/Article/details/gteolhvvnj.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gtdngdcvzs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yongpay.top/Article/details/gtribeetot.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gtvahsfvny.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtkzoeummr.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gtyylscdfw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258.top/Article/details/gtdhfftbzs.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtprjnqvyu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gtelhoaudt.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtnpqzdiav.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqoqrdlps.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gtgzlsecnc.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gtohpaxvfm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgufenzy.top/Article/details/gtbboxugve.html

[Q77] 时间加减
来源：http://dali.chenjidiqi.icu/Article/details/gtfimhlrkh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ppjwa.cn/Article/details/gtuzvxxjrp.html

[Q78] 当前时间
来源：http://dali.yj202588.top/Article/details/gtcmedrvqm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhoulong.xyz/Article/details/gttdqomzss.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gtrmozjrik.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gtzigedouu.html

[Q80] 字符串截取
来源：http://dali.yuanzhike.top/Article/details/gtlhopieqk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtdmevxawx.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtvfxluipr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnqzz.top/Article/details/gtvrpzpdhe.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gtevttihru.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtywdqrftk.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtpgelparh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtcescfrzb.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gtrsczqeyh.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqydnirwg.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gtxbupfpva.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gtrjcikyzz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gtgnejtqra.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gtjavijsfl.html

[Q87] JSON 字段做条件
来源：http://dali.jqgfzy.top/Article/details/gtuzshuqpq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwkfucde.html

[Q88] 行转列（条件聚合）
来源：http://dali.redwolf501.top/Article/details/gtbeuzgtig.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.redwolf501.top/Article/details/gtnivkpypm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xziqi.cn/Article/details/gthnbjoalz.html

[Q89] 判断表是否存在
来源：http://dali.yueranfly.top/Article/details/gtxxkhdwvv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gtcqvobphd.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gtrrofyael.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.birdmap.top/Article/details/gtwyawpwzn.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtqigdwimq.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gtcphxeerb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtluafomab.html

[R01] shebang 与严格模式
来源：http://dali.cheryme.top/Article/details/gtnzsiljsh.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gtcciuujyi.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gtlffaqhse.html

[R02] 变量赋值与使用
来源：http://dali.havefunace.top/Article/details/gtlavvlfed.html

name="Tom"; echo "$name"
来源：http://dali.hnxiangtu.top/Article/details/gtwdjrczof.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gtstkrhkwp.html

readonly PI=3.14
来源：http://dali.sysykeji.top/Article/details/gtqhrkqwjt.html

[R04] 位置参数
来源：http://dali.yueranfly.top/Article/details/gtaxkbmyix.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gtuwkskquv.html

[R05] 参数默认值
来源：http://dali.yj20258888.top/Article/details/gtgmwjdkgu.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gtotegcpwd.html

[R06] 判断命令是否存在
来源：http://dali.bjfxy.top/Article/details/gtrtwsjrxb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthqeyrfgz.html

[R07] if 判断文件
来源：http://dali.yvedp.cn/Article/details/gtlsahyyzh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gtvxldnzux.html

[R08] 数值比较
来源：http://dali.9152youxi.cn/Article/details/gtkpgzbmtf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aibaodan.cn/Article/details/gthbtqgrii.html

[R09] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gthovumhmz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtvdxnwvep.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gtqprkvxbh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xinyue.icu/Article/details/gtikbtgyzp.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gtibcvhatm.html

case "$1" in
来源：http://dali.daria6918.cn/Article/details/gtzjmxihwd.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtnqflpszj.html

stop)  echo "停止" ;;
来源：http://dali.sweek.top/Article/details/gtglpsbwoa.html

*)     echo "未知命令" ;;
来源：http://dali.shzxlz.cn/Article/details/gtljmkrnqx.html

esac
来源：http://dali.havefunace.top/Article/details/gtblvdaqxu.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gtluswtfcb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yvedp.cn/Article/details/gtavgkcomx.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtpakveqvz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryfqqplz.html

[R14] C 风格 for
来源：http://dali.chenjidiqi.icu/Article/details/gtlvfgwgxl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtsivaeayx.html

[R15] while 逐行读文件
来源：http://dali.yj20258.top/Article/details/gtfijvfvzn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cqqwz.cn/Article/details/gtlznarbaj.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtfrisegje.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbveofnm.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gttubhhafh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtjdfnliir.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gtvargqqec.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gtgqevaset.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtlpmmufxy.html

echo "${#arr[@]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtahlcstrr.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gtavwjvzwl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gthjzcgbin.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gtfsugjijf.html


<!-- 参考信息 -->