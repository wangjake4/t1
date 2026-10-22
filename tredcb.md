代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gt2efnazair.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gt2ihaazohe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gt2rnvesgnz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ppjwa.cn/Article/details/gt2tzbisvkm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangshuangyany.cn/Article/details/gt2tuiwlght.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.svipenyu.cn/Article/details/gt2ixxyhjkv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hysaishi.cn/Article/details/gt2emmqvpmp.html

[P04] 求长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjpxwbsb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.smart0.xyz/Article/details/gt2ippmhfsg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2etcdtdvm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gt2hkgryiie.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gt2uorlrcax.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gt2swbzjunr.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2odpufzew.html

Ruby: x.length;  x.size
来源：http://dali.xuanzx.com/Article/details/gt2qyhlpusq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gt2lttystxi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuetiantiany.cn/Article/details/gt2udvjogfx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gt2hgmoxlpd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gt2hwgqinlt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangshuangyany.cn/Article/details/gt2voumxfdv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gt2zhlkizqm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hammf.cn/Article/details/gt2moqzjeso.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2zlnsxdpp.html

Ruby: a == b
来源：http://dali.gzhubu.top/Article/details/gt2pothysxa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sufxvd.cn/Article/details/gt2qphbnuiv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hywenlv.cn/Article/details/gt2szfebtvk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.vqdsnc.cn/Article/details/gt2linnzrpq.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gt2uqmgtmrk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jiagoushi.top/Article/details/gt2cgvhschc.html

TS:   if (x == null) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2bnbldzvs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gt2rntzaibu.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gt2luvvkgsp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eicprxls.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gt2auaxvrjo.html

[P07] 防抖与节流
来源：http://dali.zdqjudy.top/Article/details/gt2sxscjght.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gt2gbxnenro.html

PHP:  // 手写时间戳比较
来源：http://dali.0kj1m.cn/Article/details/gt2tqzfyhts.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gt2zobnrhoh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2dcrziupe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.snrcjt.cn/Article/details/gt2svjcgyuo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hfpthk.cn/Article/details/gt2brgrbhxf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zycfv.cn/Article/details/gt2xfzdfrkm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.c1oappe.top/Article/details/gt2edfobotj.html

[P08] 处理浮点精度问题
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqsgrtcw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gt2yizwldle.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.316326.xyz/Article/details/gt2icfatvbv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gt2fjikiofi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gt2avizidmz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.birdmap.top/Article/details/gt2efafyzax.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xylfe.cn/Article/details/gt2tlacpnce.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cdnleiting.top/Article/details/gt2zopsssdt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gt2iuazoffp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ssjabavf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fzhhl.top/Article/details/gt2tdbxahgt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ldcnbvzp.html

[Q01] 创建表
来源：http://dali.wangdashe.top/Article/details/gt2jdkzoudm.html

CREATE TABLE users (
来源：http://dali.guannengcc.top/Article/details/gt2uwnzmwbr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhiaixkp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gt2mkfimmvx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdpprrgr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybmijrqi.html

);
来源：http://dali.haohaochexian.top/Article/details/gt2uuyrvbik.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gt2sjrhqsxb.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gt2mubmqisa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gt2vjetiiob.html

user_id INT NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gt2aukvzbsu.html

amount DECIMAL(10, 2),
来源：http://dali.tanke756.top/Article/details/gt2knmllmap.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gt2sysavuro.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2bbjzialz.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gt2sazphtph.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gt2zklrwgwu.html

[Q04] 修改列类型
来源：http://dali.jiagoushi.top/Article/details/gt2jgavhdxg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.vqdsnc.cn/Article/details/gt2zeiadhom.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gt2qhfqizcd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2falhycld.html

[Q06] 删除列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnuiyrsy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sxryk.cn/Article/details/gt2yirodmkt.html

[Q07] 删除表
来源：http://dali.shuidangran.top/Article/details/gt2hqvyuzic.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hfpthk.cn/Article/details/gt2ifgsseev.html

[Q08] 创建普通索引
来源：http://dali.tianlin.xyz/Article/details/gt2xocxfyvj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gt2jufbsmcs.html

[Q09] 创建唯一索引
来源：http://dali.ivvv.top/Article/details/gt2lzpeuvse.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gt2qaxoxaxj.html

[Q10] 插入单行
来源：http://dali.hysaishi.cn/Article/details/gt2glkutwgd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.9152youxi.cn/Article/details/gt2eruldnnj.html

[Q11] 一次插入多行
来源：http://dali.jyoumei.cn/Article/details/gt2yrkelavb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gt2hnsdlydo.html

[Q12] 插入后取自增 ID
来源：http://dali.ydzc1.top/Article/details/gt2geeiousg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hfpthk.cn/Article/details/gt2prgmvtwk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shzxlz.cn/Article/details/gt2kuiarcgk.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gt2vqzotatr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gt2awlaqzkp.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gt2jaxsdrpn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ehwqpu.com/Article/details/gt2yfjljbts.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gt2ocnpnpyk.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gt2jaieyqgw.html

SELECT * FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2gubxuoof.html

[Q16] 查询指定列
来源：http://dali.cashguo.top/Article/details/gt2hnjtyfju.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2kvhbklqv.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gt2yqzklrsm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2pdbdjhje.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gt2nzkjydjb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgufenzy.top/Article/details/gt2mufzmdtk.html

[Q19] 范围查询
来源：http://dali.jqgfzy.top/Article/details/gt2kfnewunx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hywenlv.cn/Article/details/gt2icplfpah.html

[Q20] IN 列表
来源：http://dali.aizwys.cn/Article/details/gt2lkgtelqm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2tmeiuxcy.html

[Q21] 空值判断
来源：http://dali.jqgfzy.top/Article/details/gt2dpbxevrg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuanzx.com/Article/details/gt2unwjuowu.html

[Q22] 排序
来源：http://dali.jiagoushi.top/Article/details/gt2eyddwbhw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gogol.net.cn/Article/details/gt2ampmmqgr.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gt2beatxmqz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.snrcjt.cn/Article/details/gt2bmjjaord.html

[Q24] 去重
来源：http://dali.gzhubu.top/Article/details/gt2nymfjgkz.html

SELECT DISTINCT city FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2twcxwoyy.html

[Q25] 只取前 N 条
来源：http://dali.shangyingyoupin.top/Article/details/gt2alamrban.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigfzy.top/Article/details/gt2lobimztm.html

[Q26] 计数
来源：http://dali.sweek.top/Article/details/gt2bxhefehd.html

SELECT COUNT(*) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2fjxpszok.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ofazikbv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ttbwqysb.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gt2qwioijeh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2tcwtrppz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrqabff.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2wswnjlli.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gt2pnfgjnbt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xzluntou.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gt2pvcopjst.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gzhubu.top/Article/details/gt2gffnuiqn.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2tpkcmhqx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gt2uonceylb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gt2simwoatz.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gt2tucsqhwl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cucudq.cn/Article/details/gt2cfcwqxwj.html

[Q34] 每组取第一条
来源：http://dali.gotoacloud.top/Article/details/gt2szeiligo.html

SELECT * FROM (
来源：http://dali.yvedp.cn/Article/details/gt2ehtkcrgv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhongyouzk.top/Article/details/gt2mldrkpzp.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2dexzpjxe.html

[Q35] 内连接
来源：http://dali.yongpay.top/Article/details/gt2mzelxguq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gt2rocrhvvs.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cncdrcsh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gt2nsavnqmc.html

[Q37] 右连接
来源：http://dali.cdnleiting.top/Article/details/gt2kbcsazwv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gt2ufyldhhz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhixingplan.top/Article/details/gt2ahqyipph.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zjmoueeb.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gt2lcovtfsc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dashuyun.cn/Article/details/gt2eencspbd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gt2dbudatnt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gt2yxrhcrys.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gt2yaqzkuhq.html

[Q41] 多表连接
来源：http://dali.cheryme.top/Article/details/gt2ecjaxjey.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zdqjudy.top/Article/details/gt2iskcqosc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gt2opvaccyg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gt2nhoqzkcd.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gt2hbeaobor.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenjidiqi.icu/Article/details/gt2mletxhnh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gt2uwfwhglx.html

[Q43] 标量子查询
来源：http://dali.birdmap.top/Article/details/gt2wtatsnug.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gt2tuwnyuht.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gt2bqtrmdxr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gt2azbzojng.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gt2wdhcyjkr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gt2mpnuuwbd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gt2ieusleaa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gt2ibucojvm.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gt2onrepvqc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gt2hsknrzdo.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gt2kvzjtyff.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gt2ziezqcxy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gt2kjcuychx.html

[Q49] 更新单行
来源：http://dali.jqgfzy.top/Article/details/gt2gvckxkbx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gt2zulatzam.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gt2xwidqfri.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nwbrower.top/Article/details/gt2hyssexhm.html

[Q51] 用子查询更新
来源：http://dali.jlsjyb.cn/Article/details/gt2gkmlirrd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hammf.cn/Article/details/gt2cwfskhgk.html

[Q52] 删除指定行
来源：http://dali.nwbrower.top/Article/details/gt2abuinbqf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2gqbiioer.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gt2fxsvaytg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aibaodan.cn/Article/details/gt2metbfahg.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gt2soeiadri.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gt2pdekzeuv.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gt2qtwwywhu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gt2zbrchrfn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxuanxn.top/Article/details/gt2ksthkbxs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gt2reretgqe.html

[Q57] 行号
来源：http://dali.jianghu66.top/Article/details/gt2tivccckv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gt2guoeezcx.html

[Q58] 累计求和
来源：http://dali.meibo888.top/Article/details/gt2urzthhru.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2acfzpjhf.html

[Q59] 分组内累计
来源：http://dali.chenzaomai.com/Article/details/gt2oyjibxhy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2nrvtlpwv.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gt2dkxiexhy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gt2vpiqzsct.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhlkbkqh.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gt2rfzugqty.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2molgxqrv.html

[Q62] 分组占比
来源：http://dali.c1oappe.top/Article/details/gt2hsgzfdnu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gt2logmhlhs.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gt2bpbuuqfx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gogol.net.cn/Article/details/gt2hgpvdrma.html

[Q64] 提交事务
来源：http://dali.xziqi.cn/Article/details/gt2yzcxxvzz.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gt2ewrbpjhs.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gt2irqvxtyh.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yezfiaxk.html

[Q66] 行锁查询
来源：http://dali.svipenyu.cn/Article/details/gt2bmutzpwh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gt2frulqhkg.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gt2gjbmryfj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzvptdtz.html

[Q68] 保存点
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvaihacj.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gt2ycxherth.html

ROLLBACK TO sp1;
来源：http://dali.jqgfzy.top/Article/details/gt2kffgfgbs.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gt2ovmbhjkf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.0kj1m.cn/Article/details/gt2zaiajvrx.html

[Q70] 更新统计信息
来源：http://dali.jqgufenzy.top/Article/details/gt2kyoczmlb.html

ANALYZE TABLE users;
来源：http://dali.yj202588.top/Article/details/gt2vimznvfn.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ezxoymkz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangshuangyany.cn/Article/details/gt2flxcehra.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gt2curgepmr.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2aypcsnog.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gt2pkegjlpr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gt2uankjmhm.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gt2svhrdmdn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gzhubu.top/Article/details/gt2hiesnbic.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gt2lhfamuta.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gnpynirm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gt2ihvkyfkm.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gt2lwvguxlg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gt2ekrwruny.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gt2bchdrytx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gt2zvulmiie.html

[Q78] 当前时间
来源：http://dali.yangfankeji.com/Article/details/gt2vrraqnhu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tianlin.xyz/Article/details/gt2wzbfalfb.html

[Q79] 字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gt2fzpbnxwj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gt2cbldqvkk.html

[Q80] 字符串截取
来源：http://dali.jinqigfzy.top/Article/details/gt2qpxexlbp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2yndrzhes.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gt2sypisopm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2apbelyqn.html

[Q82] 字符长度与字节长度
来源：http://dali.nwbrower.top/Article/details/gt2lbymcxyq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkenuuvf.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbifbuap.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2vdjasksk.html

[Q84] 去除首尾空格
来源：http://dali.hysaishi.cn/Article/details/gt2gitcgauw.html

SELECT TRIM(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2rxdgncnd.html

[Q85] 数值取整
来源：http://dali.cheryme.top/Article/details/gt2qjkiunvs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guannengcc.top/Article/details/gt2oxatbaxz.html

[Q86] 读取 JSON 字段
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvccovjz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gt2xxxnbmbr.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258.top/Article/details/gt2obmxxfma.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gt2waauwwqg.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvyhvwzx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zycfv.cn/Article/details/gt2hxlkghud.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2xxstbyrt.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gt2zzvvoprq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gt2lfichfhp.html

[Q90] 生成序号列
来源：http://dali.cucudq.cn/Article/details/gt2tfuhbayj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gt2uslzrnad.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rfkjdiac.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gt2esjnpwsu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2sgvqtqdg.html

[R01] shebang 与严格模式
来源：http://dali.yuanzhike.top/Article/details/gt2sanfbsdl.html

#!/usr/bin/env bash
来源：http://dali.yj20258.top/Article/details/gt2brvwspbr.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywvpfivh.html

[R02] 变量赋值与使用
来源：http://dali.c1oappe.top/Article/details/gt2bklgpgmx.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gt2jycmasmw.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gt2cjzkkosx.html

readonly PI=3.14
来源：http://dali.hnxiangtu.top/Article/details/gt2bfsgaujp.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2minnsgdc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gt2nnkruglp.html

[R05] 参数默认值
来源：http://dali.zhengqikj.top/Article/details/gt2sixhwzua.html

name="${1:-default}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2jmlpsrgf.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2jtfvnkhv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gt2volrlniz.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gt2wbdqqipd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2wwgfyelb.html

[R08] 数值比较
来源：http://dali.jlsjyb.cn/Article/details/gt2tjqrpkfx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cucudq.cn/Article/details/gt2vkewxcld.html

[R09] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gt2azczinme.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2tvwibhuw.html

[R10] 正则匹配
来源：http://dali.snrcjt.cn/Article/details/gt2sevfhpjw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2tikprruu.html

[R11] case 多分支
来源：http://dali.zhongyouzk.top/Article/details/gt2vvktjqxy.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gt2fiqmhffm.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2egpisgqo.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gt2psuchyom.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pgvfunkh.html

esac
来源：http://dali.hysaishi.cn/Article/details/gt2bxdbrmmu.html

[R12] for 遍历文件
来源：http://dali.aizwys.cn/Article/details/gt2zsytoypl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yonumen.top/Article/details/gt2gqzveket.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gt2knkicgrh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gt2lkgztkix.html

[R14] C 风格 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txhcwodz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gt2orwjvfcx.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2vaoxidgt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj202588.top/Article/details/gt2yaijnqno.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gt2ohgmmauh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2fgclwptw.html

[R17] 数组定义与取值
来源：http://dali.xuanzx.com/Article/details/gt2kbopjfyf.html


<!-- 参考信息 -->