代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhengqikj.top/Article/details/gtgqhkextl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gtvkdbeitk.html

[P03] 生成短随机字符串
来源：http://dali.svipenyu.cn/Article/details/gtuzjsdhqv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gtrodkrqjj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gttulghwnq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gthrkeurae.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtqirjdgcv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gtnpvkkvwk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gtilxgmiya.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.meibo888.top/Article/details/gtvpkvpvko.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.meibo888.top/Article/details/gttxufwpyv.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gtkxbtzsno.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gtniqjptkn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtlsosfbqt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwexjsktd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gtvrejpzuv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pycfn.com/Article/details/gtpcxlirod.html

Go:   len(arr);  len(m)
来源：http://dali.iojbl.cn/Article/details/gtfwjwotzd.html

Ruby: x.length;  x.size
来源：http://dali.fengsongda.top/Article/details/gtdupmhsbd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.mhx1999.top/Article/details/gtxgyrrqge.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gteltaruqe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yangfankeji.com/Article/details/gtwkegghto.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sysykeji.top/Article/details/gtbbupxlvg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhongyouzk.top/Article/details/gtrsdkhfrt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtmrwnklko.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cashguo.top/Article/details/gtmpnjrvex.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnqzz.top/Article/details/gtqpjaobdk.html

Ruby: a == b
来源：http://dali.316326.xyz/Article/details/gtupqtbutx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenjidiqi.icu/Article/details/gtqcfpmhfv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gtshdkjjzm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cheryme.top/Article/details/gtissvnsnj.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gtydbnskpr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gtxomgmyzr.html

TS:   if (x == null) {}
来源：http://dali.tanke756.top/Article/details/gtqkirrutb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknylzrki.html

Go:   if x == nil {}
来源：http://dali.yj20258.top/Article/details/gttxgeeoko.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yangfankeji.com/Article/details/gtufijxwjy.html

C#:   if (x is null) {}
来源：http://dali.andypj.xyz/Article/details/gtgyvxxrid.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gtfqgojocz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenjidiqi.icu/Article/details/gthmyrwgee.html

PHP:  // 手写时间戳比较
来源：http://dali.iojbl.cn/Article/details/gtrotmxkxr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtrxclqsfh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtujpdzzxp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gtmprlsvnh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhengqikj.top/Article/details/gtljkjmyet.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gtvwancxef.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gtdiaqoxmj.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gtfslanbcy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gthdphsxis.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnqzz.top/Article/details/gtevfselss.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yanxiufei.cn/Article/details/gtfomkgmcr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ivvv.top/Article/details/gtkqpnmjyi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hysaishi.cn/Article/details/gtkqpjdgty.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gotoacloud.top/Article/details/gtahsjiopg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangdashe.top/Article/details/gtwyiiioje.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gtsgkeruei.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtthoephcl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gtbntckdnp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtbkmhcfxg.html

[Q01] 创建表
来源：http://dali.yj202588.top/Article/details/gtexwjewrv.html

CREATE TABLE users (
来源：http://dali.chenlongwang.top/Article/details/gtmnmudafi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtdujdgrwd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtpnnpbiuu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xylfe.cn/Article/details/gteqmqvcoh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gtmhpfkjrv.html

);
来源：http://dali.shuidangran.top/Article/details/gtngkwqfal.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gtxqqwvaco.html

CREATE TABLE orders (
来源：http://dali.havefunace.top/Article/details/gtsojlvwxa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzldjpbp.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtieunavxx.html

amount DECIMAL(10, 2),
来源：http://dali.yuanzhike.top/Article/details/gtgwgdqqru.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.mhx1999.top/Article/details/gtqweodpfs.html

);
来源：http://dali.ydzc1.top/Article/details/gtfrpedncd.html

[Q03] 增加列
来源：http://dali.havefunace.top/Article/details/gthpcfaxuj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gtbfodsglk.html

[Q04] 修改列类型
来源：http://dali.pycfn.com/Article/details/gtuypddwnn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guannengcc.top/Article/details/gthdcelfaf.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gtzxtgdyfv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gtrqhjqiwi.html

[Q06] 删除列
来源：http://dali.zhiwuduotai.top/Article/details/gtwxefzmbs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yangfankeji.com/Article/details/gtfztivwqu.html

[Q07] 删除表
来源：http://dali.c1oappe.top/Article/details/gtiozvssnv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuxming.cn/Article/details/gtpbaijcgh.html

[Q08] 创建普通索引
来源：http://dali.chenjidiqi.icu/Article/details/gtllnfimwn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gtpduegicc.html

[Q09] 创建唯一索引
来源：http://dali.daxiang520.top/Article/details/gtavhmmyda.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmabjtsj.html

[Q10] 插入单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrizcnpb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtmlrgpqsw.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gtdyeosblz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtdmprptjb.html

[Q12] 插入后取自增 ID
来源：http://dali.pycfn.com/Article/details/gtablgcqwr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tanke756.top/Article/details/gtxadeaklt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hfpthk.cn/Article/details/gttygpubdd.html

[Q13] 忽略重复插入
来源：http://dali.vqdsnc.cn/Article/details/gtxtqjlibr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.redwolf501.top/Article/details/gtpffptcvk.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gtrqgmpnbe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gttuuibmwf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnxiangtu.top/Article/details/gtjaeattem.html

[Q15] 查询全部
来源：http://dali.shzxlz.cn/Article/details/gtrhuwsixa.html

SELECT * FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtaeggffux.html

[Q16] 查询指定列
来源：http://dali.ivvv.top/Article/details/gtpnlrvdcn.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfegflsmc.html

[Q17] 条件查询
来源：http://dali.cucudq.cn/Article/details/gtbawscnls.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gtkxlpsdea.html

[Q18] 模糊匹配
来源：http://dali.sysykeji.top/Article/details/gtegrvnorf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gtdfgwqivv.html

[Q19] 范围查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtegheboyx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yongpay.top/Article/details/gtinphczoo.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gthefsycdz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shuidangran.top/Article/details/gtjuemldmx.html

[Q21] 空值判断
来源：http://dali.jinqigufen.top/Article/details/gtdazdeilr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cqqwz.cn/Article/details/gtgmzgswzu.html

[Q22] 排序
来源：http://dali.mhx1999.top/Article/details/gtpwyzbnnm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gtcigvldkk.html

[Q23] 分页
来源：http://dali.zhoulong.xyz/Article/details/gtjsajqpna.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gtqtfqblde.html

[Q24] 去重
来源：http://dali.chenlongwang.top/Article/details/gtvwmtuxtf.html

SELECT DISTINCT city FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtmfrukxmq.html

[Q25] 只取前 N 条
来源：http://dali.wangshuangyany.cn/Article/details/gtihpqopya.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexszluhx.html

[Q26] 计数
来源：http://dali.yvedp.cn/Article/details/gtqvsuuyow.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtutbmzqld.html

[Q27] 条件计数
来源：http://dali.feifeiyinyue.top/Article/details/gtnvviavwv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gthstpptlc.html

[Q28] 求和与平均
来源：http://dali.shzxlz.cn/Article/details/gtrdtkakvi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtjsdauhma.html

[Q29] 最大最小值
来源：http://dali.316326.xyz/Article/details/gtuuepewbj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtqyyqoysv.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdupxmta.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtoeyczezn.html

[Q31] 分组后过滤
来源：http://dali.sxryk.cn/Article/details/gtxbtkrdzk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gtyixycwxi.html

[Q32] 分组拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtoxhrrqtz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtwmpsuotr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gtuhobcssg.html

[Q33] 多列分组
来源：http://dali.chenlongwang.top/Article/details/gtkezoblhm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijbglghp.html

[Q34] 每组取第一条
来源：http://dali.nanxinkj.top/Article/details/gtuuuvutsx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gtoghilupm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gtdvrxtusr.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gtwjkmhkxv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gtrzmfdblf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gtayybohiq.html

[Q36] 左连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzmfzlmt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtjllnjrgz.html

[Q37] 右连接
来源：http://dali.shuidangran.top/Article/details/gtgluhohij.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gtijlvwbye.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.316326.xyz/Article/details/gtbebjikks.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gtqymqnowl.html

[Q39] 自连接（查上下级）
来源：http://dali.xinyue.icu/Article/details/gtqajgkcio.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sysykeji.top/Article/details/gtpvakoeai.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gtkisflajn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnqzz.top/Article/details/gtwnvcmjri.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gtfmjfrybc.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gtydehisox.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.snrcjt.cn/Article/details/gtnjofgwsr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cucudq.cn/Article/details/gtgnjouout.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxinkj.top/Article/details/gthneljdty.html

[Q42] 连接条件附加过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxarqvoub.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dashuyun.cn/Article/details/gtrkoaxsya.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gtbuglqerl.html

[Q43] 标量子查询
来源：http://dali.vqdsnc.cn/Article/details/gtehhkvavw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gtdsbkzebh.html

[Q44] IN 子查询
来源：http://dali.9152youxi.cn/Article/details/gtslgycvwv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258.top/Article/details/gtwxrvacrc.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gtibqwcouz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtulsqmcvr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yonumen.top/Article/details/gtlbqzpspc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtpcgcfdwt.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gtzonljrto.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gtymjphguz.html

[Q48] CTE 公用表表达式
来源：http://dali.hysaishi.cn/Article/details/gtpkifmfgo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gtniepdjen.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gaohongyu789.top/Article/details/gtnxiwlqrf.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gtfkyklmng.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtatzuhtbi.html

[Q50] 批量更新
来源：http://dali.aibaodan.cn/Article/details/gtxfpswfvg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gtfpcbktbs.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gtpgwgzhrd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangdashe.top/Article/details/gtsimkxyhj.html

[Q52] 删除指定行
来源：http://dali.yangfankeji.com/Article/details/gtdfqmxvey.html

DELETE FROM users WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtppybqlkr.html

[Q53] 按条件删除
来源：http://dali.yonumen.top/Article/details/gtzmdsnfyy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtpiarxvcb.html

[Q54] 清空表
来源：http://dali.gogol.net.cn/Article/details/gtypayuvvh.html

TRUNCATE TABLE logs;
来源：http://dali.hywenlv.cn/Article/details/gtlhdsufes.html

[Q55] 排名（并列占位）
来源：http://dali.gaohongyu789.top/Article/details/gtobrumnkb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gttuskdpnw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjedxybfd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtvxqjhoar.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gtcqpvyscw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gtsgapncps.html

[Q58] 累计求和
来源：http://dali.yueranfly.top/Article/details/gtrqraqfoi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtmwjmmcws.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gtjxhjldrt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtnrsjswci.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgfzy.top/Article/details/gtmajokstk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gtejfwewsi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xinyue.icu/Article/details/gticbwmxeq.html

[Q61] 移动平均
来源：http://dali.jlsjyb.cn/Article/details/gtlojdvigg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtzowzbpob.html

[Q62] 分组占比
来源：http://dali.tianlin.xyz/Article/details/gtprqmsnlh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtpkodsoxt.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gtocpljgsz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aibaodan.cn/Article/details/gtuyhhwcbr.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gtnazvsssa.html

COMMIT;
来源：http://dali.c1oappe.top/Article/details/gtgawwxhxl.html

[Q65] 回滚事务
来源：http://dali.0kj1m.cn/Article/details/gtcwejyuyq.html

ROLLBACK;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsqsuwzi.html

[Q66] 行锁查询
来源：http://dali.smart0.xyz/Article/details/gtpmygmkfo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258.top/Article/details/gtzyeqtvdd.html

[Q67] 设置隔离级别
来源：http://dali.svipenyu.cn/Article/details/gtnhgslhyj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gtonpbkcnx.html

[Q68] 保存点
来源：http://dali.c1oappe.top/Article/details/gttwprengc.html

SAVEPOINT sp1;
来源：http://dali.dianchejie.cn/Article/details/gtqdehkskw.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gtrqdjoecs.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhimjsbt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gtneadyxnb.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gtjdiiqiex.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzxfssef.html

[Q71] 查看建表语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiulbvkax.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sufxvd.cn/Article/details/gtthnjypvu.html

[Q72] 查看索引
来源：http://dali.yuanzhike.top/Article/details/gtupjzkygr.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gthwvxfumm.html

[Q73] 查看表状态
来源：http://dali.jinghuilouyu.cn/Article/details/gtesqjwgzf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gtkerrnzmp.html

[Q74] 强制使用索引
来源：http://dali.haohaochexian.top/Article/details/gtvnspbvgx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jlsjyb.cn/Article/details/gtvgghliwi.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtxyueeuzn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gthleudluu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gtvlvfyrzu.html

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gtonmzilvp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gthnulfzyn.html

[Q77] 时间加减
来源：http://dali.yuanzhike.top/Article/details/gtytvxkugx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shzxlz.cn/Article/details/gtdshetlda.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gtrmynyxtz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gtycoqlkuh.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gthphynciu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gtwzyhiltk.html

[Q80] 字符串截取
来源：http://dali.shuidangran.top/Article/details/gtumhtunhb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gtjnqoefkk.html

[Q81] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gtkfnkiqjr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtcdfzvmse.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gtgvqpfopm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtzwlueosf.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gttxxvlvxp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtqckvqaze.html

[Q84] 去除首尾空格
来源：http://dali.zycfv.cn/Article/details/gtkjoduqdw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtlswtktin.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gthtzzjriy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.quarkkingdee.top/Article/details/gtmazybalk.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gtwipirawm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgfzy.top/Article/details/gtqlnlayke.html

[Q87] JSON 字段做条件
来源：http://dali.jqgfzy.top/Article/details/gtaujrqoej.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gtkumcshbx.html

[Q88] 行转列（条件聚合）
来源：http://dali.pengpengdd.cyou/Article/details/gtrltlgjll.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.haohaochexian.top/Article/details/gtlkofvije.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gtvspqqbvg.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gtrmkjkqns.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwvorfxe.html

[Q90] 生成序号列
来源：http://dali.sufxvd.cn/Article/details/gteqnmvsit.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fengsongda.top/Article/details/gtzcvdrleg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtypvzerec.html

R. Bash 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtkmfojhdz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtagvrflwh.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gtxrirynks.html

#!/usr/bin/env bash
来源：http://dali.hongshengwenyu.top/Article/details/gtbmcrzcqv.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gthpfkbgut.html

[R02] 变量赋值与使用
来源：http://dali.jiagoushi.top/Article/details/gtpwxugobs.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gtwaeutmyc.html

[R03] 只读变量
来源：http://dali.hysaishi.cn/Article/details/gtxyydohgm.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gtggcaaecf.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gtwknaeckf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jlsjyb.cn/Article/details/gtirvsanwu.html

[R05] 参数默认值
来源：http://dali.yj20258888.top/Article/details/gtcqciixke.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gtfiirulci.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gtaakrdasz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqbhcvgbf.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhzjzfdp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtlqnilelh.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gtzqiqxpzf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yvedp.cn/Article/details/gtglebrdsc.html

[R09] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gtoigywjfq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gtlyhrlrpa.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gtdakadzmc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gtfwxhtdvm.html

[R11] case 多分支
来源：http://dali.9152youxi.cn/Article/details/gtyezioszi.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gtnrjakufq.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtnujluwym.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfaclovij.html

*)     echo "未知命令" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtswecfgmh.html

esac
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxhucydc.html

[R12] for 遍历文件
来源：http://dali.vqdsnc.cn/Article/details/gtxpofthrc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtzeraxdcy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtfdgheroy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtxoejyhle.html

[R14] C 风格 for
来源：http://dali.yonumen.top/Article/details/gtntkyeizg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gtjswhdbkl.html

[R15] while 逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtzdnkegdc.html


<!-- 参考信息 -->