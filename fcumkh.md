代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gtvkkegsok.html

[P02] MD5 / SHA256 摘要
来源：http://dali.bjfxy.top/Article/details/gtmwqdussq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gtqzozztwu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gtaxzhxmph.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gthrmrojbq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xylfe.cn/Article/details/gtzcdevuqk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nwbrower.top/Article/details/gtuwpjyzbk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aizwys.cn/Article/details/gthpvorufd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258.top/Article/details/gtnpuwcztr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jianghu66.top/Article/details/gtgyxpxwxq.html

[P03] 生成短随机字符串
来源：http://dali.0kj1m.cn/Article/details/gtsqksficj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuxming.cn/Article/details/gtgfomzeog.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyoqhnqsg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gtnudzvcdy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gtggsictmb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gtynhitbsa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.quarkkingdee.top/Article/details/gtzoqlfklg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yongpay.top/Article/details/gtkimvadui.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xinyue.icu/Article/details/gtdspssaqs.html

[P04] 求长度
来源：http://dali.yj202588.top/Article/details/gtkaiusxlh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.quarkkingdee.top/Article/details/gtjglnhjfz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiebhtws.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gtmthdqgtd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gtnsuxidsc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtsdolrxri.html

Go:   len(arr);  len(m)
来源：http://dali.yonumen.top/Article/details/gtvuwlghwk.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gtohvyflhc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtsrpikjyo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pycfn.com/Article/details/gtkexfwmiw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yongpay.top/Article/details/gtyqbtwkll.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jianghu66.top/Article/details/gtmsgxjtdo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.havefunace.top/Article/details/gtptnzpfrw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtajdapzoy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.kuanghao11.cn/Article/details/gtgqgitcnd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtdjsgnpuy.html

Ruby: a == b
来源：http://dali.jinqigufen.top/Article/details/gtenulopqh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.snrcjt.cn/Article/details/gtckfntrmo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aizwys.cn/Article/details/gtwlgztyfw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gaohongyu789.top/Article/details/gttuifmlbe.html

PHP:  if (empty($x)) {}
来源：http://dali.gotoacloud.top/Article/details/gtvpwomofq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sufxvd.cn/Article/details/gtfodnwfmp.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gtthepxerr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gthzxovgnj.html

Go:   if x == nil {}
来源：http://dali.yangfankeji.com/Article/details/gtunrmsaei.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sufxvd.cn/Article/details/gthlmlemcv.html

C#:   if (x is null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdzzrsyd.html

[P07] 防抖与节流
来源：http://dali.tianlin.xyz/Article/details/gtluesnmoj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.smart0.xyz/Article/details/gtyabxubol.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gtxzvfobnh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtpqwcncgz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtbvyvqkpy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gtcesuctuv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yonumen.top/Article/details/gtdbkpwtbi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cdnleiting.top/Article/details/gthvnsuzxw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gtkgctgvlk.html

[P08] 处理浮点精度问题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyodkpyea.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnqzz.top/Article/details/gtqqngwzjf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daxiang520.top/Article/details/gtrwzjbayo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.0kj1m.cn/Article/details/gtodmfxwhv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtvzzwlupc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gttozzltqa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gtxebqzziv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gtyugirfuj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daria6918.cn/Article/details/gtvcidnxns.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmmtmqitm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fzhhl.top/Article/details/gtcmscgxtm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkrcfhvrx.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gtdgqgjsec.html

CREATE TABLE users (
来源：http://dali.0kj1m.cn/Article/details/gtyffdaktg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtowsffzzq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtfwwdflhe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sweek.top/Article/details/gtlzveawcu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gtnznllzfe.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtvlhvgduq.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gtpxtufyhi.html

CREATE TABLE orders (
来源：http://dali.wangshuangyany.cn/Article/details/gtgaqnwhbp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtilstzpgi.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtwnrvjfms.html

amount DECIMAL(10, 2),
来源：http://dali.smart0.xyz/Article/details/gtfnajuvin.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aibaodan.cn/Article/details/gtrjarvwho.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtdpxbrnrp.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtheslwrtz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tianlin.xyz/Article/details/gtxlfgguyk.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gtseesukci.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cdnleiting.top/Article/details/gtjfaoimkn.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gtvdvdxzbi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.birdmap.top/Article/details/gtqelnqeeo.html

[Q06] 删除列
来源：http://dali.gogol.net.cn/Article/details/gtpvpwdfqw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cqqwz.cn/Article/details/gtdvfhnypc.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gtcjlowpft.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gtlbjhqapx.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtfnvcwzxb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtskafgypk.html

[Q09] 创建唯一索引
来源：http://dali.ivvv.top/Article/details/gtkgxxvnux.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gtrnipruyh.html

[Q10] 插入单行
来源：http://dali.hysaishi.cn/Article/details/gtslocvfhu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtmhwberep.html

[Q11] 一次插入多行
来源：http://dali.jlsjyb.cn/Article/details/gtazudlkzb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gtlqtansrw.html

[Q12] 插入后取自增 ID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttozrdrhx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gtzhznonqu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gtfyengnek.html

[Q13] 忽略重复插入
来源：http://dali.jinghuilouyu.cn/Article/details/gtppdnuslz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.iojbl.cn/Article/details/gtwtlljqbe.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gtmcuxnscf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.316326.xyz/Article/details/gtcqivanfd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnqzz.top/Article/details/gtozxwcunj.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgbqqitj.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtlhnvxciq.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gtkeddywld.html

SELECT id, name FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtgrxxctve.html

[Q17] 条件查询
来源：http://dali.xuanzx.com/Article/details/gthmfpzsku.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gttannhgmd.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gtxzjkjlgh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.svipenyu.cn/Article/details/gtesvmibbx.html

[Q19] 范围查询
来源：http://dali.hongshengwenyu.top/Article/details/gtrexayjfr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.svipenyu.cn/Article/details/gtswrdplnk.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gtchujadpg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xylfe.cn/Article/details/gtkwcxpbqf.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gtktwlqnsx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtlhmbtrmi.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gtrdkrnzsc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gtpxolszgd.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gtrtutfmoi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gtxxgscnns.html

[Q24] 去重
来源：http://dali.gzhubu.top/Article/details/gtnrgdtelr.html

SELECT DISTINCT city FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtucskvrpj.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gttembmrdn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cheryme.top/Article/details/gtilsixlhd.html

[Q26] 计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiatufpcw.html

SELECT COUNT(*) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtsaidwutw.html

[Q27] 条件计数
来源：http://dali.havefunace.top/Article/details/gtqwfpihqn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gthxqhpjvt.html

[Q28] 求和与平均
来源：http://dali.shangyingyoupin.top/Article/details/gtvjccodut.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtfswqccbp.html

[Q29] 最大最小值
来源：http://dali.snrcjt.cn/Article/details/gtiozyihri.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtakxhpdlr.html

[Q30] 分组统计
来源：http://dali.feifeiyinyue.top/Article/details/gtmzbjrbgh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtgupiuxfg.html

[Q31] 分组后过滤
来源：http://dali.gaohongyu789.top/Article/details/gtbqnameto.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtwkubhait.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtbzgwwqfe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtjekfwqjt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daria6918.cn/Article/details/gtgfwhjiab.html

[Q33] 多列分组
来源：http://dali.yvedp.cn/Article/details/gtkoxtvyfs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sufxvd.cn/Article/details/gtfpqdjile.html

[Q34] 每组取第一条
来源：http://dali.jqgufenzy.top/Article/details/gthfsplwtl.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gtmlxqkhvy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsmnvpyp.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtofawouzn.html

[Q35] 内连接
来源：http://dali.jqgufenzy.top/Article/details/gtwwsjojho.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtoqygasjn.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gtivfyujmx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtsmnsaogv.html

[Q37] 右连接
来源：http://dali.cashguo.top/Article/details/gttxgjsgbb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgufenzy.top/Article/details/gtrpkhcziw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daxiang520.top/Article/details/gtpntustkq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shzxlz.cn/Article/details/gtwfsytsef.html

[Q39] 自连接（查上下级）
来源：http://dali.guannengcc.top/Article/details/gtiodhtsfq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hysaishi.cn/Article/details/gtptvymcpf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gttggvycrq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xylfe.cn/Article/details/gtpiymdewv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gtbckkhpze.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gtjtbtebku.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gtaxqgzgre.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gtzoudzhqs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gtvwrwiycz.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258.top/Article/details/gtjhprzbss.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gtlvsvvrcn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtigvvmrqn.html

[Q43] 标量子查询
来源：http://dali.aibaodan.cn/Article/details/gtbtjlmpnh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cheryme.top/Article/details/gtlxibydjo.html

[Q44] IN 子查询
来源：http://dali.xylfe.cn/Article/details/gtbyqyvizb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenzaomai.com/Article/details/gtcwascnpl.html

[Q45] EXISTS 判断存在
来源：http://dali.snrcjt.cn/Article/details/gtzdljdlro.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtbjdtywnd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gtnlgzdtyn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtxxdboamw.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gtsdjzkcwm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigufen.top/Article/details/gthydgezef.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gtllskamgc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgufenzy.top/Article/details/gtacmzckqr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnxiangtu.top/Article/details/gtzrncwjdp.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gtnbxasqmr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtobfqatxw.html

[Q50] 批量更新
来源：http://dali.shzxlz.cn/Article/details/gtodfgnibx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ydzc1.top/Article/details/gtzotzicni.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gtvhnpzhdt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daxiang520.top/Article/details/gtfehbzlxp.html

[Q52] 删除指定行
来源：http://dali.aibaodan.cn/Article/details/gtjlxyskwk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtgeyydnba.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gtbztmglfi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gteczjsmje.html

[Q54] 清空表
来源：http://dali.iojbl.cn/Article/details/gtopxvvwly.html

TRUNCATE TABLE logs;
来源：http://dali.tian-w.cn/Article/details/gteyampchk.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gteqwgvbct.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtnkuykwwb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sysykeji.top/Article/details/gtpucxjkkz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtdzwaxydp.html

[Q57] 行号
来源：http://dali.hysaishi.cn/Article/details/gtdqmviyti.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gtzhznkcvx.html

[Q58] 累计求和
来源：http://dali.havefunace.top/Article/details/gtruoedirn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtgtlueezx.html

[Q59] 分组内累计
来源：http://dali.hysaishi.cn/Article/details/gtezskmluy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gttrlethew.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgfzy.top/Article/details/gtyrbczajc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fzhhl.top/Article/details/gtkyurtytt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtlqicnuea.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gtbzpnlmll.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfuwwhdb.html

[Q62] 分组占比
来源：http://dali.zhixingplan.top/Article/details/gtswltirjd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtkspcdbse.html

[Q63] 开启事务
来源：http://dali.hnqzz.top/Article/details/gtivpahimi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.0kj1m.cn/Article/details/gtbzcqyzkc.html

[Q64] 提交事务
来源：http://dali.gotoacloud.top/Article/details/gtlnxwgzhn.html

COMMIT;
来源：http://dali.bjfxy.top/Article/details/gtapxuymdo.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gtdjiipsug.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gticjgbgcr.html

[Q66] 行锁查询
来源：http://dali.jinqigfzy.top/Article/details/gtbdjjnxbc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitxlrpxd.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gttobfzpnf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenlongwang.top/Article/details/gtukrmyvvn.html

[Q68] 保存点
来源：http://dali.chenjidiqi.icu/Article/details/gtyuxwwsmb.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtamkyhpby.html

ROLLBACK TO sp1;
来源：http://dali.c1oappe.top/Article/details/gtlgundkdl.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gtoazhgnzh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnqzz.top/Article/details/gtcyqymwwp.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gthllaxfzt.html

ANALYZE TABLE users;
来源：http://dali.chenjidiqi.icu/Article/details/gtstmhhqlv.html

[Q71] 查看建表语句
来源：http://dali.jlsjyb.cn/Article/details/gtclbkxrpx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yongpay.top/Article/details/gtsvwyqwln.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gtabwbavgr.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtvodasuev.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gtyngdhlrq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aibaodan.cn/Article/details/gtqwtuylld.html

[Q74] 强制使用索引
来源：http://dali.sufxvd.cn/Article/details/gtfbhmxlxl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gtuzfumhwx.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtnhykljdj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtrzaxjduy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.havefunace.top/Article/details/gtkzrdzgtp.html

[Q76] 按天统计
来源：http://dali.vqdsnc.cn/Article/details/gtsnliaxxl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ydzc1.top/Article/details/gtodvjkehe.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gtamhdneiq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gtpahvnzld.html

[Q78] 当前时间
来源：http://dali.jiagoushi.top/Article/details/gtkfvpqenn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gtwygdnagr.html

[Q79] 字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtwjcxnmlu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gtlscacprn.html

[Q80] 字符串截取
来源：http://dali.fengsongda.top/Article/details/gtorzfpmpc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sysykeji.top/Article/details/gttsaqaziu.html

[Q81] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtsbngiewd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtwidhzqdg.html

[Q82] 字符长度与字节长度
来源：http://dali.xuanzx.com/Article/details/gtnrutredv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmlrxdgl.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtfbyisdqi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtwlgolkuv.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkofpojf.html

SELECT TRIM(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtgahcgogy.html

[Q85] 数值取整
来源：http://dali.xuetiantiany.cn/Article/details/gtoiynfrky.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gtwkzgjfoo.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gtvtmimuki.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gtqtjqcpbi.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gtcarkldko.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.svipenyu.cn/Article/details/gtzeikghbe.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtrdadhmra.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigfzy.top/Article/details/gtbxowvjlp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258888.top/Article/details/gtfgtrxnek.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gtxrtjkuup.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yvedp.cn/Article/details/gtrtmlmpfi.html

[Q90] 生成序号列
来源：http://dali.yuanzhike.top/Article/details/gtfvwtrzlv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gtsxhptzdx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthfyhtnfz.html

R. Bash 专题
来源：http://dali.ydzc1.top/Article/details/gthgvgpqgc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyoduuojz.html

[R01] shebang 与严格模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzdaucco.html

#!/usr/bin/env bash
来源：http://dali.316326.xyz/Article/details/gtvbfwkijt.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gtswofavgr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gtuzodsoat.html

name="Tom"; echo "$name"
来源：http://dali.zycfv.cn/Article/details/gtqbsmiyvr.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gtmgsxdzdy.html

readonly PI=3.14
来源：http://dali.zhiwuduotai.top/Article/details/gtcnmxuavq.html

[R04] 位置参数
来源：http://dali.svipenyu.cn/Article/details/gtuilgnwyi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yvedp.cn/Article/details/gtdrhcyjnq.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gtuptslqkz.html

name="${1:-default}"
来源：http://dali.jianghu66.top/Article/details/gthxayevta.html

[R06] 判断命令是否存在
来源：http://dali.zdqjudy.top/Article/details/gtnmavablz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtxuhmzoxw.html

[R07] if 判断文件
来源：http://dali.guowangkeji.top/Article/details/gttnhrmokg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gtygenqfnt.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gtsuzyftfn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuanzx.com/Article/details/gtqiyjqfjy.html

[R09] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtyduukjtv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gtsivuvuop.html

[R10] 正则匹配
来源：http://dali.ydzc1.top/Article/details/gttvyjnuqc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtqsqgmaml.html

[R11] case 多分支
来源：http://dali.feifeiyinyue.top/Article/details/gtncwghfvy.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gtvslsvsju.html

start) echo "启动" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtqceogpct.html

stop)  echo "停止" ;;
来源：http://dali.nwbrower.top/Article/details/gtzacdlngt.html

*)     echo "未知命令" ;;
来源：http://dali.yangfankeji.com/Article/details/gtdbqnhlvl.html


<!-- 参考信息 -->