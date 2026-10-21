代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.gotoacloud.top/Article/details/gtxcflgdag.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hfpthk.cn/Article/details/gtxyjodklk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gtuetfgoyy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yueranfly.top/Article/details/gtvarwcvfm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gtvlyuabuh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guannengcc.top/Article/details/gtmfxnvjaa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gtpbwbzkoy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gtnmnsbrmi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ivvv.top/Article/details/gtxdnphalg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cdnleiting.top/Article/details/gttyffkgqi.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtoasyuayz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gtjcltruak.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gtnctlmzcz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtzpoojqrw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gtdwduzmtm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sysykeji.top/Article/details/gtvfmfuuln.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenjidiqi.icu/Article/details/gtntkptrly.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.meibo888.top/Article/details/gtctiabziz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gtsesdghyl.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gtgbilqjan.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xylfe.cn/Article/details/gtbgsqowai.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtkbvqhzhv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtxoqufxtc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtnfpnushu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtsupsunkv.html

Go:   len(arr);  len(m)
来源：http://dali.0kj1m.cn/Article/details/gtoeychxzg.html

Ruby: x.length;  x.size
来源：http://dali.xuanzx.com/Article/details/gtyhnwzmtc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtbdbekxrm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gtskcbzatk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dashuyun.cn/Article/details/gtsqvulwuf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gtjgvfecji.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gtwfplehde.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtlqdyvogb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aizwys.cn/Article/details/gthghhzvbq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtpgneguxg.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gtdvvquxjs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jianghu66.top/Article/details/gtrxslexjy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gtsfhywutn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbbswmhs.html

PHP:  if (empty($x)) {}
来源：http://dali.ybcxt.top/Article/details/gtqfaacuko.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.andypj.xyz/Article/details/gtvizfiofy.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gttlopwwqt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtnamijhrh.html

Go:   if x == nil {}
来源：http://dali.ivvv.top/Article/details/gtdfdimagi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pengpengdd.cyou/Article/details/gtnxjovccp.html

C#:   if (x is null) {}
来源：http://dali.sweek.top/Article/details/gtiptettcc.html

[P07] 防抖与节流
来源：http://dali.jinqigufen.top/Article/details/gttbsqprgy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yonumen.top/Article/details/gtmrxigtnb.html

PHP:  // 手写时间戳比较
来源：http://dali.feifeiyinyue.top/Article/details/gtywtjndrv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtsewlcxvo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gtntxyhxsw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenlongwang.top/Article/details/gtrzfjnbca.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhixingplan.top/Article/details/gtjyhnqblm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gtjjopbytc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuxming.cn/Article/details/gtzwxuexgd.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gtcgknmref.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hywenlv.cn/Article/details/gtmijehjyb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzqjnwzl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.vqdsnc.cn/Article/details/gtyreetifb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gtywxtussm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgfzy.top/Article/details/gtjctdupmq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gtauilyrxv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gttbublybe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258888.top/Article/details/gtdlcqfbmg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtizeqqbzz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtqlkzpqlq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gteufwkatj.html

[Q01] 创建表
来源：http://dali.hammf.cn/Article/details/gtovlueodf.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gtrhtubjzk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtrkmnybme.html

name VARCHAR(50) NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gtyxwzljit.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gtdgdoiirb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cucudq.cn/Article/details/gtautjabud.html

);
来源：http://dali.yueranfly.top/Article/details/gtkuxdiqoh.html

[Q02] 创建带外键的表
来源：http://dali.bjfxy.top/Article/details/gtnwqfsoxx.html

CREATE TABLE orders (
来源：http://dali.chenzaomai.com/Article/details/gtigjxkmns.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtrarzzmaf.html

user_id INT NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtywzacstr.html

amount DECIMAL(10, 2),
来源：http://dali.hysaishi.cn/Article/details/gtoaggjemb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gtmaucetof.html

);
来源：http://dali.cdnleiting.top/Article/details/gtewvostmk.html

[Q03] 增加列
来源：http://dali.ivvv.top/Article/details/gtpkmofpyu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gtylgmftxg.html

[Q04] 修改列类型
来源：http://dali.cucudq.cn/Article/details/gtiiyebqyg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hfpthk.cn/Article/details/gtsgcjscjs.html

[Q05] 重命名列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiunfoxkq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dianchejie.cn/Article/details/gttjbznciq.html

[Q06] 删除列
来源：http://dali.smart0.xyz/Article/details/gteucpddxi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yonumen.top/Article/details/gtjhymdrng.html

[Q07] 删除表
来源：http://dali.shangyingyoupin.top/Article/details/gtjwjfqvff.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkawrovi.html

[Q08] 创建普通索引
来源：http://dali.tian-w.cn/Article/details/gtkzpuycuc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtuixwhcie.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gtrtvrekir.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtrdiybhzn.html

[Q10] 插入单行
来源：http://dali.yuanzhike.top/Article/details/gthcqeugfw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yvedp.cn/Article/details/gtvmakqjle.html

[Q11] 一次插入多行
来源：http://dali.zhongyouzk.top/Article/details/gtzyoawoks.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cheryme.top/Article/details/gtpnrytzgi.html

[Q12] 插入后取自增 ID
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeuxyvej.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.bjfxy.top/Article/details/gtmjpmswsy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dianchejie.cn/Article/details/gttxdqdyjv.html

[Q13] 忽略重复插入
来源：http://dali.shzxlz.cn/Article/details/gtfyitywxc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ybcxt.top/Article/details/gtufwwizic.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenzaomai.com/Article/details/gtmyqrnsnf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ydzc1.top/Article/details/gtqvntdiwn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yangfankeji.com/Article/details/gttgrwanbh.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gtjahnwjcz.html

SELECT * FROM users;
来源：http://dali.birdmap.top/Article/details/gttkibsyfr.html

[Q16] 查询指定列
来源：http://dali.yj20258888.top/Article/details/gtsdjaynik.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtvbhswqzb.html

[Q17] 条件查询
来源：http://dali.yonumen.top/Article/details/gtngptescg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtujeropsk.html

[Q18] 模糊匹配
来源：http://dali.guowangkeji.top/Article/details/gtudqzibfu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gtfzgeordj.html

[Q19] 范围查询
来源：http://dali.fzhhl.top/Article/details/gtrkzxshai.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gtdxrrrewm.html

[Q20] IN 列表
来源：http://dali.hfpthk.cn/Article/details/gtkifmquta.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gtyubrxqvz.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvvmfjtp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gtpxeahttc.html

[Q22] 排序
来源：http://dali.vqdsnc.cn/Article/details/gtcsbvyeha.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigfzy.top/Article/details/gtbsojtxti.html

[Q23] 分页
来源：http://dali.hnqzz.top/Article/details/gtvbjdhraa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nwbrower.top/Article/details/gtxflbcgjw.html

[Q24] 去重
来源：http://dali.guowangkeji.top/Article/details/gtrqjycddb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtzsurjehi.html

[Q25] 只取前 N 条
来源：http://dali.hfpthk.cn/Article/details/gtkiawwtmi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnqzz.top/Article/details/gtefxukabr.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbeudvgrz.html

SELECT COUNT(*) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtquqtlaet.html

[Q27] 条件计数
来源：http://dali.haohaochexian.top/Article/details/gtillbkbwy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtipofyuyt.html

[Q28] 求和与平均
来源：http://dali.fzhhl.top/Article/details/gtlxvlbnit.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtgmlrkhpg.html

[Q29] 最大最小值
来源：http://dali.zhengqikj.top/Article/details/gtcpdqgjwh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtvgdhonow.html

[Q30] 分组统计
来源：http://dali.hywenlv.cn/Article/details/gtdmtpjfwx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gttqinssjy.html

[Q31] 分组后过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoymbzcw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.c1oappe.top/Article/details/gtoenmwqop.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtbxcyjpky.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtdwmrbpje.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gtklpcmszx.html

[Q33] 多列分组
来源：http://dali.ehwqpu.com/Article/details/gtrgehtrug.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cdnleiting.top/Article/details/gtvotjdami.html

[Q34] 每组取第一条
来源：http://dali.nwbrower.top/Article/details/gtaicnjhux.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtexlvysht.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gtgyzbffis.html

) t WHERE rn = 1;
来源：http://dali.yonumen.top/Article/details/gtsvsholqc.html

[Q35] 内连接
来源：http://dali.birdmap.top/Article/details/gtbcybygji.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtsiksjdox.html

[Q36] 左连接
来源：http://dali.hysaishi.cn/Article/details/gtxxoxmgli.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gthvbjynbm.html

[Q37] 右连接
来源：http://dali.xuetiantiany.cn/Article/details/gtrdhpglnd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhixingplan.top/Article/details/gtzaopouqt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ivvv.top/Article/details/gtdhnijeeh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqhkysca.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgfzy.top/Article/details/gtsaqzmkyd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.9152youxi.cn/Article/details/gtkbbtmzeq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dianchejie.cn/Article/details/gtkynuhwhw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gtnmkoxtdb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmktvkbe.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gtwdlvytch.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gogol.net.cn/Article/details/gtihdrsllc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gtfenelsse.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gtenccmeol.html

[Q42] 连接条件附加过滤
来源：http://dali.cdnleiting.top/Article/details/gtaulpyubn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jyoumei.cn/Article/details/gtmpnipsxb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gthtemqqkp.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gttyvbvjph.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gttjqkrucw.html

[Q44] IN 子查询
来源：http://dali.yj20258888.top/Article/details/gtntgdjiwk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangshuangyany.cn/Article/details/gtiwblkmhj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtlhymhihj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtseiyrebb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.0kj1m.cn/Article/details/gtwwmjbzug.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gttmsssrsx.html

[Q47] 与平均值比较
来源：http://dali.quarkkingdee.top/Article/details/gtvgexabmb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gtsqsvgwcu.html

[Q48] CTE 公用表表达式
来源：http://dali.chenzaomai.com/Article/details/gtipoprcjk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.feifeiyinyue.top/Article/details/gtytsflany.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cashguo.top/Article/details/gtqbiwxmfs.html

[Q49] 更新单行
来源：http://dali.jqgufenzy.top/Article/details/gtkuboiiwj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtcerjyjmv.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gtlqjwhkrd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtgkeoojyz.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gtvkgzfufm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daria6918.cn/Article/details/gtfjzzbxka.html

[Q52] 删除指定行
来源：http://dali.xuetiantiany.cn/Article/details/gtrkfcsalj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gthhfbdezj.html

[Q53] 按条件删除
来源：http://dali.c1oappe.top/Article/details/gtuocsflsz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gtqjbzadsv.html

[Q54] 清空表
来源：http://dali.hysaishi.cn/Article/details/gtmeexhkym.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gtpdjvfyfb.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtjmxinumd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtljaesuih.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrswycbu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtvjnypyab.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gtqlitxrxb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gtlbbcdomw.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gthlgirqcy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtcrhbhgkx.html

[Q59] 分组内累计
来源：http://dali.chenzaomai.com/Article/details/gtuzhgiskv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtszypnzxs.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gtgpvqarck.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigfzy.top/Article/details/gtulcipevf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fzhhl.top/Article/details/gttqnwcbhr.html

[Q61] 移动平均
来源：http://dali.wangshuangyany.cn/Article/details/gtoytuapsg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtueniigzy.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gtorcecmbv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtddxonvbg.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gtjxdzdybj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jianghu66.top/Article/details/gtxjyytyke.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gtcxhkduhm.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gtwhytquqn.html

[Q65] 回滚事务
来源：http://dali.sufxvd.cn/Article/details/gtvytcxssk.html

ROLLBACK;
来源：http://dali.cdnleiting.top/Article/details/gtckohhnif.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwxtizju.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangdashe.top/Article/details/gtvhbnqyyn.html

[Q67] 设置隔离级别
来源：http://dali.nanxuanxn.top/Article/details/gtdtghlnfs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tian-w.cn/Article/details/gthlvxwahv.html

[Q68] 保存点
来源：http://dali.0kj1m.cn/Article/details/gtvnjgbcas.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gtbvslfqnj.html

ROLLBACK TO sp1;
来源：http://dali.andypj.xyz/Article/details/gtvefqrhjs.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gtcxcnlelr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gotoacloud.top/Article/details/gthsfnmnec.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gtzxcbuoyh.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gtdadmffex.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gtjcwdpbyr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gtdorsrdzs.html

[Q72] 查看索引
来源：http://dali.jinqigfzy.top/Article/details/gtbytdcyxa.html

SHOW INDEX FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtagucwlmi.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gtyfmxfayv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtuzkdvkpu.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gthdxbfpzo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gtjadmqwjl.html

[Q75] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtuzbhaahz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtxozknycd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnqzz.top/Article/details/gtqivsyiig.html

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gtzxftlyar.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtslmrtsqx.html

[Q77] 时间加减
来源：http://dali.tanke756.top/Article/details/gthekjfova.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuetiantiany.cn/Article/details/gteiguovnc.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gtjaqvkscw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhhpzfki.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gtvybzfnrz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.mhx1999.top/Article/details/gtsgljmgjl.html

[Q80] 字符串截取
来源：http://dali.gogol.net.cn/Article/details/gtrzzyezts.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtbtsaduoz.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtsvvcpddr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gtcnkrrxpr.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gtcoswjhub.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtfwpskbwf.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtpgmzaevn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtpbyykcgb.html

[Q84] 去除首尾空格
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmrcmmdr.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtbkocwluj.html

[Q85] 数值取整
来源：http://dali.zhongyouzk.top/Article/details/gthkhpbqbo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ehwqpu.com/Article/details/gtolzekczc.html

[Q86] 读取 JSON 字段
来源：http://dali.haohaochexian.top/Article/details/gtnepuvlce.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzfbsvno.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gtynktvnnp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfranujn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gtkyumuccx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xziqi.cn/Article/details/gtrasyaqng.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtvxubbyxr.html

[Q89] 判断表是否存在
来源：http://dali.xziqi.cn/Article/details/gtrakitygj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtiimhylic.html

[Q90] 生成序号列
来源：http://dali.meibo888.top/Article/details/gtmjowonif.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gtekzeyiyw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtiumcgzny.html

R. Bash 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtndhxykzp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwruqcnab.html

[R01] shebang 与严格模式
来源：http://dali.daria6918.cn/Article/details/gtwckfooxv.html

#!/usr/bin/env bash
来源：http://dali.hysaishi.cn/Article/details/gtevxxbvta.html

set -euo pipefail
来源：http://dali.chenjidiqi.icu/Article/details/gtafqbcpac.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gthnknulwd.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gtsenirwjn.html

[R03] 只读变量
来源：http://dali.yj20258.top/Article/details/gtbaybpfua.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gtldnojgtw.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gtvvodxiei.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hywenlv.cn/Article/details/gtpbysxova.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtrqeegjzk.html

name="${1:-default}"
来源：http://dali.zhengqikj.top/Article/details/gtqwzjgjmf.html

[R06] 判断命令是否存在
来源：http://dali.gotoacloud.top/Article/details/gtomjclxuq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtljpxnwui.html

[R07] if 判断文件
来源：http://dali.xziqi.cn/Article/details/gthplczyui.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gtauydblyv.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gtdnzfsagb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gtzcqofcas.html

[R09] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gtizxplhve.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gtavcmxsfl.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gtmpaavwro.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtmtlixauy.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gtzfpzhhez.html

case "$1" in
来源：http://dali.daria6918.cn/Article/details/gtblbnzzzv.html

start) echo "启动" ;;
来源：http://dali.yj20258.top/Article/details/gtwzesyznx.html

stop)  echo "停止" ;;
来源：http://dali.chenlongwang.top/Article/details/gtktkdxezt.html

*)     echo "未知命令" ;;
来源：http://dali.zdqjudy.top/Article/details/gtcngdfnkn.html


<!-- 参考信息 -->