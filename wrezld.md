代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhixingplan.top/Article/details/gt2rjxuauld.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2wikyyqcy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gt2ckubcqve.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.iojbl.cn/Article/details/gt2qkuvdfni.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gt2yogpbtfu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258.top/Article/details/gt2azcmsqzw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yanxiufei.cn/Article/details/gt2ndvoppmt.html

[P04] 求长度
来源：http://dali.jiagoushi.top/Article/details/gt2ihyocwel.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.quarkkingdee.top/Article/details/gt2sjcdxsge.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2xxbafapn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gt2sezvhmrh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gt2zgsyxlkf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2lrpajxzc.html

Go:   len(arr);  len(m)
来源：http://dali.sxryk.cn/Article/details/gt2wvvdqnrb.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gt2kentmfmw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gt2ylnbcytu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.havefunace.top/Article/details/gt2doseemuq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gt2vodxguvx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gt2ybndtyzj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gt2mcadeeyy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2oyhkmugm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gt2ijqdbqwu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2axdhuuzx.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gt2tfxfnprp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gt2nydzlozg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cdnleiting.top/Article/details/gt2pkivfghi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxinkj.top/Article/details/gt2plncxnpy.html

PHP:  if (empty($x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2igqxpkfv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nwbrower.top/Article/details/gt2yjyvarwh.html

TS:   if (x == null) {}
来源：http://dali.hnqzz.top/Article/details/gt2pjjzvpnd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gt2qijrrovh.html

Go:   if x == nil {}
来源：http://dali.cqqwz.cn/Article/details/gt2lkupeuqj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdwukemd.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gt2mmxazuin.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gt2dxnrsdpt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgufenzy.top/Article/details/gt2yxtswxzw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhongyouzk.top/Article/details/gt2racmwnvh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gt2ugtzyptj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gt2ntokimmp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gt2zigxogcm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cdnleiting.top/Article/details/gt2bpnjzsiw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gt2qubgvrvy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258.top/Article/details/gt2nvpjqzzq.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gt2hosscjjn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gt2guqyoztn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpovjqp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jyoumei.cn/Article/details/gt2kuexbona.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gt2zmhkmdue.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cqqwz.cn/Article/details/gt2dedqirvo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bufrqoiz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.316326.xyz/Article/details/gt2pcsdjnei.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ybcxt.top/Article/details/gt2rjevvifs.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2dykdatdl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zdqjudy.top/Article/details/gt2wvnivihc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhodosdd.html

[Q01] 创建表
来源：http://dali.gaohongyu789.top/Article/details/gt2yfpcgvwe.html

CREATE TABLE users (
来源：http://dali.shzxlz.cn/Article/details/gt2ouyiulbn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gt2uyfwdtgb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.snrcjt.cn/Article/details/gt2xclduzdf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hammf.cn/Article/details/gt2jyvmihcl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.mhx1999.top/Article/details/gt2tupgkhyv.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvpqvrfd.html

[Q02] 创建带外键的表
来源：http://dali.gaohongyu789.top/Article/details/gt2nlzdqymb.html

CREATE TABLE orders (
来源：http://dali.birdmap.top/Article/details/gt2ycdmhbmr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gt2srohlvyz.html

user_id INT NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gt2nlimwsyf.html

amount DECIMAL(10, 2),
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzyjiudz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujgvlnym.html

);
来源：http://dali.fzhhl.top/Article/details/gt2pesxyvqk.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gt2rjlbnghh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ppjwa.cn/Article/details/gt2tspvtztz.html

[Q04] 修改列类型
来源：http://dali.hywenlv.cn/Article/details/gt2ojemhmgz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gt2osoggrug.html

[Q05] 重命名列
来源：http://dali.xinyue.icu/Article/details/gt2wjwovhdw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gt2jpwfdgnn.html

[Q06] 删除列
来源：http://dali.hysaishi.cn/Article/details/gt2guvhzjnh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gogol.net.cn/Article/details/gt2ubxrqcqh.html

[Q07] 删除表
来源：http://dali.jlsjyb.cn/Article/details/gt2iyrnipfo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zycfv.cn/Article/details/gt2gwsognlc.html

[Q08] 创建普通索引
来源：http://dali.dianchejie.cn/Article/details/gt2ybkcdhsp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gt2zjevzpud.html

[Q09] 创建唯一索引
来源：http://dali.redwolf501.top/Article/details/gt2ezaiyqjf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gt2ahgneqts.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gt2srgzuyxj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2tkdvvgmm.html

[Q11] 一次插入多行
来源：http://dali.hammf.cn/Article/details/gt2zqxwavwn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gt2rqtlxdga.html

[Q12] 插入后取自增 ID
来源：http://dali.nwbrower.top/Article/details/gt2kgzimxce.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuanzx.com/Article/details/gt2reiphwjm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhengqikj.top/Article/details/gt2owohnrpi.html

[Q13] 忽略重复插入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbttmhip.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gt2usdurtog.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gt2vmqtvmot.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gt2fsmkpcjv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmindiha.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gt2jtpihfno.html

SELECT * FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2mjwxvzwt.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gt2vqgsifzy.html

SELECT id, name FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2hwesyjvo.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gt2obchugbp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gt2ljgbriqi.html

[Q18] 模糊匹配
来源：http://dali.xylfe.cn/Article/details/gt2sxxhgihp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gt2zykhzdsw.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gt2mgkniomc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hammf.cn/Article/details/gt2pvroybjt.html

[Q20] IN 列表
来源：http://dali.zdqjudy.top/Article/details/gt2owwvrbuc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yonumen.top/Article/details/gt2psbobcwx.html

[Q21] 空值判断
来源：http://dali.iojbl.cn/Article/details/gt2wgncyxqt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.vqdsnc.cn/Article/details/gt2zmcwhced.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffzlgefq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gt2itneuwcg.html

[Q23] 分页
来源：http://dali.smart0.xyz/Article/details/gt2yoylfvrp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2punctxau.html

[Q24] 去重
来源：http://dali.guowangkeji.top/Article/details/gt2dztnefwu.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2fgecixwc.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gt2vnoklwcd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dashuyun.cn/Article/details/gt2nhslbcso.html

[Q26] 计数
来源：http://dali.snrcjt.cn/Article/details/gt2mqzmrfxc.html

SELECT COUNT(*) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gphlpqxe.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gt2onxnzgda.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgafdojz.html

[Q28] 求和与平均
来源：http://dali.iojbl.cn/Article/details/gt2ahwhrikw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2imgjqomk.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gt2poerxhsw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2einuycxi.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gt2dmfwjfif.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2hjccxvxt.html

[Q31] 分组后过滤
来源：http://dali.9152youxi.cn/Article/details/gt2caajbegi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xssdmyzr.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2fdbbbwlz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gt2vwpzwpgk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gt2kckhotiv.html

[Q33] 多列分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zyiljyuf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gt2fikjjolb.html

[Q34] 每组取第一条
来源：http://dali.redwolf501.top/Article/details/gt2nppfysnh.html

SELECT * FROM (
来源：http://dali.ppjwa.cn/Article/details/gt2gexhmkoq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenzaomai.com/Article/details/gt2rozixslf.html

) t WHERE rn = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2ilbnigwd.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gt2rqgbkeen.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gt2upavyagr.html

[Q36] 左连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phsqitdr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gt2ljeaakvq.html

[Q37] 右连接
来源：http://dali.smart0.xyz/Article/details/gt2kcfwueus.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ybcxt.top/Article/details/gt2dkjabcms.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gt2opvcnhfe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guowangkeji.top/Article/details/gt2somlrflt.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2hueimkts.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.mhx1999.top/Article/details/gt2oqirswpl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xylfe.cn/Article/details/gt2wafybktc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.c1oappe.top/Article/details/gt2kcfpaaug.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daria6918.cn/Article/details/gt2lrpqpapf.html

[Q41] 多表连接
来源：http://dali.iojbl.cn/Article/details/gt2qeahkdic.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfkcymev.html

JOIN users u ON u.id = o.user_id
来源：http://dali.bjfxy.top/Article/details/gt2fogmqbfa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.haohaochexian.top/Article/details/gt2bujfngzs.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gt2bifwwehg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gt2tbwzznel.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gt2uhdsmmbk.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gt2swkyohbn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gt2cxhiocxx.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gt2kefwunjn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhoulong.xyz/Article/details/gt2nqikozxr.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gt2ghymedjf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gt2muamhoqr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.bjfxy.top/Article/details/gt2txhdvhuz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gt2qqjzlkyk.html

[Q47] 与平均值比较
来源：http://dali.xylfe.cn/Article/details/gt2smrsoqtb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnxiangtu.top/Article/details/gt2fwuyvhsu.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gt2reabtoea.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cucudq.cn/Article/details/gt2enrbpgwi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daxiang520.top/Article/details/gt2ujumlmzi.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gt2kjmejdmd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gt2khcnalav.html

[Q50] 批量更新
来源：http://dali.svipenyu.cn/Article/details/gt2widnwhte.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kjknnmzh.html

[Q51] 用子查询更新
来源：http://dali.yj20258.top/Article/details/gt2imuvwhpw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zygkbiyy.html

[Q52] 删除指定行
来源：http://dali.yj20258888.top/Article/details/gt2hpdywqhp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gt2epkostxf.html

[Q53] 按条件删除
来源：http://dali.jianghu66.top/Article/details/gt2ygrjthwd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shzxlz.cn/Article/details/gt2tduoxvax.html

[Q54] 清空表
来源：http://dali.jyoumei.cn/Article/details/gt2zfwgwiky.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gt2depifzgp.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gt2fhakivrt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gt2hjbxvdtn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gt2unabpkhj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daxiang520.top/Article/details/gt2fopglyyg.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gt2zijiephb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2ieaaqfvw.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gt2sycqujse.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2nkzmizay.html

[Q59] 分组内累计
来源：http://dali.meibo888.top/Article/details/gt2mnoknrwg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2dguenrty.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gt2gheiphtb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.andypj.xyz/Article/details/gt2rdnyabel.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2suatxaic.html

[Q61] 移动平均
来源：http://dali.zhixingplan.top/Article/details/gt2ogzxjycd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2qhnfetpm.html

[Q62] 分组占比
来源：http://dali.daria6918.cn/Article/details/gt2uxkamemw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gt2txhbnylh.html

[Q63] 开启事务
来源：http://dali.xylfe.cn/Article/details/gt2fzksfpwj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gt2gdiziipu.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gt2jozhivtq.html

COMMIT;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnqvhskn.html

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gt2njbdcziu.html

ROLLBACK;
来源：http://dali.wangshuangyany.cn/Article/details/gt2znvwggce.html

[Q66] 行锁查询
来源：http://dali.tian-w.cn/Article/details/gt2desccqfw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenzaomai.com/Article/details/gt2wnozpgku.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gt2nwomdzjz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.kuanghao11.cn/Article/details/gt2kafhyeuy.html

[Q68] 保存点
来源：http://dali.yangfankeji.com/Article/details/gt2xpndgydb.html

SAVEPOINT sp1;
来源：http://dali.sxryk.cn/Article/details/gt2ysmqftqe.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gt2iarpktip.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gt2rnbudlao.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gt2snxgdhqi.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gt2inlhffqb.html

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gt2jeujewwt.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gt2afmeppbo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sweek.top/Article/details/gt2naanqyty.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gt2xzjmuyrb.html

SHOW INDEX FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2lrpalhzm.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gt2htougrpm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.quarkkingdee.top/Article/details/gt2zzhlmwpj.html

[Q74] 强制使用索引
来源：http://dali.zhongyouzk.top/Article/details/gt2aelzmlal.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gt2ezhnogvn.html

[Q75] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jezkilfk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2ecapximd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gt2qjkodjny.html

[Q76] 按天统计
来源：http://dali.fengsongda.top/Article/details/gt2qkduiffb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gt2ziepvnca.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nexnvkup.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gt2arxftpge.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gt2hhqjobpk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sweek.top/Article/details/gt2ptcvnxtj.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gt2pcxaqytn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xziqi.cn/Article/details/gt2yhymzeuq.html

[Q80] 字符串截取
来源：http://dali.yj20258888.top/Article/details/gt2faaxzysv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2acpdyghg.html

[Q81] 字符串替换
来源：http://dali.cheryme.top/Article/details/gt2gausugll.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gt2liqefztp.html

[Q82] 字符长度与字节长度
来源：http://dali.ydzc1.top/Article/details/gt2oifyehtf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2fxdmzxlv.html

[Q83] 大小写转换
来源：http://dali.cashguo.top/Article/details/gt2ikhdjtku.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2huvhqvlj.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjexuhzw.html

SELECT TRIM(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2eiklzzwp.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gt2qbmcyhtg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.quarkkingdee.top/Article/details/gt2mrudorwn.html

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gt2tdtzyeqk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gt2nshanyhy.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gt2cljeuejw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvckrwit.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gt2jyhbislq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gt2dswbviea.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2mspfnibm.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gt2syhnnhzq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gt2krmegirf.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gt2xfclgtlt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gt2emyxtjqh.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2mxivfwpm.html

R. Bash 专题
来源：http://dali.yangfankeji.com/Article/details/gt2tgqeoixv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2lmlqlvee.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gt2fzmulrub.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gt2zbzunsng.html

set -euo pipefail
来源：http://dali.xuanzx.com/Article/details/gt2vorpxiua.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gt2emwdfuds.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gt2mdpainpu.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gt2hhmnxsdh.html

readonly PI=3.14
来源：http://dali.gogol.net.cn/Article/details/gt2yvtcponk.html

[R04] 位置参数
来源：http://dali.hammf.cn/Article/details/gt2ainabnwo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gt2owsmqjjm.html

[R05] 参数默认值
来源：http://dali.ybcxt.top/Article/details/gt2idmbawgc.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gt2gvrfzdrn.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2yxfmgvrc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gt2vnpccxrt.html

[R07] if 判断文件
来源：http://dali.hfpthk.cn/Article/details/gt2nymibdid.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qotfbolp.html

[R08] 数值比较
来源：http://dali.yangfankeji.com/Article/details/gt2aqbljyfq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2oskqychr.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gt2ucbicjrz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.meibo888.top/Article/details/gt2utqtahyo.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqjtqjps.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gt2jxfqfmwy.html

[R11] case 多分支
来源：http://dali.sysykeji.top/Article/details/gt2ktxpulyt.html

case "$1" in
来源：http://dali.smart0.xyz/Article/details/gt2aahystdq.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2vmhgpggq.html

stop)  echo "停止" ;;
来源：http://dali.ydzc1.top/Article/details/gt2wamnefuz.html

*)     echo "未知命令" ;;
来源：http://dali.jianghu66.top/Article/details/gt2gjefhwse.html

esac
来源：http://dali.wangdashe.top/Article/details/gt2hsjzybek.html

[R12] for 遍历文件
来源：http://dali.fengsongda.top/Article/details/gt2wudsgtxp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gt2zbygiwlr.html

[R13] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gt2pscnbwnr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gt2lwhdgeuj.html

[R14] C 风格 for
来源：http://dali.zhiwuduotai.top/Article/details/gt2ecyajdte.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2whybnqal.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2rcrvptzn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2roioujoy.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gt2cbndmars.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gt2hsgeznix.html

[R17] 数组定义与取值
来源：http://dali.sxryk.cn/Article/details/gt2toxmsmoi.html


<!-- 参考信息 -->