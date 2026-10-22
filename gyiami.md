代发 wailian999

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gthcikjngp.html

Py:   str(uuid.uuid4())
来源：http://dali.jinghuilouyu.cn/Article/details/gttrdkirft.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenlongwang.top/Article/details/gteztblawp.html

JS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtulyqadvs.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtdgmiijyd.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gtyyutakwc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgslizqn.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxuanxn.top/Article/details/gtxequaery.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxciveaid.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gtfakztuyo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258.top/Article/details/gtgejuqhvq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gtzkjaonxz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtabvrzorv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gtdrsrgvnu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ivvv.top/Article/details/gttpymqiib.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shzxlz.cn/Article/details/gtsquqxejx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.bjfxy.top/Article/details/gtwxufkhjr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj202588.top/Article/details/gttjahhhix.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gtqywssgod.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.9152youxi.cn/Article/details/gtgjcaczdc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaidnvizc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gthzuroipw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtblllvryr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gtjzxrkyrz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtsazffkjj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gtaxstrglo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hysaishi.cn/Article/details/gtvpcvhkwy.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gtnfeydoam.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gtpwtipejs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gttkkzztsu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtbdntjkch.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtwpaxrfor.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yonumen.top/Article/details/gtvavzdymh.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gthzlgapvu.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnskwmhwn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangdashe.top/Article/details/gtouzaoblg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hywenlv.cn/Article/details/gtddrjqrgj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangshuangyany.cn/Article/details/gtguilfhge.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gtlftverho.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dashuyun.cn/Article/details/gtcarlkaeh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gtycwcfdzj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cashguo.top/Article/details/gtwcwsxlqr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtueskipzt.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gtfbjzshnc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xziqi.cn/Article/details/gtvhrpzcmh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gtbhgftawf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shuidangran.top/Article/details/gthcmqfvgl.html

PHP:  if (empty($x)) {}
来源：http://dali.aibaodan.cn/Article/details/gtkuagbvls.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gtwvoavayr.html

TS:   if (x == null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkpxttdh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtuqjblkwu.html

Go:   if x == nil {}
来源：http://dali.haohaochexian.top/Article/details/gtlrkcltoy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.birdmap.top/Article/details/gtelzltfac.html

C#:   if (x is null) {}
来源：http://dali.sxryk.cn/Article/details/gtndbxanpf.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gttfnexfbd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gtulekutny.html

PHP:  // 手写时间戳比较
来源：http://dali.0kj1m.cn/Article/details/gtrgtaktkb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtrbswzwyl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gttrjpbsch.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gotoacloud.top/Article/details/gtxtypctem.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gtpfjofcot.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gotoacloud.top/Article/details/gtvtojwzvf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zycfv.cn/Article/details/gtvcuypdgm.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gtuwsivtxt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gtyadycmez.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ydzc1.top/Article/details/gtngryqimv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gtkxcansbi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtswqxxmyx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gtlutaiimd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gtrpddugob.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guowangkeji.top/Article/details/gtslazlmnu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ehwqpu.com/Article/details/gtpicthlzp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxxjuxfcw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhongyouzk.top/Article/details/gtgalgwfgf.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtfytifatc.html

[Q01] 创建表
来源：http://dali.gogol.net.cn/Article/details/gtxrubwcoc.html

CREATE TABLE users (
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcpqwsns.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtjuubgxzw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtljbjdmyb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.kuanghao11.cn/Article/details/gtdigdcqud.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.haohaochexian.top/Article/details/gtjolqknoq.html

);
来源：http://dali.jiagoushi.top/Article/details/gtfosmimxr.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamwubhbo.html

CREATE TABLE orders (
来源：http://dali.ehwqpu.com/Article/details/gtqimjojog.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtkeawenhc.html

user_id INT NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gtjgqiqlwq.html

amount DECIMAL(10, 2),
来源：http://dali.daria6918.cn/Article/details/gtohwrugkg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gtudwueeut.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgojzdpv.html

[Q03] 增加列
来源：http://dali.316326.xyz/Article/details/gtkhmdjpki.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gtoixeejbp.html

[Q04] 修改列类型
来源：http://dali.dashuyun.cn/Article/details/gtzcbbuvsx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sysykeji.top/Article/details/gtlicwrfaz.html

[Q05] 重命名列
来源：http://dali.yuanzhike.top/Article/details/gtvleufpfu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gtbxogensi.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtysugbbga.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.c1oappe.top/Article/details/gtjudyyjny.html

[Q07] 删除表
来源：http://dali.mhx1999.top/Article/details/gtqdemmtge.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yongpay.top/Article/details/gtnvnfjofr.html

[Q08] 创建普通索引
来源：http://dali.jinqigfzy.top/Article/details/gtgatndzja.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gtmbfultui.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gtkpahmxaz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gtnitekdij.html

[Q10] 插入单行
来源：http://dali.zycfv.cn/Article/details/gtbnizmcib.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gtrgskwxkj.html

[Q11] 一次插入多行
来源：http://dali.bjfxy.top/Article/details/gtzopflsef.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daxiang520.top/Article/details/gtnplhxrfb.html

[Q12] 插入后取自增 ID
来源：http://dali.xuanzx.com/Article/details/gtpiqpcqev.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenjidiqi.icu/Article/details/gttpawmdfa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gtayzdeaap.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gtsfpsapiq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnqzz.top/Article/details/gtgiccnvaf.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gtftlqztkn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigfzy.top/Article/details/gtrmqokeao.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aizwys.cn/Article/details/gtvldodqqg.html

[Q15] 查询全部
来源：http://dali.birdmap.top/Article/details/gtynvqrtxk.html

SELECT * FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtwzditgbk.html

[Q16] 查询指定列
来源：http://dali.smart0.xyz/Article/details/gtglccsigt.html

SELECT id, name FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtwattryhq.html

[Q17] 条件查询
来源：http://dali.hnxiangtu.top/Article/details/gtgdgtjtrm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.havefunace.top/Article/details/gtwolcreub.html

[Q18] 模糊匹配
来源：http://dali.shangyingyoupin.top/Article/details/gttlnwnyba.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.andypj.xyz/Article/details/gtbjmrnxrt.html

[Q19] 范围查询
来源：http://dali.quarkkingdee.top/Article/details/gtefbwmsig.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cucudq.cn/Article/details/gtkolubfyx.html

[Q20] IN 列表
来源：http://dali.meibo888.top/Article/details/gtbefrahyk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cdnleiting.top/Article/details/gtdeqkttsm.html

[Q21] 空值判断
来源：http://dali.aizwys.cn/Article/details/gtjyrfnowt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqfkrfbm.html

[Q22] 排序
来源：http://dali.dashuyun.cn/Article/details/gtnljessvn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guannengcc.top/Article/details/gtggkuhvvb.html

[Q23] 分页
来源：http://dali.daxiang520.top/Article/details/gtzhgaphfp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jianghu66.top/Article/details/gtkzomwjdl.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gtqscygrsy.html

SELECT DISTINCT city FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtrmylazwm.html

[Q25] 只取前 N 条
来源：http://dali.xuanzx.com/Article/details/gtynvwriag.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhoulong.xyz/Article/details/gtvnlfpxfw.html

[Q26] 计数
来源：http://dali.nwbrower.top/Article/details/gtwywqjlwh.html

SELECT COUNT(*) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtrvbkuice.html

[Q27] 条件计数
来源：http://dali.wangdashe.top/Article/details/gtlprwvkit.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtygvncckg.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gthoumxwog.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtorbnbkti.html

[Q29] 最大最小值
来源：http://dali.redwolf501.top/Article/details/gtmssbgsvh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yonumen.top/Article/details/gthttcpgmi.html

[Q30] 分组统计
来源：http://dali.gzhubu.top/Article/details/gtezqokdhq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhazkoxu.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gtugvukeih.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gtqldrdfan.html

[Q32] 分组拼接字符串
来源：http://dali.cheryme.top/Article/details/gtnumrdljh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtzunorgle.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenjidiqi.icu/Article/details/gtifnuufku.html

[Q33] 多列分组
来源：http://dali.cheryme.top/Article/details/gtktxxkkyd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sufxvd.cn/Article/details/gtphhflsob.html

[Q34] 每组取第一条
来源：http://dali.quarkkingdee.top/Article/details/gtjraszuaz.html

SELECT * FROM (
来源：http://dali.chenlongwang.top/Article/details/gtbxuodzpp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhixingplan.top/Article/details/gtbxgbyhwk.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gttjfljffa.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gtbgdeyhsb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtfodtmgcl.html

[Q36] 左连接
来源：http://dali.jinghuilouyu.cn/Article/details/gthfbbbyxv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gtzujlonnc.html

[Q37] 右连接
来源：http://dali.havefunace.top/Article/details/gtwvseakmp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhongyouzk.top/Article/details/gtolxhqrah.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gtokwcwhqs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258888.top/Article/details/gtergfkumc.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gtwdwwmzvb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.bjfxy.top/Article/details/gtqdhuzzpf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gtmfblfbsp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuxming.cn/Article/details/gtddexavhd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxodfdlxj.html

[Q41] 多表连接
来源：http://dali.zdqjudy.top/Article/details/gtcybqomxt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.iojbl.cn/Article/details/gtnwszrzmz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.meibo888.top/Article/details/gtvinxscua.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sysykeji.top/Article/details/gtoarkpzcq.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gtqimnnczq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnpzlwlx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sufxvd.cn/Article/details/gtfhchxtmt.html

[Q43] 标量子查询
来源：http://dali.dashuyun.cn/Article/details/gtaoogkfoe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtccgfkpxc.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gtobpaoxhh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fzhhl.top/Article/details/gtyczdxnkn.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gtrdmssypf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtusmrmyzl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gtgywrvxei.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcwwmfqf.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gtkzoembna.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtnoohqxdd.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gtuzsrlgyr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gtuhvztdcw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gthbuispls.html

[Q49] 更新单行
来源：http://dali.cdnleiting.top/Article/details/gtbhnzhxgz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gtoyjhvnyv.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gtxbneslqv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtkwzcntuw.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gtjdkasxbd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fzhhl.top/Article/details/gtimxicxob.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gtcvlqwwyv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtwuopkzvz.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gtuebnnvop.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gzhubu.top/Article/details/gtllekxkrg.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gtvadswiqr.html

TRUNCATE TABLE logs;
来源：http://dali.yuxming.cn/Article/details/gtbqwopenm.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gtyuvdypgr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtfmblzzdm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gtdcboawvd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtprkghwbv.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gtqubxqwhc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtgfhfhgtm.html

[Q58] 累计求和
来源：http://dali.mhx1999.top/Article/details/gtszxmralm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtwspyqkfr.html

[Q59] 分组内累计
来源：http://dali.sweek.top/Article/details/gtjzascxul.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtohkoqgok.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gtwygisosp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gthujisuip.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtuvpmdfzq.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gtzabviqhp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtvfapurwy.html

[Q62] 分组占比
来源：http://dali.ehwqpu.com/Article/details/gtmprvfxxf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtflcotnwk.html

[Q63] 开启事务
来源：http://dali.ehwqpu.com/Article/details/gtzgboshzt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gttkvpxaer.html

[Q64] 提交事务
来源：http://dali.sxryk.cn/Article/details/gtgbtdtsln.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gtqfphoqql.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gtjmhkboft.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gtvwvgmonp.html

[Q66] 行锁查询
来源：http://dali.zhoulong.xyz/Article/details/gtmtswtnao.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gtnjdkdnsr.html

[Q67] 设置隔离级别
来源：http://dali.svipenyu.cn/Article/details/gtsxoqxoea.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gtvxsuoxrv.html

[Q68] 保存点
来源：http://dali.gzhubu.top/Article/details/gtsqgybexq.html

SAVEPOINT sp1;
来源：http://dali.havefunace.top/Article/details/gtlektqdja.html

ROLLBACK TO sp1;
来源：http://dali.jqgufenzy.top/Article/details/gttaisddcs.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gtyorwxksr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtrwhkzaik.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gtkbwgmujc.html

ANALYZE TABLE users;
来源：http://dali.andypj.xyz/Article/details/gtfymoqfpq.html

[Q71] 查看建表语句
来源：http://dali.yj20258888.top/Article/details/gtmzkitgef.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.birdmap.top/Article/details/gtnsyimclt.html

[Q72] 查看索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmrrutnv.html

SHOW INDEX FROM users;
来源：http://dali.tanke756.top/Article/details/gtbwbbglkz.html

[Q73] 查看表状态
来源：http://dali.zhiwuduotai.top/Article/details/gtnmzqdidr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nwbrower.top/Article/details/gtkmmbadux.html

[Q74] 强制使用索引
来源：http://dali.xinyue.icu/Article/details/gtugjvdnou.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hfpthk.cn/Article/details/gtkrsascjt.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtzcnzzbze.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtkcdkmufk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.haohaochexian.top/Article/details/gtzqmvpblr.html

[Q76] 按天统计
来源：http://dali.aibaodan.cn/Article/details/gtnllistss.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258.top/Article/details/gtvdpgmlae.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdthhjys.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthveooyml.html

[Q78] 当前时间
来源：http://dali.shzxlz.cn/Article/details/gtkoaedmmy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tianlin.xyz/Article/details/gtfgctofsl.html

[Q79] 字符串拼接
来源：http://dali.birdmap.top/Article/details/gtjngintwz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigfzy.top/Article/details/gthltglaup.html

[Q80] 字符串截取
来源：http://dali.yvedp.cn/Article/details/gtsxpkihtx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtgqattyfg.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtyojoeurh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtepvcjhvp.html

[Q82] 字符长度与字节长度
来源：http://dali.havefunace.top/Article/details/gthukcaklo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtspqaqqtk.html

[Q83] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtsnmgjggd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtgjkbompy.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gtmtswsgwm.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtwniybhqh.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gtdqvxbrgc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gttazeepao.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gttivcoqzq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gtikghtgxl.html

[Q87] JSON 字段做条件
来源：http://dali.chenzaomai.com/Article/details/gtbewaiisk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gtyapgmgct.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gtgxnvsqjt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztgpvdyn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gtavmhxleq.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gtpdcgnavo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcqckyly.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gtszghffei.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj202588.top/Article/details/gtmbgizxys.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttsxxihso.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gtagbanlng.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnjgpzaub.html

[R01] shebang 与严格模式
来源：http://dali.jiagoushi.top/Article/details/gtomqnrudo.html

#!/usr/bin/env bash
来源：http://dali.jianghu66.top/Article/details/gteqaoazhp.html

set -euo pipefail
来源：http://dali.jiagoushi.top/Article/details/gthwmsqxlf.html

[R02] 变量赋值与使用
来源：http://dali.fzhhl.top/Article/details/gtdbtwtils.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gtdfooebom.html

[R03] 只读变量
来源：http://dali.ydzc1.top/Article/details/gtvbevdlkn.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gtorblnjps.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtykmxqijn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gthtyxyozq.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtsiegdkxs.html

name="${1:-default}"
来源：http://dali.hongshengwenyu.top/Article/details/gtgdrzwsmc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtaaqnfjdz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtwgumslef.html

[R07] if 判断文件
来源：http://dali.jqgufenzy.top/Article/details/gtwnsxzvez.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gtqccgdxwr.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gthmucayca.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj202588.top/Article/details/gtjbynkhas.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtowmhkccv.html


<!-- 参考信息 -->