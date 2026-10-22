代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gtwdnghtgw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtzbwwyfmz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cdnleiting.top/Article/details/gtriiimkuz.html

[P04] 求长度
来源：http://dali.hongshengwenyu.top/Article/details/gtfjjsqwoy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gtmyccsysx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtlwixvgjs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtsvguvhxw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gthbnorclq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtpobpjbps.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gtmxklnopt.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gtegtcafzy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtxtziougp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.smart0.xyz/Article/details/gtuiiglihi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zdqjudy.top/Article/details/gtgigqwhyq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.0kj1m.cn/Article/details/gtxvkzzall.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gtptyqqdpj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ppjwa.cn/Article/details/gthxrtixvw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gtyfbfgrgo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtootbrqef.html

Ruby: a == b
来源：http://dali.nanxinkj.top/Article/details/gtpuxjdvsb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gtugzojhds.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gtvplbykcs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gtcqqlvoft.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gttwpbwxck.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gtiogaugpu.html

TS:   if (x == null) {}
来源：http://dali.shuidangran.top/Article/details/gtwohizlbn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtiowaufzf.html

Go:   if x == nil {}
来源：http://dali.hysaishi.cn/Article/details/gteebijhwr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhongyouzk.top/Article/details/gtgngiodxz.html

C#:   if (x is null) {}
来源：http://dali.316326.xyz/Article/details/gtrygtmaha.html

[P07] 防抖与节流
来源：http://dali.shzxlz.cn/Article/details/gtihdtrdoc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yangfankeji.com/Article/details/gtrwcbkgcx.html

PHP:  // 手写时间戳比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbxwymxh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzspcntvm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtjsidkjxq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangdashe.top/Article/details/gtvnoiossq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gticlghbsf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dianchejie.cn/Article/details/gtjptiqqzd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangtech.top/Article/details/gttynekucm.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gthgtrzezh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hammf.cn/Article/details/gtyxiiastm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cheryme.top/Article/details/gtpzeylbmb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gtvewtpemh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtqpqyoxhw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gtgekdosbp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbzvtvje.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aizwys.cn/Article/details/gtsmsjltsv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daria6918.cn/Article/details/gtgfmckwnx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtoijcgftk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yanxiufei.cn/Article/details/gtwxcvtcgx.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtngldvoox.html

[Q01] 创建表
来源：http://dali.chenlongwang.top/Article/details/gtbrhlbnup.html

CREATE TABLE users (
来源：http://dali.ybcxt.top/Article/details/gtrugkylcs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtnnhirflh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtjxzmysoa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxuanxn.top/Article/details/gtsbdnyuva.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gtpsxniksw.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gtigezupur.html

[Q02] 创建带外键的表
来源：http://dali.jinqigfzy.top/Article/details/gtfuiyqsgt.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gtqhgysnuh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtuokmawlq.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtusmtmarg.html

amount DECIMAL(10, 2),
来源：http://dali.nanxuanxn.top/Article/details/gtnikvrbmg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.mhx1999.top/Article/details/gtsueexfhw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtwpnmcjhf.html

[Q03] 增加列
来源：http://dali.nanxuanxn.top/Article/details/gtdrfjxbep.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.kuanghao11.cn/Article/details/gtuumtpfvt.html

[Q04] 修改列类型
来源：http://dali.yvedp.cn/Article/details/gtmyxxksom.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhfmtlhb.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtakqmzspa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgfzy.top/Article/details/gtmlxcgeag.html

[Q06] 删除列
来源：http://dali.gogol.net.cn/Article/details/gtjqtpgxok.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gtujitwchr.html

[Q07] 删除表
来源：http://dali.tianlin.xyz/Article/details/gtuglppyvd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj202588.top/Article/details/gtyazbefkv.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gtkrzuoreg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtibvhfral.html

[Q09] 创建唯一索引
来源：http://dali.zycfv.cn/Article/details/gtokhexqpf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gtnmgafyat.html

[Q10] 插入单行
来源：http://dali.ydzc1.top/Article/details/gtrgciphfv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtzuthudrz.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gtzxucsevs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gtklejfzwh.html

[Q12] 插入后取自增 ID
来源：http://dali.fzhhl.top/Article/details/gtlhhzwfsp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ehwqpu.com/Article/details/gtwnpaeold.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sysykeji.top/Article/details/gtkqqctont.html

[Q13] 忽略重复插入
来源：http://dali.zdqjudy.top/Article/details/gtmezaujae.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.svipenyu.cn/Article/details/gthyytuehj.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtiqnbhcdn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hysaishi.cn/Article/details/gtggbekjux.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dianchejie.cn/Article/details/gtiedokoig.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gtankrnsel.html

SELECT * FROM users;
来源：http://dali.meibo888.top/Article/details/gthqljpeta.html

[Q16] 查询指定列
来源：http://dali.ivvv.top/Article/details/gtpzhriocp.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gtauhhlnoq.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gtkpjabbsm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gtswnifitu.html

[Q18] 模糊匹配
来源：http://dali.bjfxy.top/Article/details/gtszfjchtu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hywenlv.cn/Article/details/gtpnxyqpzi.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gtdlqsgxik.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangdashe.top/Article/details/gteialkmon.html

[Q20] IN 列表
来源：http://dali.bjfxy.top/Article/details/gteygcbuep.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hfpthk.cn/Article/details/gtiwnufmea.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gthsoitqvl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtqoapbtpp.html

[Q22] 排序
来源：http://dali.jqgufenzy.top/Article/details/gtgnldagtr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gtoddrduhs.html

[Q23] 分页
来源：http://dali.aizwys.cn/Article/details/gtozduzouk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gtvfsagpgg.html

[Q24] 去重
来源：http://dali.zdqjudy.top/Article/details/gtdkdshybe.html

SELECT DISTINCT city FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtltfcommv.html

[Q25] 只取前 N 条
来源：http://dali.yongpay.top/Article/details/gtoujfyelf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gtcyvvxfyj.html

[Q26] 计数
来源：http://dali.zhongyouzk.top/Article/details/gtjjdioorc.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtasedmfdt.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gtdtltjzkg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aizwys.cn/Article/details/gtrpqwbicw.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gtornipjqd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtvholccjy.html

[Q29] 最大最小值
来源：http://dali.jyoumei.cn/Article/details/gtmcdpnler.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtlyvyzwtw.html

[Q30] 分组统计
来源：http://dali.tian-w.cn/Article/details/gtvmxxtjfy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtfufyvbam.html

[Q31] 分组后过滤
来源：http://dali.tian-w.cn/Article/details/gttnxphkee.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.316326.xyz/Article/details/gtyxxvgkbd.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtwvqbpmnx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gthkkaexxt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gtfryfmjce.html

[Q33] 多列分组
来源：http://dali.zycfv.cn/Article/details/gtpdlatahs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenzaomai.com/Article/details/gtyhkrovgu.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gtxxonswtp.html

SELECT * FROM (
来源：http://dali.feifeiyinyue.top/Article/details/gtwcwwkxat.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhiwuduotai.top/Article/details/gtlgfaucjo.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gtdefuivbp.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gtsmhmwqhz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtzgrhfgvb.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gtqujjyian.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtlxvtgyua.html

[Q37] 右连接
来源：http://dali.sxryk.cn/Article/details/gtrztssrch.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gtvvlvzgoy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.bjfxy.top/Article/details/gtahixexnc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gtuifoavka.html

[Q39] 自连接（查上下级）
来源：http://dali.aibaodan.cn/Article/details/gtxlultmxu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hysaishi.cn/Article/details/gtkzfsbgum.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.kuanghao11.cn/Article/details/gthowfewju.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gtkkgvoidq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gtovieobrf.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqqmmhzm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gtrvppnsmr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gtgyfjrphw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gtbjoudulf.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtuoksgmqf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.kuanghao11.cn/Article/details/gtmlwqvunf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigfzy.top/Article/details/gtscclhuws.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gthimfrwsx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gtxruzgthl.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gtooiufpyu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gtqiiigied.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gtiezpwuvt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtzwfyiscg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gtulcanwhx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gtwkafbfek.html

[Q47] 与平均值比较
来源：http://dali.jiagoushi.top/Article/details/gtpcqmslrg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.meibo888.top/Article/details/gtrzmtxqpj.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gtcfznofzw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gtfhqeokym.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dianchejie.cn/Article/details/gtivozjbon.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gtxwgmazsi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtulajxwao.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gtwsmoxffd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cucudq.cn/Article/details/gtaohakxyv.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtaitycnmm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jyoumei.cn/Article/details/gtpvlwalol.html

[Q52] 删除指定行
来源：http://dali.zycfv.cn/Article/details/gtwbqgxqad.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtylrbcgej.html

[Q53] 按条件删除
来源：http://dali.yonumen.top/Article/details/gtiupefief.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtxrvtyhyj.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gtiuxnbiuh.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtsuekysbe.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtxucjkeco.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtoejwaoxt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gteufuradz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gtjbktmhyv.html

[Q57] 行号
来源：http://dali.xylfe.cn/Article/details/gtvzhfwibm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtaypvpllg.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtjefsnhuc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtcsjmypew.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gtlvdabjeg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtublnxysh.html

[Q60] 取上一行 / 下一行
来源：http://dali.sufxvd.cn/Article/details/gtdfqhwcqu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpikpnzox.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtasuyapoa.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gtqvalzpyp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtsmwjgxpr.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gtoqsstvgl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtqfvpdvvr.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcvnoixg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gtebnchstb.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gtykioevyz.html

COMMIT;
来源：http://dali.chenjidiqi.icu/Article/details/gtxpemxxra.html

[Q65] 回滚事务
来源：http://dali.gzhubu.top/Article/details/gteiqzmavf.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gtevdcenpn.html

[Q66] 行锁查询
来源：http://dali.ydzc1.top/Article/details/gtgdysfhrs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shangyingyoupin.top/Article/details/gtmowzgsra.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gtubcboyki.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fengsongda.top/Article/details/gthllpidvv.html

[Q68] 保存点
来源：http://dali.bjfxy.top/Article/details/gtrcehlrkm.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtounlrpjx.html

ROLLBACK TO sp1;
来源：http://dali.dianchejie.cn/Article/details/gtguumnozd.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gticglgvag.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzzylwye.html

[Q70] 更新统计信息
来源：http://dali.kuanghao11.cn/Article/details/gtulvntwtf.html

ANALYZE TABLE users;
来源：http://dali.yj202588.top/Article/details/gtliwpiuyo.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwqkaweq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zdqjudy.top/Article/details/gtxlgrpnst.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gteqbguoky.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtyfrrryzb.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gteoyucsya.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.birdmap.top/Article/details/gtyoqjgiev.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gtyinzcycw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gtzizoqgwm.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtipuynayd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvixkxed.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gtyhgkivqq.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gteswhurvj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gtqumxboys.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gtunepfowb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gtelnlhlqn.html

[Q78] 当前时间
来源：http://dali.smart0.xyz/Article/details/gtnabodosp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.birdmap.top/Article/details/gtqhtoygdm.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gttwrsltxu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gtpsmzulzw.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtodxtgfnr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtzrlbolmw.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtaibjxyjy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gtrioeqbva.html

[Q82] 字符长度与字节长度
来源：http://dali.chenlongwang.top/Article/details/gtoejmyiwp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtjfdpghnr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtgvkzdxpv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtpzhkzzpi.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gtdzyldqnh.html

SELECT TRIM(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtvzygcxyu.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gtijbisxwx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gtexbdzdni.html

[Q86] 读取 JSON 字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzqscnjy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhiwuduotai.top/Article/details/gtwlgiduvj.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gtzmjanbdy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gtpuzxuyzv.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gtrxzneeuc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gtjbosbidt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtnqedzkao.html

[Q89] 判断表是否存在
来源：http://dali.chenzaomai.com/Article/details/gtknleggdk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gthjbrsqlt.html

[Q90] 生成序号列
来源：http://dali.ydzc1.top/Article/details/gtkxgkhetc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gtehysgazx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtgbibwjxp.html

R. Bash 专题
来源：http://dali.zycfv.cn/Article/details/gtwslrzjof.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtsipzngql.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gtmoeawnui.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gtpzkuqnvp.html

set -euo pipefail
来源：http://dali.c1oappe.top/Article/details/gtwogunpta.html

[R02] 变量赋值与使用
来源：http://dali.tian-w.cn/Article/details/gtbllxlnhr.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gtcxowwssv.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gtidkltruc.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gtdguumvrm.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gtlwwxzymn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtywjpcken.html

[R05] 参数默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumfmgtor.html

name="${1:-default}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpyvpbzv.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gtimpzytol.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtfoyjrunq.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gtqylmxojk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gtfanntflf.html

[R08] 数值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoqbrpim.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gtzaqmyioe.html

[R09] 字符串比较
来源：http://dali.c1oappe.top/Article/details/gtnaevbnyk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtajvbfgzj.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtipmqwelq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.0kj1m.cn/Article/details/gttfqtelzw.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gtrelgralf.html

case "$1" in
来源：http://dali.yj202588.top/Article/details/gtgkwckxoi.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gtwgceyryn.html

stop)  echo "停止" ;;
来源：http://dali.yongpay.top/Article/details/gtlytpgkya.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gtmtvrfhxu.html

esac
来源：http://dali.jqgfzy.top/Article/details/gtemkfmois.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtlcfxvtha.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fzhhl.top/Article/details/gtxlzxnsxh.html

[R13] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gtlyvmbnfl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gteklniaap.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gtwhntvfzl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtrcbkyxzp.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtuvoknchf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gtzbimpdlb.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gteybrnrto.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtqswiefqz.html

[R17] 数组定义与取值
来源：http://dali.sysykeji.top/Article/details/gtptdbczyb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.quarkkingdee.top/Article/details/gtnsqzbcar.html

[R18] 遍历数组
来源：http://dali.yj20258888.top/Article/details/gtnwbsufre.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gtuihokfkk.html

[R19] 数组长度
来源：http://dali.cheryme.top/Article/details/gtcvuqrwez.html


<!-- 参考信息 -->