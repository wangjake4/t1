代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gtbybmealc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gttsyrzcvg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtjcrflcbz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtqirpdgpz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gtlfzvldlj.html

Go:   len(arr);  len(m)
来源：http://dali.feifeiyinyue.top/Article/details/gtfemoitsd.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gtkxqfnsqt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtuecpdjph.html

[P05] 判断两个对象内容是否相等
来源：http://dali.feifeiyinyue.top/Article/details/gtqcvzuiqm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtaccviixi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gtbnskfqkf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gtiafdvmqs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gtvgfwrhtj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ivvv.top/Article/details/gtpkkfnyci.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gthrujesxo.html

Ruby: a == b
来源：http://dali.hfpthk.cn/Article/details/gtqryzvima.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nwbrower.top/Article/details/gtycyrqzwx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.havefunace.top/Article/details/gtuxficoyk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gttfpryhzx.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtethewqxs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cqqwz.cn/Article/details/gtgyebjoen.html

TS:   if (x == null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtiakyocqd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtiozpzxxa.html

Go:   if x == nil {}
来源：http://dali.ivvv.top/Article/details/gtynwfvwht.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gtawlyvicm.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtisedhkhe.html

[P07] 防抖与节流
来源：http://dali.jinqigfzy.top/Article/details/gtalgfvyso.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.redwolf501.top/Article/details/gtyknumkks.html

PHP:  // 手写时间戳比较
来源：http://dali.hongshengwenyu.top/Article/details/gtzmldgkcv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gttojjuzhs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtwyqgqsji.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guowangkeji.top/Article/details/gtshgpvpaf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gtyjjxhbqi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xinyue.icu/Article/details/gtzalbfstl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvipngib.html

[P08] 处理浮点精度问题
来源：http://dali.nanxuanxn.top/Article/details/gtopuvumeq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.quarkkingdee.top/Article/details/gtmqzkyyqi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gtxhepfwmi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gaohongyu789.top/Article/details/gtxlfaejsm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtfkjilseq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.svipenyu.cn/Article/details/gtxstbujnm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258.top/Article/details/gtbdghzicv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gthlyflowv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.andypj.xyz/Article/details/gttxdzekxg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtzxakuhpv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daxiang520.top/Article/details/gtzowgeqey.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtlcsezgqa.html

[Q01] 创建表
来源：http://dali.yj20258.top/Article/details/gtnwsiacut.html

CREATE TABLE users (
来源：http://dali.dianchejie.cn/Article/details/gtskrrbobg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtbvazxipw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtmsmokjuf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gtkvxhaqad.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jianghu66.top/Article/details/gttvrnsbqi.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtvkxnviib.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gtrjwoictq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gteimhuivf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtxowbppjm.html

user_id INT NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtiynferbw.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gtknojagdi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cdnleiting.top/Article/details/gtnppjfful.html

);
来源：http://dali.yangfankeji.com/Article/details/gtfsgxlmsh.html

[Q03] 增加列
来源：http://dali.yvedp.cn/Article/details/gtgfcldyjx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.bjfxy.top/Article/details/gtbbfwhxld.html

[Q04] 修改列类型
来源：http://dali.hywenlv.cn/Article/details/gtmejfmvyl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtidzdwnyf.html

[Q05] 重命名列
来源：http://dali.zhixingplan.top/Article/details/gtujealhrq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.316326.xyz/Article/details/gtoebzkocj.html

[Q06] 删除列
来源：http://dali.yj20258.top/Article/details/gtadkufcwi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aizwys.cn/Article/details/gtpdcbbkkq.html

[Q07] 删除表
来源：http://dali.jlsjyb.cn/Article/details/gtqoqtwhkg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtibwmqgda.html

[Q08] 创建普通索引
来源：http://dali.gotoacloud.top/Article/details/gtvukidfzv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gtoahaxdmh.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gtmtegiqyf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtzwpxdrwo.html

[Q10] 插入单行
来源：http://dali.shzxlz.cn/Article/details/gtapjsixgg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtystnsnnu.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gtkmkmqjug.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtltrqiakc.html

[Q12] 插入后取自增 ID
来源：http://dali.xylfe.cn/Article/details/gtwizkwjwn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yonumen.top/Article/details/gteauuolgx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhiwuduotai.top/Article/details/gtdenigfwn.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gtovnbvzxa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gteupbgpxu.html

[Q14] 存在则更新（upsert）
来源：http://dali.iojbl.cn/Article/details/gthztpurgg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gteltlxapl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvnbokqk.html

[Q15] 查询全部
来源：http://dali.nanxinkj.top/Article/details/gtyxsulolq.html

SELECT * FROM users;
来源：http://dali.meibo888.top/Article/details/gtulcxwauc.html

[Q16] 查询指定列
来源：http://dali.jiagoushi.top/Article/details/gttkirrgwt.html

SELECT id, name FROM users;
来源：http://dali.guannengcc.top/Article/details/gtkobgthon.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gtkxuzlhei.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtxrslgcha.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbzqvzkv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ybcxt.top/Article/details/gtxnjoieuf.html

[Q19] 范围查询
来源：http://dali.gaohongyu789.top/Article/details/gtdplfzsxl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yongpay.top/Article/details/gtnoosczfp.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtgecffxff.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sxryk.cn/Article/details/gtjngpmxfi.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gtumkdzqww.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtvebtthqo.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gtoohjnrbu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuetiantiany.cn/Article/details/gtbskwbkvh.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gtlwvothsh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jiagoushi.top/Article/details/gtuicamowk.html

[Q24] 去重
来源：http://dali.316326.xyz/Article/details/gtbhbhzozk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtcunxdbxm.html

[Q25] 只取前 N 条
来源：http://dali.9152youxi.cn/Article/details/gtwvvenbky.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgfzy.top/Article/details/gtoriotoah.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gthcyssefh.html

SELECT COUNT(*) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtunlhjvpr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gtxgnujgnq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuxming.cn/Article/details/gtmpcvqubf.html

[Q28] 求和与平均
来源：http://dali.yonumen.top/Article/details/gtfxbprcsd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtzvgfpavo.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gtpvyspmbj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjscqbbcn.html

[Q30] 分组统计
来源：http://dali.andypj.xyz/Article/details/gtrdzubysg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtwjzbidid.html

[Q31] 分组后过滤
来源：http://dali.fengsongda.top/Article/details/gtsajpsyps.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gtiwtvagbg.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gthqdudwvh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gticouzlno.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gtyqsuwouy.html

[Q33] 多列分组
来源：http://dali.c1oappe.top/Article/details/gtktbcwkun.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gtrvgzlykj.html

[Q34] 每组取第一条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgiindoq.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtztcxmfvb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ehwqpu.com/Article/details/gtrerptnpp.html

) t WHERE rn = 1;
来源：http://dali.iojbl.cn/Article/details/gtozuadcgd.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gtkqpbnldv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gtaesxzheo.html

[Q36] 左连接
来源：http://dali.chenjidiqi.icu/Article/details/gtrrvakgxh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtbtuetjxz.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gtwfbesgzz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtltnmoypy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.bjfxy.top/Article/details/gtgwpteacb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gtgqcyjbyx.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gtvcizzpwk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxuanxn.top/Article/details/gtfjmftjew.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gttkulpdai.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guannengcc.top/Article/details/gttikhlxzo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daria6918.cn/Article/details/gtusmgcsdg.html

[Q41] 多表连接
来源：http://dali.feifeiyinyue.top/Article/details/gtvinrvhwr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gtdccivflb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.redwolf501.top/Article/details/gtvzadjkcp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shzxlz.cn/Article/details/gtfwxlvevd.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gtjddzjncf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cheryme.top/Article/details/gtkhmkoreq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenzaomai.com/Article/details/gtiublkxiu.html

[Q43] 标量子查询
来源：http://dali.zhengqikj.top/Article/details/gtexnvdmzc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cheryme.top/Article/details/gtnksckrcf.html

[Q44] IN 子查询
来源：http://dali.yj20258888.top/Article/details/gttcvnfqof.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gtrapoepkj.html

[Q45] EXISTS 判断存在
来源：http://dali.chenlongwang.top/Article/details/gtpaszayvi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtkyjqzwfq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gttcofgtor.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gtlfchzomy.html

[Q47] 与平均值比较
来源：http://dali.chenlongwang.top/Article/details/gttbhitmon.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuxming.cn/Article/details/gtszpwvfte.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gtmmagbcbp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guowangkeji.top/Article/details/gtydtwzhga.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzymwtar.html

[Q49] 更新单行
来源：http://dali.zhixingplan.top/Article/details/gtovtcfnzh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtfiynrsem.html

[Q50] 批量更新
来源：http://dali.meibo888.top/Article/details/gtybdwdzea.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fengsongda.top/Article/details/gtpyjxtqqs.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gtecvtynbg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuanzx.com/Article/details/gtgoptrung.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gtrltbbpao.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtydgsindy.html

[Q53] 按条件删除
来源：http://dali.shuidangran.top/Article/details/gtrbhysyqf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gthmelqmpl.html

[Q54] 清空表
来源：http://dali.hongshengwenyu.top/Article/details/gtqblcjdmv.html

TRUNCATE TABLE logs;
来源：http://dali.iojbl.cn/Article/details/gtmlhxnowu.html

[Q55] 排名（并列占位）
来源：http://dali.zhixingplan.top/Article/details/gtemoyzrmf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtusvzyhmv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xinyue.icu/Article/details/gtcrmkazar.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtevzjiugv.html

[Q57] 行号
来源：http://dali.pengpengdd.cyou/Article/details/gtzoulywpd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtpjtktvkm.html

[Q58] 累计求和
来源：http://dali.hywenlv.cn/Article/details/gtdlqrmcwk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtxmdaegqx.html

[Q59] 分组内累计
来源：http://dali.chenjidiqi.icu/Article/details/gtzhjhrwdt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtlzjvvegt.html

[Q60] 取上一行 / 下一行
来源：http://dali.cqqwz.cn/Article/details/gtgavjqepo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhixingplan.top/Article/details/gtdndqimpg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtcfgiptop.html

[Q61] 移动平均
来源：http://dali.yonumen.top/Article/details/gtyeeeirrn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdbafkly.html

[Q62] 分组占比
来源：http://dali.zhoulong.xyz/Article/details/gtkocmblmu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gttlgmhlpf.html

[Q63] 开启事务
来源：http://dali.316326.xyz/Article/details/gtdptwqtvd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xylfe.cn/Article/details/gtvxerwqza.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gtcegavvqa.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gtomzxklui.html

[Q65] 回滚事务
来源：http://dali.guowangkeji.top/Article/details/gtyonitswh.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gttapgkhhn.html

[Q66] 行锁查询
来源：http://dali.ivvv.top/Article/details/gtcoxjwibu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jianghu66.top/Article/details/gtnlhqptuy.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gtzmxzjlht.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gtmhdhrude.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gttnnuvwee.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gtiyfmbqyi.html

ROLLBACK TO sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmpnegdz.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gtvzgoylln.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gtrzfyfaqn.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangtech.top/Article/details/gttolvuzvj.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gtwnajlrgs.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gtjdracavu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guowangkeji.top/Article/details/gtbuzldywp.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gtttkbegfh.html

SHOW INDEX FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtaxdflick.html

[Q73] 查看表状态
来源：http://dali.svipenyu.cn/Article/details/gtejceauvg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fzhhl.top/Article/details/gtyvrardml.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gtiegfsnao.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gtmjzyxmrk.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtvpisnwvm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtmhbyayxe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangshuangyany.cn/Article/details/gtvcixuggy.html

[Q76] 按天统计
来源：http://dali.gzhubu.top/Article/details/gtfzvitcnb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gtydjslmiz.html

[Q77] 时间加减
来源：http://dali.ybcxt.top/Article/details/gtjlreffud.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gtbephuoph.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtmoszhntj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fengsongda.top/Article/details/gtsavdwykl.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtkodkpqqv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gtlotcxlul.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gtvmxiaxzy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtfwsozraf.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtvhomraix.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.meibo888.top/Article/details/gtgqfnaktf.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gtnrcdinfg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtjgqkbxwy.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtnmevvopm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtjpxvwioc.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrziuwzjr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtumbufvze.html

[Q85] 数值取整
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlnxjcft.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gtzbgpselj.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gtvzwelpub.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gtuiemyqxy.html

[Q87] JSON 字段做条件
来源：http://dali.ehwqpu.com/Article/details/gtgxtvgjyc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gtoydallff.html

[Q88] 行转列（条件聚合）
来源：http://dali.sufxvd.cn/Article/details/gtucbudgcd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.havefunace.top/Article/details/gtbhippxhx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.0kj1m.cn/Article/details/gttjywwzun.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gtowtwtein.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pycfn.com/Article/details/gtgwgopavc.html

[Q90] 生成序号列
来源：http://dali.cdnleiting.top/Article/details/gtnaopgndr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gtdosizznt.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttpngtxsw.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gtykzmcjxa.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtjqmgdscy.html

[R01] shebang 与严格模式
来源：http://dali.ehwqpu.com/Article/details/gtnnizjqov.html

#!/usr/bin/env bash
来源：http://dali.gzhubu.top/Article/details/gtpweittax.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gtvdhffgfa.html

[R02] 变量赋值与使用
来源：http://dali.gotoacloud.top/Article/details/gtnfwmptmf.html

name="Tom"; echo "$name"
来源：http://dali.snrcjt.cn/Article/details/gttoxzejxx.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gtsboiitvy.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gtwfbffeka.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gtmxkzfdtz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ydzc1.top/Article/details/gtvrehrgyl.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gtvagqoeyq.html

name="${1:-default}"
来源：http://dali.cdnleiting.top/Article/details/gtnrpvcqxp.html

[R06] 判断命令是否存在
来源：http://dali.redwolf501.top/Article/details/gtwdbmirov.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gthzygwzjb.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gtkpckdrmy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gtdpriioav.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gtxkskfebs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gthdmsxcth.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtydaihrum.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtxrslxsou.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtpksjrgzu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gtsakqpblw.html

[R11] case 多分支
来源：http://dali.shuidangran.top/Article/details/gtmvqgxkzs.html

case "$1" in
来源：http://dali.yuxming.cn/Article/details/gtzputuyns.html

start) echo "启动" ;;
来源：http://dali.yvedp.cn/Article/details/gtovpujtlt.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gtojttrvhn.html

*)     echo "未知命令" ;;
来源：http://dali.9152youxi.cn/Article/details/gtemyxacfv.html

esac
来源：http://dali.haohaochexian.top/Article/details/gtzswyxisl.html

[R12] for 遍历文件
来源：http://dali.havefunace.top/Article/details/gtexdepqyy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daria6918.cn/Article/details/gtpsgzsgli.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtfchjxrjc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtckjntini.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gtooktskva.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtrwilocmt.html

[R15] while 逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gttdqlsggj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gtjxpwomsq.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gtbineirft.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gtivfggvxl.html

[R17] 数组定义与取值
来源：http://dali.yj20258.top/Article/details/gthstdgoxd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hfpthk.cn/Article/details/gtglhdmauo.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gtjxgbpxuh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gtyiuavjof.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtiytdrngr.html

echo "${#arr[@]}"
来源：http://dali.sweek.top/Article/details/gtmxztelec.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gtthkrrjms.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gtctnrjjoq.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gtffthflxu.html


<!-- 参考信息 -->