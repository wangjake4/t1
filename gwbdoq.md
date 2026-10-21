代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gtnkdboxny.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aizwys.cn/Article/details/gtutvjihyr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.vqdsnc.cn/Article/details/gtaastrdul.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gtgpmlhnsy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ehwqpu.com/Article/details/gtpublmezf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtggbosvxc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gtklcpllzb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtehetvaja.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcskkhzn.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gtbxoipzfp.html

Ruby: x.length;  x.size
来源：http://dali.yanxiufei.cn/Article/details/gtbkbfhyfo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gtmwlenaup.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shuidangran.top/Article/details/gtwkhahaix.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hongshengwenyu.top/Article/details/gtymwrrghy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shzxlz.cn/Article/details/gtzjejmrjc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jiagoushi.top/Article/details/gtfgwoxmxm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gtfrietuiv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gtcrebfvpm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ydzc1.top/Article/details/gtcpoafnfs.html

Ruby: a == b
来源：http://dali.yj202588.top/Article/details/gtiynxaqjf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shuidangran.top/Article/details/gtawcchcdw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gterhbpnvz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gtajsxybjt.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gtcgckjlzk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ehwqpu.com/Article/details/gtvvkjzwzj.html

TS:   if (x == null) {}
来源：http://dali.hnqzz.top/Article/details/gtknioiuiz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtsrsfykyf.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gtdvqcbbzn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzgyoech.html

C#:   if (x is null) {}
来源：http://dali.aibaodan.cn/Article/details/gtbpcukats.html

[P07] 防抖与节流
来源：http://dali.xinyue.icu/Article/details/gtaybhnstv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yanxiufei.cn/Article/details/gtdtouxvpl.html

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gtnwblessk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtmfqzmuyj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtebqkgmsw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenlongwang.top/Article/details/gthchbtqxm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gtwignnvty.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.vqdsnc.cn/Article/details/gttqhirufq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.bjfxy.top/Article/details/gtzypnxjpz.html

[P08] 处理浮点精度问题
来源：http://dali.yj202588.top/Article/details/gtfherhzus.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cashguo.top/Article/details/gtarbaojnf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.vqdsnc.cn/Article/details/gthspbxzhp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhengqikj.top/Article/details/gtlybispgu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gtupjgfbpk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gtyedkqdsk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gtbxfbejss.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pengpengdd.cyou/Article/details/gtddbilihl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dianchejie.cn/Article/details/gtojbuerqo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gttyyscilc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvtrgswp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtcecmtsuc.html

[Q01] 创建表
来源：http://dali.hammf.cn/Article/details/gtrkiejkcw.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gtkettrrfw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtsvxoscoj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtzbtbdzlp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gtsjqfgrsn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.birdmap.top/Article/details/gtlvxrvrhd.html

);
来源：http://dali.gzhubu.top/Article/details/gttzdubkjb.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gtuvmbdpjm.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gtmtnvetje.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtohcsylwv.html

user_id INT NOT NULL,
来源：http://dali.yongpay.top/Article/details/gtuecymczm.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmagxryr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.0kj1m.cn/Article/details/gtpaaamdyk.html

);
来源：http://dali.nwbrower.top/Article/details/gtwbidukfe.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gtcloeznqw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuanzhike.top/Article/details/gttyiirytd.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gtkvcwrmuk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sysykeji.top/Article/details/gtbhglosxw.html

[Q05] 重命名列
来源：http://dali.yvedp.cn/Article/details/gtzouwcsxl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.vqdsnc.cn/Article/details/gtthhaebuf.html

[Q06] 删除列
来源：http://dali.svipenyu.cn/Article/details/gtxijhenpr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.316326.xyz/Article/details/gtvcmzpwlp.html

[Q07] 删除表
来源：http://dali.quarkkingdee.top/Article/details/gtpdtaxycx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavbntake.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gtuvtynnee.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtpqrxvxzn.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gtagbalvpd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtkvbzcbic.html

[Q10] 插入单行
来源：http://dali.shuidangran.top/Article/details/gtmptuwzac.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gtksynzadc.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gtmqhzxttd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtruwuqzio.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgufenzy.top/Article/details/gtkjfpijkl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gtxqjssdnp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jqgfzy.top/Article/details/gtnyrsptnt.html

[Q13] 忽略重复插入
来源：http://dali.kuanghao11.cn/Article/details/gtumrkddhj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtnqyqkjhl.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtllaonyxe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258888.top/Article/details/gtkvkmvozp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hywenlv.cn/Article/details/gtcodthmnk.html

[Q15] 查询全部
来源：http://dali.ydzc1.top/Article/details/gtmgnwffbh.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gttopfscps.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gtirnvxlvb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gthdsnxtvo.html

[Q17] 条件查询
来源：http://dali.yj202588.top/Article/details/gtkfprjfhm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.snrcjt.cn/Article/details/gthdcoykla.html

[Q18] 模糊匹配
来源：http://dali.xylfe.cn/Article/details/gtnmbflddd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ivvv.top/Article/details/gtcltbhvaz.html

[Q19] 范围查询
来源：http://dali.birdmap.top/Article/details/gtnbwmaxbh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gzhubu.top/Article/details/gtcqruvgjz.html

[Q20] IN 列表
来源：http://dali.yuanzhike.top/Article/details/gtvwwqsbos.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gtybvuqwgt.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsnjdhhe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gtvgqglpnw.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gtmxbwmmom.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gtfxrguslt.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gteyzozqwv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gthxcgbbtt.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gtvfyqffmx.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsmtfpbq.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gtdjtwummj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gtbuhusjxm.html

[Q26] 计数
来源：http://dali.andypj.xyz/Article/details/gtmihyistn.html

SELECT COUNT(*) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtyfkzclex.html

[Q27] 条件计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqojliiu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gttfmjyfsn.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gtclvjijza.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtncofdtgf.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gtfunbknlt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gttqkkidrw.html

[Q30] 分组统计
来源：http://dali.yvedp.cn/Article/details/gtsxgudacm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtytthnhrd.html

[Q31] 分组后过滤
来源：http://dali.yanxiufei.cn/Article/details/gtbfdonujp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gtosfelcff.html

[Q32] 分组拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtcndzjbps.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtdwefjrvd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jiagoushi.top/Article/details/gtuevxibqf.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gtwtqpgqlf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tianlin.xyz/Article/details/gtmuzgpmtu.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcuqcixx.html

SELECT * FROM (
来源：http://dali.zhoulong.xyz/Article/details/gtanlttodw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gttgbvbmdh.html

) t WHERE rn = 1;
来源：http://dali.andypj.xyz/Article/details/gtitgxcgvd.html

[Q35] 内连接
来源：http://dali.jyoumei.cn/Article/details/gtkmthhuje.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhbavftq.html

[Q36] 左连接
来源：http://dali.sufxvd.cn/Article/details/gtybkrafza.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gtyyahlwoc.html

[Q37] 右连接
来源：http://dali.fengsongda.top/Article/details/gtvswbwmef.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aizwys.cn/Article/details/gtzsrkgjhr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aibaodan.cn/Article/details/gtbwfvlrzf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.andypj.xyz/Article/details/gtcuxmnsro.html

[Q39] 自连接（查上下级）
来源：http://dali.0kj1m.cn/Article/details/gtawjejatz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pycfn.com/Article/details/gthewhvdbg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dianchejie.cn/Article/details/gtzwpkaxrw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.0kj1m.cn/Article/details/gtetrgqyfu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sysykeji.top/Article/details/gtlgfyimhu.html

[Q41] 多表连接
来源：http://dali.zhiwuduotai.top/Article/details/gtkhzqamck.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gtogslcloh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tianlin.xyz/Article/details/gtxxffulkp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhongyouzk.top/Article/details/gtsbxnsjuy.html

[Q42] 连接条件附加过滤
来源：http://dali.cucudq.cn/Article/details/gtdafpausf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cheryme.top/Article/details/gtgzhbzgth.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pycfn.com/Article/details/gtltdkyhoo.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gtflylmpxr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangshuangyany.cn/Article/details/gtbevrqjlr.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gtyqaowdit.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodrqmfjy.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gtgeazybyk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtdaifxqiw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gthaslfxsn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtzxlidrlk.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gtzeujuvgw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gtzfuydtkx.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gtgrevbksf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenlongwang.top/Article/details/gtltjdmxsj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zdqjudy.top/Article/details/gtgoqxblth.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gtggykzlcr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gthcwvmueh.html

[Q50] 批量更新
来源：http://dali.fengsongda.top/Article/details/gtzczvzvjr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gtciydprqv.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gtiddeagct.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtlmedpxno.html

[Q52] 删除指定行
来源：http://dali.mhx1999.top/Article/details/gtrsraoxoz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtfaxzddyn.html

[Q53] 按条件删除
来源：http://dali.jinqigufen.top/Article/details/gtitritbqf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gtqlhrrnrz.html

[Q54] 清空表
来源：http://dali.tianlin.xyz/Article/details/gtgtmaajsb.html

TRUNCATE TABLE logs;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmqjbynz.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gtsndwazbl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtuqtjsyqa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daria6918.cn/Article/details/gtlxuicgcs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258.top/Article/details/gtxfupkpdz.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gthtahjuyn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daxiang520.top/Article/details/gtjsuprmep.html

[Q58] 累计求和
来源：http://dali.ivvv.top/Article/details/gtpdkndesy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtdfafnooq.html

[Q59] 分组内累计
来源：http://dali.chenlongwang.top/Article/details/gtkrgyrcjs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtdgmnggvc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gtejwrhrnp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fzhhl.top/Article/details/gtdtyivckn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gttbmqpkjp.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtreqwfjgj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtzshlmdac.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlxvsusf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtaxlwqrdc.html

[Q63] 开启事务
来源：http://dali.sufxvd.cn/Article/details/gtelrqewbq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ydzc1.top/Article/details/gtqfafomie.html

[Q64] 提交事务
来源：http://dali.sysykeji.top/Article/details/gtvgndimhf.html

COMMIT;
来源：http://dali.nanxinkj.top/Article/details/gtjnycdwux.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gtlgticfhy.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gtzielyawc.html

[Q66] 行锁查询
来源：http://dali.yongpay.top/Article/details/gtrnjcsgfw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gtzfojwnxb.html

[Q67] 设置隔离级别
来源：http://dali.meibo888.top/Article/details/gtkordvmzs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gtsrzifexe.html

[Q68] 保存点
来源：http://dali.andypj.xyz/Article/details/gtgnijnuws.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbuzdcfx.html

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gtsffwdhyg.html

[Q69] 查看执行计划
来源：http://dali.yuanzhike.top/Article/details/gtcultahrl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gtneuwrsol.html

[Q70] 更新统计信息
来源：http://dali.zhixingplan.top/Article/details/gtsbayushq.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtinchosvg.html

[Q71] 查看建表语句
来源：http://dali.sweek.top/Article/details/gtavzrdxpz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhengqikj.top/Article/details/gtltpacovl.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gtaehjvxrs.html

SHOW INDEX FROM users;
来源：http://dali.wangdashe.top/Article/details/gtgaoijnzy.html

[Q73] 查看表状态
来源：http://dali.tian-w.cn/Article/details/gtcoupeipf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgfzy.top/Article/details/gtllhnmiud.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gtccssggvg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fengsongda.top/Article/details/gtukydenyl.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtjldvxoho.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtrxudzryu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.havefunace.top/Article/details/gteowcrbqk.html

[Q76] 按天统计
来源：http://dali.ybcxt.top/Article/details/gtcttaywsf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gtqokhbssd.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gtgzzowtsl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gtgeiiiwda.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gtxjaedziw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gtibjkhjoj.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gtkerponxt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhengqikj.top/Article/details/gtndhjvtyf.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gtubbrqqcy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtelyjlnop.html

[Q81] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gtzdxblkyw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gtljhylcuh.html

[Q82] 字符长度与字节长度
来源：http://dali.yangfankeji.com/Article/details/gtqqsvunii.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtszwqdfuv.html

[Q83] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtshoyxumi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtkcxhzdho.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gtdvyfhhyn.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtkhtcicek.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gtfjnjpswd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aizwys.cn/Article/details/gthbkaqgro.html

[Q86] 读取 JSON 字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcyejluf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.meibo888.top/Article/details/gtyyatwweq.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gtdfqhzueg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jlsjyb.cn/Article/details/gtxleqgpud.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gtkhtxygwv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gtpzifpufg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtsaetqdnp.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gtiukihabm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtepmxjrdy.html

[Q90] 生成序号列
来源：http://dali.pycfn.com/Article/details/gthnltpezt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtdanbohum.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfsxqxivi.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gthflrhxhv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdawirjqq.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gtdihoxdff.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gteylnfyvb.html

set -euo pipefail
来源：http://dali.jiagoushi.top/Article/details/gtozgwrndi.html

[R02] 变量赋值与使用
来源：http://dali.sweek.top/Article/details/gticzgrjiy.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gtendjllln.html

[R03] 只读变量
来源：http://dali.xuanzx.com/Article/details/gtewhmucyo.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gtnylxvnsh.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gtzfyhbrqo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jianghu66.top/Article/details/gtkeukssyz.html

[R05] 参数默认值
来源：http://dali.aizwys.cn/Article/details/gthvsjkkvl.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gthihuwpme.html

[R06] 判断命令是否存在
来源：http://dali.ehwqpu.com/Article/details/gtvovsmuao.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtfenpwwus.html

[R07] if 判断文件
来源：http://dali.zhixingplan.top/Article/details/gtrdhsrxbz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtgkdhihva.html

[R08] 数值比较
来源：http://dali.mhx1999.top/Article/details/gtrwggejhe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenzaomai.com/Article/details/gtjovllnda.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gtuqhutqcd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hammf.cn/Article/details/gtzbwvxyqk.html

[R10] 正则匹配
来源：http://dali.mhx1999.top/Article/details/gtqtflijqf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gtpjseirfm.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gtlnkcgfva.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gthzvymvul.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gtkxdxgeyq.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gtxkohgovs.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gtdodxmyqo.html

esac
来源：http://dali.tian-w.cn/Article/details/gtogslexni.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gtgqnsvtrb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gthusgnhrw.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtqnpekqcd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gtzfpqbmbk.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gtjvjmynji.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtexptaham.html

[R15] while 逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtoawvsbax.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtjkomysjo.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtjlnznsrb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtakzdkkhm.html

[R17] 数组定义与取值
来源：http://dali.yj20258888.top/Article/details/gtcicnxsje.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gtvfvbrxxm.html

[R18] 遍历数组
来源：http://dali.zhoulong.xyz/Article/details/gtlnqareni.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gtuudbqcoy.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtdcjdonia.html


<!-- 参考信息 -->