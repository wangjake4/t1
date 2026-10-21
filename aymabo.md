代发 wailian999

[P01] 生成 UUID
来源：http://dali.hammf.cn/Article/details/gtkvjqqjgm.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gtuwhonjuu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhengqikj.top/Article/details/gtdxkcnzkh.html

JS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtdzywdosx.html

TS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtyabsuxlm.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtpfuuojxn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ybcxt.top/Article/details/gtcxuhpmel.html

Ruby: SecureRandom.uuid
来源：http://dali.birdmap.top/Article/details/gtsxvpxskc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gtgjkcejgr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gtpgmfpxua.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aizwys.cn/Article/details/gtlfxxdgvs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gtxlgkjkgv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gttqfrvqnw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gtztgsujxh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gtmhkggbkc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gtgdnbtixj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.redwolf501.top/Article/details/gtrfanevbj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ppjwa.cn/Article/details/gtqtuzfhsk.html

[P03] 生成短随机字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtoionqsuc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenzaomai.com/Article/details/gtngtzcdjt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dashuyun.cn/Article/details/gtfzeuenue.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gtmqeoscka.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtosjtincz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gtatlhzyyw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gtlpaciwor.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhongyouzk.top/Article/details/gtvpdhmszu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gtlostvtjn.html

[P04] 求长度
来源：http://dali.yonumen.top/Article/details/gtvvtnabcj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gtfjnjrmir.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gttkzsenme.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyiupemml.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gtvlwywyto.html

Java: list.size();  map.size();  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtofzhcmco.html

Go:   len(arr);  len(m)
来源：http://dali.yuanzhike.top/Article/details/gtytdshnia.html

Ruby: x.length;  x.size
来源：http://dali.cucudq.cn/Article/details/gtmekblnwl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuanzx.com/Article/details/gtcctrrdnw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gaohongyu789.top/Article/details/gttynvklzg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangshuangyany.cn/Article/details/gtzqxxxozs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnxiangtu.top/Article/details/gtncomrpet.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aibaodan.cn/Article/details/gtgqioynzy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gtsograaqt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.smart0.xyz/Article/details/gtsxljrwmu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtdofpsktz.html

Ruby: a == b
来源：http://dali.cashguo.top/Article/details/gtarhvnkuc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigufen.top/Article/details/gtryedoxqp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenjidiqi.icu/Article/details/gtlhdvxnwk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gtqtkogbnv.html

PHP:  if (empty($x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtousxklkr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gtjhtunsao.html

TS:   if (x == null) {}
来源：http://dali.xylfe.cn/Article/details/gtjuhnohfw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtcqltsoml.html

Go:   if x == nil {}
来源：http://dali.hammf.cn/Article/details/gttodrakuf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.birdmap.top/Article/details/gtlspjioli.html

C#:   if (x is null) {}
来源：http://dali.ehwqpu.com/Article/details/gtedkbbaqx.html

[P07] 防抖与节流
来源：http://dali.yj20258.top/Article/details/gtfwogmues.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigfzy.top/Article/details/gtitbwokcs.html

PHP:  // 手写时间戳比较
来源：http://dali.fzhhl.top/Article/details/gtsgbppsqq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwafvbxq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxydtytd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yueranfly.top/Article/details/gtupvivwgd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jiagoushi.top/Article/details/gtodejzfaf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gtwjtoekys.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunlrmdhf.html

[P08] 处理浮点精度问题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbckdwci.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gtwqdwvhvv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hysaishi.cn/Article/details/gtafjaxrag.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.9152youxi.cn/Article/details/gtqynsmneg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gtilddingy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygvbswlr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xylfe.cn/Article/details/gtwwiukvtr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gtzoeqerhe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hfpthk.cn/Article/details/gtsikynzse.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtllunlxeg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gtqahisjbx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtjuejwhdp.html

[Q01] 创建表
来源：http://dali.yueranfly.top/Article/details/gtniwijjvo.html

CREATE TABLE users (
来源：http://dali.feifeiyinyue.top/Article/details/gtymqzygqh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtpbbbclsk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtyxfiabie.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zycfv.cn/Article/details/gtbviwejtu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ydzc1.top/Article/details/gtdpcjmtmw.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtmqxabwhr.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gtxamkgzvo.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gtyfhcxavf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gtrqvmcrpc.html

user_id INT NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtkmkdaeil.html

amount DECIMAL(10, 2),
来源：http://dali.guannengcc.top/Article/details/gtycohrjws.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.9152youxi.cn/Article/details/gtlfreokca.html

);
来源：http://dali.tianlin.xyz/Article/details/gthzbhmkmp.html

[Q03] 增加列
来源：http://dali.shangyingyoupin.top/Article/details/gtreblweuj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xinyue.icu/Article/details/gtmchyndaw.html

[Q04] 修改列类型
来源：http://dali.c1oappe.top/Article/details/gtbzjlwfva.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.316326.xyz/Article/details/gtkueuwabs.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gtudiuknjg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sxryk.cn/Article/details/gtjqdaplfg.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gtavoaarmf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gtiixoysbn.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gttejgmoas.html

DROP TABLE IF EXISTS orders;
来源：http://dali.svipenyu.cn/Article/details/gtrzjsgxxy.html

[Q08] 创建普通索引
来源：http://dali.sufxvd.cn/Article/details/gteyqgyjhz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gtbeqhoexb.html

[Q09] 创建唯一索引
来源：http://dali.smart0.xyz/Article/details/gtnhltmtiu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtmxcxghyy.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gtloxbcfih.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daria6918.cn/Article/details/gthjmqiegx.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gtwlgbxiye.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gtqwogpvpi.html

[Q12] 插入后取自增 ID
来源：http://dali.quarkkingdee.top/Article/details/gtrzxcphkq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.feifeiyinyue.top/Article/details/gtaphgiuzj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fzhhl.top/Article/details/gtisvdnwbt.html

[Q13] 忽略重复插入
来源：http://dali.sweek.top/Article/details/gtkztpyxbc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtgnsoukhw.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtsypfbvij.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.andypj.xyz/Article/details/gtzxewxyde.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gtzuyonwae.html

[Q15] 查询全部
来源：http://dali.pycfn.com/Article/details/gtbqvfnqov.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gttogfatux.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtrpmydwwb.html

SELECT id, name FROM users;
来源：http://dali.tian-w.cn/Article/details/gtauiliabc.html

[Q17] 条件查询
来源：http://dali.yj202588.top/Article/details/gtfalzdlxm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shuidangran.top/Article/details/gtfxnkikak.html

[Q18] 模糊匹配
来源：http://dali.andypj.xyz/Article/details/gtevfjfyxk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gtuknvvizt.html

[Q19] 范围查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvaoffmwb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gtlgtkosdt.html

[Q20] IN 列表
来源：http://dali.chenlongwang.top/Article/details/gtmcscmjsd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sxryk.cn/Article/details/gtvhmnnhls.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gtbqiforpx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jyoumei.cn/Article/details/gthrgolnjo.html

[Q22] 排序
来源：http://dali.guannengcc.top/Article/details/gtukkvbnif.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gtzfpxiihc.html

[Q23] 分页
来源：http://dali.yongpay.top/Article/details/gttsbadqct.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jyoumei.cn/Article/details/gthdpevtqf.html

[Q24] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtqdbgddym.html

SELECT DISTINCT city FROM users;
来源：http://dali.daxiang520.top/Article/details/gtqzkratfs.html

[Q25] 只取前 N 条
来源：http://dali.svipenyu.cn/Article/details/gtssqzdbus.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gtpbzucflh.html

[Q26] 计数
来源：http://dali.nanxuanxn.top/Article/details/gtozqfqltl.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gtmgvudzan.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gtzxaqklox.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtqejzeyhe.html

[Q28] 求和与平均
来源：http://dali.316326.xyz/Article/details/gtnocuofwz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtnfsqeufo.html

[Q29] 最大最小值
来源：http://dali.ivvv.top/Article/details/gtrhocdlcp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtsdeibpgc.html

[Q30] 分组统计
来源：http://dali.sufxvd.cn/Article/details/gtlojugxfa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtnayfoltm.html

[Q31] 分组后过滤
来源：http://dali.zhongyouzk.top/Article/details/gtauytdvhf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.redwolf501.top/Article/details/gttnumrcfg.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtxwwwwcds.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtmfneulzp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gthnngomnv.html

[Q33] 多列分组
来源：http://dali.xziqi.cn/Article/details/gtpifdhqsj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gtfwntymtg.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtpwfxzwgd.html

SELECT * FROM (
来源：http://dali.sufxvd.cn/Article/details/gtojrygjvq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cheryme.top/Article/details/gtpgpqofve.html

) t WHERE rn = 1;
来源：http://dali.zhengqikj.top/Article/details/gtxraemwpi.html

[Q35] 内连接
来源：http://dali.nanxuanxn.top/Article/details/gtxtoqoctd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gtncirnttk.html

[Q36] 左连接
来源：http://dali.tanke756.top/Article/details/gtbmojddzc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gthipvbgkf.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gtneuidjwr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gtdcyoxxxv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gtaimldryc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuanzx.com/Article/details/gtnucyosrn.html

[Q39] 自连接（查上下级）
来源：http://dali.yj202588.top/Article/details/gtczefbhvh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tian-w.cn/Article/details/gtwkbzyclx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yangfankeji.com/Article/details/gtxgmmuppn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gtqfcsgrkw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hfpthk.cn/Article/details/gtegpsdzoe.html

[Q41] 多表连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcherxhi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.andypj.xyz/Article/details/gtopxnibft.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dianchejie.cn/Article/details/gtpcfiacsc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtymlibrql.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gtxdbctrbz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hfpthk.cn/Article/details/gtlinarusl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gtemkzwbcd.html

[Q43] 标量子查询
来源：http://dali.gogol.net.cn/Article/details/gtvcfwebbt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gtfoppncqf.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gteychbtxa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gtsfgtuldi.html

[Q45] EXISTS 判断存在
来源：http://dali.wangdashe.top/Article/details/gtxkdjydmo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtzbefsxmf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gthaitvstg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gtiqtfysjh.html

[Q47] 与平均值比较
来源：http://dali.xziqi.cn/Article/details/gtrdaolfbg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ivvv.top/Article/details/gtrtfkqiev.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gtxgxwuzee.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgfzy.top/Article/details/gtuowzohal.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guowangkeji.top/Article/details/gtctpmmnku.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gtndzlbqyh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtporamdli.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gtaqoqrenv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtdludsvvm.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpsdssrm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gtgnildgmm.html

[Q52] 删除指定行
来源：http://dali.hongshengwenyu.top/Article/details/gtymdrxkca.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtmxwflszl.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gtgrzmcgbp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtudbtvkec.html

[Q54] 清空表
来源：http://dali.wangdashe.top/Article/details/gtxzuztdat.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gtlcspyljj.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gtsjyqwiht.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gtbqsuehvo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangdashe.top/Article/details/gtglnkcefr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gtrltkqjyj.html

[Q57] 行号
来源：http://dali.havefunace.top/Article/details/gtysvbondr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtjftwquql.html

[Q58] 累计求和
来源：http://dali.cucudq.cn/Article/details/gtkmnutxnf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gthodwqmhn.html

[Q59] 分组内累计
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxwgvkol.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtxeziczri.html

[Q60] 取上一行 / 下一行
来源：http://dali.fengsongda.top/Article/details/gttkmjuqen.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jianghu66.top/Article/details/gtrocfyntp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtcyojsiut.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gtvuypgfvk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtwovheslm.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gttfkcvhkl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlszidlmk.html

[Q63] 开启事务
来源：http://dali.hysaishi.cn/Article/details/gtcilmajuu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hongshengwenyu.top/Article/details/gtfkdvpddt.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gtksmhimzj.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gtlturyrkw.html

[Q65] 回滚事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihtnfamc.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gtprlgbapw.html

[Q66] 行锁查询
来源：http://dali.ydzc1.top/Article/details/gtpqgwqihf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gtdlndywgx.html

[Q67] 设置隔离级别
来源：http://dali.meibo888.top/Article/details/gtxwhcuxfg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenjidiqi.icu/Article/details/gttkhidwpk.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gtxousgnpk.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtlmmgfvqo.html

ROLLBACK TO sp1;
来源：http://dali.ybcxt.top/Article/details/gtizrmnncp.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouqjxphg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gtpktkubrn.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gtersqyzjc.html

ANALYZE TABLE users;
来源：http://dali.dashuyun.cn/Article/details/gtizqnpzjg.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gtnusqillk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhongyouzk.top/Article/details/gtiyalxwdp.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gttikqggqq.html

SHOW INDEX FROM users;
来源：http://dali.c1oappe.top/Article/details/gthjsswtjn.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxaynjrk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.havefunace.top/Article/details/gtulekwhya.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtmkkigdnw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gtlyzioubj.html

[Q75] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtgoeswrfi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtbwjbzwlz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gtkjfqfjsq.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gtqgnhruiz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gtqkpibyfd.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gtxniboric.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aibaodan.cn/Article/details/gteitrcedk.html

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gtmhjsjrfj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gtzesstuxh.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtolwpavbl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gttrjlcgdm.html

[Q80] 字符串截取
来源：http://dali.gzhubu.top/Article/details/gtjoopptug.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtftottrid.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtxkmsedmj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gtnxapduuu.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gtycghvqeo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtalknqqnq.html

[Q83] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtrywvwewn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtdwkcgnqi.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gtpdvjkpfp.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtllpnakua.html

[Q85] 数值取整
来源：http://dali.hysaishi.cn/Article/details/gtwrgqradu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gtvxxptaqe.html

[Q86] 读取 JSON 字段
来源：http://dali.tian-w.cn/Article/details/gtrjbgwfvp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gthygosgtd.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gtuflryvbj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cheryme.top/Article/details/gtvmcczzsa.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtvudswlbj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuanzhike.top/Article/details/gtanjfxzxw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtbkvlxtsq.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gtmejmzpin.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtrqrsnlpz.html

[Q90] 生成序号列
来源：http://dali.jlsjyb.cn/Article/details/gtljazpucw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gtvfksgdnn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyndtyoz.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gtfgvdsuvk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gttjirufzt.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gtyzijiolg.html

#!/usr/bin/env bash
来源：http://dali.jinqigfzy.top/Article/details/gtwokwwvtl.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gtpaoeatad.html

[R02] 变量赋值与使用
来源：http://dali.mhx1999.top/Article/details/gtlweatidu.html

name="Tom"; echo "$name"
来源：http://dali.sweek.top/Article/details/gtdivcbtgg.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gtshzbcdnx.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gtfqlfhffu.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftqtekbn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.birdmap.top/Article/details/gtdyiesnej.html

[R05] 参数默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtyouyabdt.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gtdtykjikj.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gtkscwndjq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gthhsfvmvr.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfhopskl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gtpwpzogte.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gtytgyuqcg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yongpay.top/Article/details/gtlurysqma.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtvrthhxfz.html


<!-- 参考信息 -->