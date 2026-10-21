代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gtfmssowzw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gthpawjpjf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkumkusqk.html

[P04] 求长度
来源：http://dali.zhixingplan.top/Article/details/gthltmpjmt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gotoacloud.top/Article/details/gtqylwpoqp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtuqfgvarm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gtbufrwwqz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtlmxxqwqh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xylfe.cn/Article/details/gtxakxxujk.html

Go:   len(arr);  len(m)
来源：http://dali.zhongyouzk.top/Article/details/gtgicsunlj.html

Ruby: x.length;  x.size
来源：http://dali.zhengqikj.top/Article/details/gtltzlqvqy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yongpay.top/Article/details/gtmbozzbhf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cucudq.cn/Article/details/gtmfwvjbka.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pycfn.com/Article/details/gttawsmgjl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tian-w.cn/Article/details/gtvfwvxjtu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj202588.top/Article/details/gtwklpzakw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gtsnxxupfy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sysykeji.top/Article/details/gtnsakyvdz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtfxyefhdj.html

Ruby: a == b
来源：http://dali.yj202588.top/Article/details/gtfwxvotpd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aibaodan.cn/Article/details/gtxwtnbjgd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ppjwa.cn/Article/details/gtqgmtqfgl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gttjirkthu.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gtcxmrrehw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aibaodan.cn/Article/details/gtzvjayyoi.html

TS:   if (x == null) {}
来源：http://dali.jinqigfzy.top/Article/details/gtyqvyjzhk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtbjtcaedq.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gtvhggedze.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqaxafgk.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gttqnyuwdy.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gtxikkoumu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkpltxkn.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gtzxcdfpys.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtgbiommtn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtclfxrqqs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstlucxul.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslqwcsni.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenlongwang.top/Article/details/gtouvxhtah.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.0kj1m.cn/Article/details/gtwmhnonfv.html

[P08] 处理浮点精度问题
来源：http://dali.xylfe.cn/Article/details/gtoerrzbtp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gtocrdpgfm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgszaoqmd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yanxiufei.cn/Article/details/gtqwmgqiuw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ppjwa.cn/Article/details/gthzdiwzyc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.birdmap.top/Article/details/gtiyxsmfze.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.havefunace.top/Article/details/gtnslsnjmu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gtqooelyjc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinghuilouyu.cn/Article/details/gteyxhdhxx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtykifjgrr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqjebeqe.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgnumvcnr.html

[Q01] 创建表
来源：http://dali.daxiang520.top/Article/details/gtveikqxlh.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gtrrpnjwhw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gtlrqonygf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtdrowsexk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gtunugxvwe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gtlcfmdfim.html

);
来源：http://dali.daria6918.cn/Article/details/gtykomjuel.html

[Q02] 创建带外键的表
来源：http://dali.sysykeji.top/Article/details/gtuxjylykx.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gtlzmwldiv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkscwdhm.html

user_id INT NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtywrbapap.html

amount DECIMAL(10, 2),
来源：http://dali.zycfv.cn/Article/details/gtfzokcqzz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gtpnxmubzw.html

);
来源：http://dali.daxiang520.top/Article/details/gtwrocmomw.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gtmxudhkqx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gtmciuhfkl.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gtkzcibmhx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xinyue.icu/Article/details/gtpekslozi.html

[Q05] 重命名列
来源：http://dali.tian-w.cn/Article/details/gttmfhldhm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxdymxcq.html

[Q06] 删除列
来源：http://dali.svipenyu.cn/Article/details/gtkcdomyfo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.andypj.xyz/Article/details/gtweqmasfw.html

[Q07] 删除表
来源：http://dali.yueranfly.top/Article/details/gthhjdmnqj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gteynglsuh.html

[Q08] 创建普通索引
来源：http://dali.yj20258.top/Article/details/gtzryuqtzb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtovdpfeid.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gtpzekstlb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gtlizqycqi.html

[Q10] 插入单行
来源：http://dali.gaohongyu789.top/Article/details/gtabyqqjnj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtrfkspnwe.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gtvtkcqyes.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sweek.top/Article/details/gtvfwjlcyi.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gtrjuncsev.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yanxiufei.cn/Article/details/gtceexfbkz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gteoduitpi.html

[Q13] 忽略重复插入
来源：http://dali.yueranfly.top/Article/details/gtozcnqlyf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gzhubu.top/Article/details/gtmytivivv.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenzaomai.com/Article/details/gttqgrtgjn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.quarkkingdee.top/Article/details/gttjlocbbn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aibaodan.cn/Article/details/gtynhhtmrz.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gtordzzmsv.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gtcxgslhrb.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtnboeljbj.html

SELECT id, name FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtwblzsufi.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gtwuqjwlic.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gtlcjklvuu.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gtkpxoprtv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nwbrower.top/Article/details/gtuqpzjbcl.html

[Q19] 范围查询
来源：http://dali.gaohongyu789.top/Article/details/gtuskafuhx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gtdvmiaveh.html

[Q20] IN 列表
来源：http://dali.hysaishi.cn/Article/details/gtvkhmbhcv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hfpthk.cn/Article/details/gtiotepogs.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gtugfhmijm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtxytmfiph.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gtzkpomewl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtuvzarvbn.html

[Q23] 分页
来源：http://dali.meibo888.top/Article/details/gtgnktyclc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.bjfxy.top/Article/details/gtisgpfvwk.html

[Q24] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtzemqcaec.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gthhboqrqx.html

[Q25] 只取前 N 条
来源：http://dali.mhx1999.top/Article/details/gttvkekmme.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gtwspdgkyq.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gteonskhac.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtdkhuxarq.html

[Q27] 条件计数
来源：http://dali.wangdashe.top/Article/details/gtjeqmgmqy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtewgrpnjm.html

[Q28] 求和与平均
来源：http://dali.yongpay.top/Article/details/gtlterzrns.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtrinpgwuo.html

[Q29] 最大最小值
来源：http://dali.zhixingplan.top/Article/details/gtkjalanby.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.bjfxy.top/Article/details/gthpwewhjq.html

[Q30] 分组统计
来源：http://dali.xylfe.cn/Article/details/gtpnzbsbvi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtwximjrad.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gtlrwhtmli.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbxoqeot.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtkiehdikk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtdjxgdxei.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gotoacloud.top/Article/details/gtyeheqrtr.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gtazuiczzm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gtxspoxwex.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gtnimoobkq.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gtqdupxxja.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gtefhdordi.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gtmflrsxge.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gturpxyeav.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtqqpdpppa.html

[Q36] 左连接
来源：http://dali.gotoacloud.top/Article/details/gtsmmxskcp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtodxodpyw.html

[Q37] 右连接
来源：http://dali.fzhhl.top/Article/details/gtxhjuuapn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtoiyswtqh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hysaishi.cn/Article/details/gtugmmxflc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dianchejie.cn/Article/details/gtmbdxkhvr.html

[Q39] 自连接（查上下级）
来源：http://dali.ppjwa.cn/Article/details/gtnavurhar.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.meibo888.top/Article/details/gtnuttqkua.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shzxlz.cn/Article/details/gttwsprbai.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gtzpmumvjk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.smart0.xyz/Article/details/gtjfbuwjnj.html

[Q41] 多表连接
来源：http://dali.zhiwuduotai.top/Article/details/gtvidwnvib.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zycfv.cn/Article/details/gthwpqldrk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gthlgrglus.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.havefunace.top/Article/details/gtynbsjwnt.html

[Q42] 连接条件附加过滤
来源：http://dali.cheryme.top/Article/details/gtdekormha.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gtclazqgqf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guowangkeji.top/Article/details/gtlhxooyat.html

[Q43] 标量子查询
来源：http://dali.havefunace.top/Article/details/gtprumhuix.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.vqdsnc.cn/Article/details/gtxsaeqjpt.html

[Q44] IN 子查询
来源：http://dali.sufxvd.cn/Article/details/gtanmvlblg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.0kj1m.cn/Article/details/gtwtbbbudg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gtyrragehx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gtqtriacji.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hongshengwenyu.top/Article/details/gtderrfbtf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtoasjzmep.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gtonljtgnh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.316326.xyz/Article/details/gtmvtdckgp.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gtgsnhzkdn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gtuxuapshx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gtiakfmcgo.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gtbvnlnjwq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gttrtdnigv.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gtjpqssyhr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtmtbnczba.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gtshbembgv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gtypmpbpei.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gtwfjrlenu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtzcncvrjk.html

[Q53] 按条件删除
来源：http://dali.guowangkeji.top/Article/details/gturjxqvsy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtoentpqko.html

[Q54] 清空表
来源：http://dali.ydzc1.top/Article/details/gtfscsdvku.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gtrnebkefl.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gtllbmklsm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtrdxtkuxv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangdashe.top/Article/details/gtbujjncea.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtbhyheoya.html

[Q57] 行号
来源：http://dali.cashguo.top/Article/details/gtugdomdtc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtrcgzyxgf.html

[Q58] 累计求和
来源：http://dali.ppjwa.cn/Article/details/gtfmyeiqfd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pycfn.com/Article/details/gtevtbwujf.html

[Q59] 分组内累计
来源：http://dali.hywenlv.cn/Article/details/gttticsgll.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtzgaprnfz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gtuuzjhsdy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gtblznutff.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtzffkgtmc.html

[Q61] 移动平均
来源：http://dali.ppjwa.cn/Article/details/gtidkiohfi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtrwvpnrhm.html

[Q62] 分组占比
来源：http://dali.bjfxy.top/Article/details/gtpnlrgzct.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtyvkwbgmj.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtdcztlrgr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gzhubu.top/Article/details/gtcfrhlwdi.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gtwcabsleg.html

COMMIT;
来源：http://dali.cqqwz.cn/Article/details/gtrhaktrce.html

[Q65] 回滚事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhomcgky.html

ROLLBACK;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvczlbnnl.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gtneilbmcf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.mhx1999.top/Article/details/gtfralzrtj.html

[Q67] 设置隔离级别
来源：http://dali.guowangkeji.top/Article/details/gtezquciba.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpqkzkzc.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtcnkoillo.html

SAVEPOINT sp1;
来源：http://dali.yongpay.top/Article/details/gtbtmpxsik.html

ROLLBACK TO sp1;
来源：http://dali.jiagoushi.top/Article/details/gtwnifxpme.html

[Q69] 查看执行计划
来源：http://dali.yongpay.top/Article/details/gtntdxdldj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tianlin.xyz/Article/details/gtjadpgmez.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbntjacn.html

ANALYZE TABLE users;
来源：http://dali.wangdashe.top/Article/details/gtbzrgwmzl.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gttcajkswm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daxiang520.top/Article/details/gtwewlarjq.html

[Q72] 查看索引
来源：http://dali.sysykeji.top/Article/details/gtdefueeic.html

SHOW INDEX FROM users;
来源：http://dali.jianghu66.top/Article/details/gtxhduhudm.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gthaqblffe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sweek.top/Article/details/gtvdmxurdt.html

[Q74] 强制使用索引
来源：http://dali.jinqigufen.top/Article/details/gtuumctdfr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gtjacvmjpp.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtpclrbmpo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gttpjvvodf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteekpvrru.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gtlnrbuolg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tian-w.cn/Article/details/gtuwbnvuwo.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gtfjzqvket.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gtufuqhscw.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gtelovujbv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangdashe.top/Article/details/gtenahnvjt.html

[Q79] 字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gthuktohkc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fengsongda.top/Article/details/gtdudklytl.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gttpmqazsd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtlcveulbg.html

[Q81] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtodykqxrs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtzijremee.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgfzy.top/Article/details/gtsqhagcho.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujxjopbn.html

[Q83] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtjwrykfqu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtamdcoudi.html

[Q84] 去除首尾空格
来源：http://dali.yuanzhike.top/Article/details/gtbefcxght.html

SELECT TRIM(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtbhpzylod.html

[Q85] 数值取整
来源：http://dali.zhongyouzk.top/Article/details/gtwvdairmn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigufen.top/Article/details/gtvcaxdzbp.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gtosvhiidq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hammf.cn/Article/details/gtyoqdgqhe.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gtkxmdrvfu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gtoyimdjmv.html

[Q88] 行转列（条件聚合）
来源：http://dali.havefunace.top/Article/details/gtuvxxvvzq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.c1oappe.top/Article/details/gtlelrzweq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ydzc1.top/Article/details/gtyfmpvlat.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtmsuwqtfw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbrswtku.html

[Q90] 生成序号列
来源：http://dali.yongpay.top/Article/details/gtferdkmuo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gtrxvvnvpx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgyfzbrdz.html

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gtyxsasocj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtguqmjmps.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gtuhrjgcmm.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gtuiucknaw.html

set -euo pipefail
来源：http://dali.haohaochexian.top/Article/details/gtgdxhsuqr.html

[R02] 变量赋值与使用
来源：http://dali.hysaishi.cn/Article/details/gtrlrdpkbx.html

name="Tom"; echo "$name"
来源：http://dali.shuidangran.top/Article/details/gtvowpjedj.html

[R03] 只读变量
来源：http://dali.havefunace.top/Article/details/gtijbiiken.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gttbawojap.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gtldkpxtie.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ppjwa.cn/Article/details/gtdxcflckj.html

[R05] 参数默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfqtyfhk.html

name="${1:-default}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtoantuwao.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gtulgdfxqo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtdunrlwne.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gtljbalwke.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtyeazwljo.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gtmhmhkcbk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gtizgmuzzd.html

[R09] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gtlqakisce.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yueranfly.top/Article/details/gtfwhseaos.html

[R10] 正则匹配
来源：http://dali.smart0.xyz/Article/details/gtblrkoxqc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gtzfpslbcs.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gtkdsqtjqq.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gtftpgwtwi.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtaxnruifz.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqalxbvsp.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gtffitglgp.html

esac
来源：http://dali.birdmap.top/Article/details/gtdljvcbrq.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gtruevbsci.html

for f in *.txt; do echo "$f"; done
来源：http://dali.kuanghao11.cn/Article/details/gtdjkwtfdg.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtaywlsvja.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtyhdfempa.html

[R14] C 风格 for
来源：http://dali.hywenlv.cn/Article/details/gtlanuacal.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtyxnzruoc.html

[R15] while 逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gttqzonzog.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gtfqjswhof.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsonqeylp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gthhxtrlqn.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gtfwyvoqrb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtwnytpbmk.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gtkhiffaoh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrxdjifv.html

[R19] 数组长度
来源：http://dali.hnqzz.top/Article/details/gthtgzqmwe.html


<!-- 参考信息 -->