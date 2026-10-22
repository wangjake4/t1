代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shzxlz.cn/Article/details/gt2uvjrymnq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gt2tejqamze.html

[P03] 生成短随机字符串
来源：http://dali.chenzaomai.com/Article/details/gt2wfemqtft.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tian-w.cn/Article/details/gt2txhkwlng.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmcjxbyb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2voncfabq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gt2pxarkdfa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenzaomai.com/Article/details/gt2rqgjikfj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgfzy.top/Article/details/gt2sslfhrkd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffiudvlx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gt2ufxybkvo.html

[P04] 求长度
来源：http://dali.ybcxt.top/Article/details/gt2nbtjvppq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwjjcjgd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2njxgtldq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gt2lqxfzsfg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnilloxg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ppjwa.cn/Article/details/gt2jfucfcwi.html

Go:   len(arr);  len(m)
来源：http://dali.quarkkingdee.top/Article/details/gt2dwzxzchl.html

Ruby: x.length;  x.size
来源：http://dali.ybcxt.top/Article/details/gt2kntjrsgc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2ugobqxtp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xinyue.icu/Article/details/gt2vkzgrhvz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.9152youxi.cn/Article/details/gt2ydtaaqxn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yueranfly.top/Article/details/gt2yknfamwq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gaohongyu789.top/Article/details/gt2xjvbcwnd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.snrcjt.cn/Article/details/gt2svxadbhh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.0kj1m.cn/Article/details/gt2juikwmss.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2sdhikztj.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gt2ogxrvfdi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gt2jrejcskn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigfzy.top/Article/details/gt2fwccmfnl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tian-w.cn/Article/details/gt2dscabbtt.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gt2doxspwoj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgfagvzt.html

TS:   if (x == null) {}
来源：http://dali.dashuyun.cn/Article/details/gt2dkfhhvcu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2fuejqnhx.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gt2nmicdpev.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gldrldng.html

C#:   if (x is null) {}
来源：http://dali.yuxming.cn/Article/details/gt2cndpklys.html

[P07] 防抖与节流
来源：http://dali.jinqigfzy.top/Article/details/gt2ybnoomgr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnxiangtu.top/Article/details/gt2ufxdszmo.html

PHP:  // 手写时间戳比较
来源：http://dali.svipenyu.cn/Article/details/gt2dsazevfz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gt2uqptzjsp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gt2rdjsiyvz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.0kj1m.cn/Article/details/gt2halkhwgl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigfzy.top/Article/details/gt2rwxflsht.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shzxlz.cn/Article/details/gt2qawgbjet.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gt2huztcmwj.html

[P08] 处理浮点精度问题
来源：http://dali.ydzc1.top/Article/details/gt2azftouwq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.aibaodan.cn/Article/details/gt2zyhucwqa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gt2medpzlml.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258888.top/Article/details/gt2mkvdpqax.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gt2rtqigbwq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.bjfxy.top/Article/details/gt2dtpfzqtx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ybcxt.top/Article/details/gt2svduasjj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gt2qmjzigob.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gt2rdmyeasb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2uomiouxh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nwbrower.top/Article/details/gt2qhctxadx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2vvrepxfi.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gt2uribhacj.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gt2zoevysgy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gt2ikpzslgk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gt2ntvludpl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gt2akrcxdoz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuxming.cn/Article/details/gt2moqzgjkx.html

);
来源：http://dali.hysaishi.cn/Article/details/gt2ecczulsn.html

[Q02] 创建带外键的表
来源：http://dali.cheryme.top/Article/details/gt2torcwygf.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gt2typfrxfy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gt2fvqqqufv.html

user_id INT NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oehqggmv.html

amount DECIMAL(10, 2),
来源：http://dali.yanxiufei.cn/Article/details/gt2llquaoii.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dufporke.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2jrwnhbsg.html

[Q03] 增加列
来源：http://dali.haohaochexian.top/Article/details/gt2hhllongz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gaohongyu789.top/Article/details/gt2zruxxkfy.html

[Q04] 修改列类型
来源：http://dali.shzxlz.cn/Article/details/gt2bnrojprc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guannengcc.top/Article/details/gt2heyiscbu.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gt2vlcebsws.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gt2uecsjsuf.html

[Q06] 删除列
来源：http://dali.cqqwz.cn/Article/details/gt2hzfpjqpa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gt2fbgkaruu.html

[Q07] 删除表
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdnkkvzk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ehwqpu.com/Article/details/gt2umonurmf.html

[Q08] 创建普通索引
来源：http://dali.hfpthk.cn/Article/details/gt2pgppbbnm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gt2igvbysfn.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovqhcsgo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gt2ulqfjbeb.html

[Q10] 插入单行
来源：http://dali.ivvv.top/Article/details/gt2gcxgeyyu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwnsdetk.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gt2jcemrgtm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xylfe.cn/Article/details/gt2jruzxlzz.html

[Q12] 插入后取自增 ID
来源：http://dali.wangdashe.top/Article/details/gt2topzqqgr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gt2nvgfrvms.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gt2ijzvdjtq.html

[Q13] 忽略重复插入
来源：http://dali.pycfn.com/Article/details/gt2yqalzkmi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpsbbrl.html

[Q14] 存在则更新（upsert）
来源：http://dali.meibo888.top/Article/details/gt2ukdoiwac.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gt2sviubyhg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubrqjujx.html

[Q15] 查询全部
来源：http://dali.iojbl.cn/Article/details/gt2zssjeqob.html

SELECT * FROM users;
来源：http://dali.cheryme.top/Article/details/gt2eyidluny.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gt2psjdmkwy.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2rwpbtuhd.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gt2zsbfnjho.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.c1oappe.top/Article/details/gt2cfojfdaz.html

[Q18] 模糊匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtuzioga.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cheryme.top/Article/details/gt2tssdjazl.html

[Q19] 范围查询
来源：http://dali.yj20258.top/Article/details/gt2ktvjnmrc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gt2zmxvaxkh.html

[Q20] IN 列表
来源：http://dali.yj202588.top/Article/details/gt2wwogbhtn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ydzc1.top/Article/details/gt2xmhqvxye.html

[Q21] 空值判断
来源：http://dali.sufxvd.cn/Article/details/gt2aesovddb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hysaishi.cn/Article/details/gt2jkhowqhc.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gt2voimohag.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sysykeji.top/Article/details/gt2unyoosyr.html

[Q23] 分页
来源：http://dali.quarkkingdee.top/Article/details/gt2bsyusvgm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gt2qdjivnhm.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gt2fiovjsix.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gt2hinzgxva.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsbwrpue.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhixingplan.top/Article/details/gt2ggohwyyv.html

[Q26] 计数
来源：http://dali.snrcjt.cn/Article/details/gt2ynayzwls.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gcbvihyq.html

[Q27] 条件计数
来源：http://dali.zycfv.cn/Article/details/gt2yhgsrkji.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2vdyessto.html

[Q28] 求和与平均
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrvklrvw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2jhtgrdle.html

[Q29] 最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mlycvjqy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2jhoeklue.html

[Q30] 分组统计
来源：http://dali.cdnleiting.top/Article/details/gt2slkbwcda.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gt2qfmlhqxp.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gt2ikxkpdvq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yvedp.cn/Article/details/gt2ovugqqal.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2nhkojkpp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gt2dbznwocf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gt2jobgtoge.html

[Q33] 多列分组
来源：http://dali.cucudq.cn/Article/details/gt2tuopjqho.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gt2bwzivmrl.html

[Q34] 每组取第一条
来源：http://dali.gotoacloud.top/Article/details/gt2nflrehzl.html

SELECT * FROM (
来源：http://dali.zhixingplan.top/Article/details/gt2ddxzcpyo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tunnxewp.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gt2iulclccw.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gt2htyoqruu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gt2yoqypksr.html

[Q36] 左连接
来源：http://dali.jinqigufen.top/Article/details/gt2joefslcg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gt2nstxhuat.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gt2svfaperm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xylfe.cn/Article/details/gt2ipicmpyh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shzxlz.cn/Article/details/gt2fiooeqgg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aizwys.cn/Article/details/gt2roagtztc.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gttpoxlj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gt2gfesdevu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigufen.top/Article/details/gt2wxryhyme.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shzxlz.cn/Article/details/gt2pcqssxbo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shuidangran.top/Article/details/gt2cosleize.html

[Q41] 多表连接
来源：http://dali.zdqjudy.top/Article/details/gt2lzmjlzqm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tian-w.cn/Article/details/gt2ieifyglw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.meibo888.top/Article/details/gt2vnpaszcx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbpulltn.html

[Q42] 连接条件附加过滤
来源：http://dali.yangfankeji.com/Article/details/gt2vbevjvkz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewwhnlvz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhengqikj.top/Article/details/gt2qrosgjva.html

[Q43] 标量子查询
来源：http://dali.jiagoushi.top/Article/details/gt2wdocrpev.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gt2dgrjkokn.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gt2bwonlcjk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gt2jcqgnfqs.html

[Q45] EXISTS 判断存在
来源：http://dali.sufxvd.cn/Article/details/gt2mtscxyol.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gt2rqcqitra.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2eonzxhxo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gt2aiwvvhbo.html

[Q47] 与平均值比较
来源：http://dali.yangfankeji.com/Article/details/gt2ftofirhx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258.top/Article/details/gt2gfgpdsdk.html

[Q48] CTE 公用表表达式
来源：http://dali.iojbl.cn/Article/details/gt2wgxbochg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.9152youxi.cn/Article/details/gt2qqkymsml.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zycfv.cn/Article/details/gt2trjjkpnu.html

[Q49] 更新单行
来源：http://dali.zdqjudy.top/Article/details/gt2yrtzyqxu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gt2jhulaqdm.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpmeilj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gt2rhfiobts.html

[Q51] 用子查询更新
来源：http://dali.guowangkeji.top/Article/details/gt2hcufbegw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2jwvcsesw.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gt2twgzoxsx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gt2wiixbtrw.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gt2gocnubof.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gt2bjxjrgma.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gt2cwzfbdym.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gt2hlflxqio.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gt2zbqmsotb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gt2vjqeriug.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yueranfly.top/Article/details/gt2clzngleq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gt2atiymyhy.html

[Q57] 行号
来源：http://dali.jinqigufen.top/Article/details/gt2hwtffogq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2rpvanffz.html

[Q58] 累计求和
来源：http://dali.yj20258888.top/Article/details/gt2bcyypqge.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2lwvucntt.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gt2eusbukbe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jegbxppe.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gt2uctkvpwy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgufenzy.top/Article/details/gt2inyvuhqg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2echnigmh.html

[Q61] 移动平均
来源：http://dali.gotoacloud.top/Article/details/gt2pzexsblx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2npapxbsx.html

[Q62] 分组占比
来源：http://dali.yongpay.top/Article/details/gt2dspwiwsm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2aodegrec.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gt2vpsfabtc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gt2lulwafhp.html

[Q64] 提交事务
来源：http://dali.316326.xyz/Article/details/gt2kqjongox.html

COMMIT;
来源：http://dali.jqgufenzy.top/Article/details/gt2zmlekssz.html

[Q65] 回滚事务
来源：http://dali.nwbrower.top/Article/details/gt2bynhykfm.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gt2rlegmnwd.html

[Q66] 行锁查询
来源：http://dali.redwolf501.top/Article/details/gt2ywsbraax.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gt2uojyoocl.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gt2iykqzetj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gotoacloud.top/Article/details/gt2veoayhhk.html

[Q68] 保存点
来源：http://dali.sufxvd.cn/Article/details/gt2crsdrhvh.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gt2gxhgzlaq.html

ROLLBACK TO sp1;
来源：http://dali.chenzaomai.com/Article/details/gt2ciocbdgu.html

[Q69] 查看执行计划
来源：http://dali.0kj1m.cn/Article/details/gt2guoiwjtg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hammf.cn/Article/details/gt2kzzrvedo.html

[Q70] 更新统计信息
来源：http://dali.jqgufenzy.top/Article/details/gt2guuuvjeb.html

ANALYZE TABLE users;
来源：http://dali.yj20258.top/Article/details/gt2ebuxpccu.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gt2xcnchshm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ydzc1.top/Article/details/gt2lyogfohh.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gt2erlldbju.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2xlmekfrl.html

[Q73] 查看表状态
来源：http://dali.ybcxt.top/Article/details/gt2etwvnwbl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gt2cdtakkgs.html

[Q74] 强制使用索引
来源：http://dali.sweek.top/Article/details/gt2bdutgsbn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gt2kaiqmysj.html

[Q75] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffailwqi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2vgebvwrg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuxming.cn/Article/details/gt2heiwcjnp.html

[Q76] 按天统计
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnakicda.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.iojbl.cn/Article/details/gt2giuagsbm.html

[Q77] 时间加减
来源：http://dali.gogol.net.cn/Article/details/gt2llixaxbj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gt2noyfhoqq.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gt2zqqkawfl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdqthvwg.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gt2wbfyrewj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gt2znllbabh.html

[Q80] 字符串截取
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrxrrsha.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2lutjahlt.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfcusqs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2fkxishuv.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258888.top/Article/details/gt2dkyeotze.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2gvpdwppl.html

[Q83] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2kpwwrhgj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2ovolojdw.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjayqypo.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2qaogfprx.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gt2zvrrgcad.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcgsupsu.html

[Q86] 读取 JSON 字段
来源：http://dali.shzxlz.cn/Article/details/gt2qsmotnzg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gt2qkbmidhb.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gt2tptwdztx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dashuyun.cn/Article/details/gt2fighqdyo.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gt2zsuckqkh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gt2vyfatrwv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2iwumuxfd.html

[Q89] 判断表是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzyapcoe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yueranfly.top/Article/details/gt2qflobajf.html

[Q90] 生成序号列
来源：http://dali.sweek.top/Article/details/gt2iloztcjp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuanzhike.top/Article/details/gt2pszjgisy.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2pndczirp.html

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gt2dnambqss.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2jqofkdoc.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gt2brvgoaxd.html

#!/usr/bin/env bash
来源：http://dali.pycfn.com/Article/details/gt2ofmptpzw.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjewkymz.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gt2yxdabfus.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gt2sftsdssk.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gt2zdnloljf.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gt2dnfwhmsd.html

[R04] 位置参数
来源：http://dali.chenzaomai.com/Article/details/gt2zcvxfjfn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gt2huveocoo.html

[R05] 参数默认值
来源：http://dali.jianghu66.top/Article/details/gt2fkgcmegk.html

name="${1:-default}"
来源：http://dali.shzxlz.cn/Article/details/gt2bmydbvke.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2aggydpdg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gt2jjbmuicd.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zwleygvm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2szlxwvsb.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gt2shjdpckg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.meibo888.top/Article/details/gt2sadmlqps.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gt2qcquhlej.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yvedp.cn/Article/details/gt2xqypbmhy.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gt2rdndosgg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ybcxt.top/Article/details/gt2ynctuuej.html

[R11] case 多分支
来源：http://dali.bjfxy.top/Article/details/gt2knmasiuq.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gt2zmqdnvef.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2aewlhtxu.html

stop)  echo "停止" ;;
来源：http://dali.yvedp.cn/Article/details/gt2loislbzw.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xgblhwtc.html

esac
来源：http://dali.yonumen.top/Article/details/gt2exxhmdye.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gt2jhaitzfe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gt2gylcwovt.html

[R13] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gt2rgyoefoh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gt2mcwmdefl.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gt2nhwsmubf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gt2dbitbgmp.html

[R15] while 逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iukrytua.html


<!-- 参考信息 -->