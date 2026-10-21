代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlaekylsx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shangyingyoupin.top/Article/details/gtsgluxblq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitrrxisg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yonumen.top/Article/details/gtfurhvrpl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zycfv.cn/Article/details/gtxadpinmx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ybcxt.top/Article/details/gtxlpgngdh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gtkpczhask.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ivvv.top/Article/details/gtclutclkk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gtzumbidoa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fzhhl.top/Article/details/gtxvgkjfir.html

[P03] 生成短随机字符串
来源：http://dali.hysaishi.cn/Article/details/gttetcgauh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gtdzjeieuv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmplfchtl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtdvpgoeml.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtrdcnizit.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fengsongda.top/Article/details/gtfollaoon.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shangyingyoupin.top/Article/details/gtsrvgardn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvlsjqcy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gtbefpejbk.html

[P04] 求长度
来源：http://dali.andypj.xyz/Article/details/gtosusqxgb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gtyhfcgdtg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtduvoykto.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffgupvov.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gteogxaruw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtgobktjot.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gtvlbvbdpo.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gtceyzbzit.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtcveijqgn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pengpengdd.cyou/Article/details/gtvcxnmvon.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yueranfly.top/Article/details/gtufvxtrwg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gtizydesya.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guowangkeji.top/Article/details/gtmghqipbt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtmuyuwhfn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.snrcjt.cn/Article/details/gtoxylqakt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtterjxetn.html

Ruby: a == b
来源：http://dali.wangshuangyany.cn/Article/details/gthgurzdkq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nwbrower.top/Article/details/gtwwyzezkf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvrxiiqb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gtexliegri.html

PHP:  if (empty($x)) {}
来源：http://dali.zhengqikj.top/Article/details/gtklllyqae.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gtlywllcet.html

TS:   if (x == null) {}
来源：http://dali.gzhubu.top/Article/details/gtjitdpkuj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtcwmcjjia.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gtqxwvjexr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuanzx.com/Article/details/gtbvcbaiux.html

C#:   if (x is null) {}
来源：http://dali.sxryk.cn/Article/details/gtcmatxwyr.html

[P07] 防抖与节流
来源：http://dali.yj20258.top/Article/details/gtipujzhjk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gtlcestjkr.html

PHP:  // 手写时间戳比较
来源：http://dali.gotoacloud.top/Article/details/gtmquwpjma.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtoxsopalt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtfortnyml.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ivvv.top/Article/details/gtcgotgdle.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhixingplan.top/Article/details/gtmrdjrdqn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtpwgjxmuz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sufxvd.cn/Article/details/gtgitnhbec.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gtzvlxsviz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sufxvd.cn/Article/details/gtwmxjrfvv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tanke756.top/Article/details/gtzsbrpeqr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgufenzy.top/Article/details/gtasmyrlcc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gtmpzgqmna.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gtdnzcadvu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhoulong.xyz/Article/details/gtomxosnns.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yueranfly.top/Article/details/gtgxapgcik.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.meibo888.top/Article/details/gtdlfuhvki.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtubncvgkp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gtiwvsfqft.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvgepscdp.html

[Q01] 创建表
来源：http://dali.dashuyun.cn/Article/details/gtjeaodqxu.html

CREATE TABLE users (
来源：http://dali.vqdsnc.cn/Article/details/gtfjgloxqu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gtjwxipdcl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtycjxfszi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangshuangyany.cn/Article/details/gtexgznuud.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ydzc1.top/Article/details/gtzdmlggpf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gttgezovfu.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gtdvidhmhv.html

CREATE TABLE orders (
来源：http://dali.chenjidiqi.icu/Article/details/gtbjgmrxzc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gtizzieaur.html

user_id INT NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtfeyeesxt.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gterveiwkn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj202588.top/Article/details/gtndxaadll.html

);
来源：http://dali.birdmap.top/Article/details/gttfheihpp.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gtxkjyhlnd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gtzakrixjs.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuywxmhyb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gtqbjwaisq.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gtntpqpext.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gtqkodyjve.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gtnqfyocwk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hywenlv.cn/Article/details/gtmhswthdq.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gtyfjckgwm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhixingplan.top/Article/details/gttymrfcaz.html

[Q08] 创建普通索引
来源：http://dali.cashguo.top/Article/details/gtiosmkznw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gtkcdnbaeo.html

[Q09] 创建唯一索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtscqnlrin.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtblcoievx.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gtcliplkrk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.redwolf501.top/Article/details/gtyvbxzuha.html

[Q11] 一次插入多行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapnhbgmh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jianghu66.top/Article/details/gtrmddwudu.html

[Q12] 插入后取自增 ID
来源：http://dali.c1oappe.top/Article/details/gtyniukdiz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gtrpjpqyfr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenzaomai.com/Article/details/gtdvcanhft.html

[Q13] 忽略重复插入
来源：http://dali.hongshengwenyu.top/Article/details/gtzbabljcn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtvuzvzkoi.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gteskiaskb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.birdmap.top/Article/details/gtbigkjlsr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxuanxn.top/Article/details/gtlehrymsp.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gtyvevppli.html

SELECT * FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtfqwufxyd.html

[Q16] 查询指定列
来源：http://dali.guannengcc.top/Article/details/gtsixuxxwh.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtwmxwsplw.html

[Q17] 条件查询
来源：http://dali.zdqjudy.top/Article/details/gtgauvtncz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdelvzsfb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gtalpxcaav.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.316326.xyz/Article/details/gtqyhmsbyi.html

[Q19] 范围查询
来源：http://dali.zhixingplan.top/Article/details/gtrmjfnuhs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gtwxoycdhe.html

[Q20] IN 列表
来源：http://dali.yj20258888.top/Article/details/gtmyuctxbz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gtvffruefz.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gtmeauvpmi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tianlin.xyz/Article/details/gtrkjwsmqj.html

[Q22] 排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxcclhgr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shuidangran.top/Article/details/gttlhxjjtr.html

[Q23] 分页
来源：http://dali.pycfn.com/Article/details/gtexrbzhmu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.kuanghao11.cn/Article/details/gtysmmtbff.html

[Q24] 去重
来源：http://dali.hywenlv.cn/Article/details/gtvwscrnlz.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtktmiywmx.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtlekyibvn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258.top/Article/details/gtktcmeiaz.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gtznaqqctl.html

SELECT COUNT(*) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtnudzovlf.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gtqabkhjnq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gtqdxekgle.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gtzgsihctu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gttxkvqkwv.html

[Q29] 最大最小值
来源：http://dali.zycfv.cn/Article/details/gtoeufaymr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtessbatcu.html

[Q30] 分组统计
来源：http://dali.bjfxy.top/Article/details/gtlerxfnlj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtghwrhvsq.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gtlmdiehro.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gtghzdloxc.html

[Q32] 分组拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gthaaxzsjv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtiixjuqrv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gtuhswsbgm.html

[Q33] 多列分组
来源：http://dali.fengsongda.top/Article/details/gtqdzkgyvm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.9152youxi.cn/Article/details/gtffleegdt.html

[Q34] 每组取第一条
来源：http://dali.redwolf501.top/Article/details/gtphzsxpmg.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gtltfbfbom.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hfpthk.cn/Article/details/gtsizcdohd.html

) t WHERE rn = 1;
来源：http://dali.haohaochexian.top/Article/details/gtmiusbbsk.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gtmggoiigp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gttgaybifo.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gtssimwefv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtfisyhvnn.html

[Q37] 右连接
来源：http://dali.fzhhl.top/Article/details/gtkmvaganq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dashuyun.cn/Article/details/gtmcacvmbn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ivvv.top/Article/details/gtfxaziavo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jlsjyb.cn/Article/details/gtlwbyvyna.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gthkvaetnc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shuidangran.top/Article/details/gtddolaxso.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.svipenyu.cn/Article/details/gtnxhgkytj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cucudq.cn/Article/details/gtbroeytmc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgfzy.top/Article/details/gtsojufimp.html

[Q41] 多表连接
来源：http://dali.zhongyouzk.top/Article/details/gtuctvkwkb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxuanxn.top/Article/details/gtvkrpdpri.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinghuilouyu.cn/Article/details/gtenhjpjzs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.0kj1m.cn/Article/details/gtzwdjalat.html

[Q42] 连接条件附加过滤
来源：http://dali.quarkkingdee.top/Article/details/gtvnxfmdzh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuxming.cn/Article/details/gtnynplygx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258888.top/Article/details/gtediwabyx.html

[Q43] 标量子查询
来源：http://dali.kuanghao11.cn/Article/details/gtpdcdauah.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gtenijfxol.html

[Q44] IN 子查询
来源：http://dali.jlsjyb.cn/Article/details/gtbttbozkt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqbihlpr.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgufenzy.top/Article/details/gtwfgzaruf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtppzcxcaj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tian-w.cn/Article/details/gtqljjfpbc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtrvkdfntz.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gtetrisxhr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xylfe.cn/Article/details/gtlcmlwyde.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gtdgqmeeqh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gtisoiqxxq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gtywczbfqs.html

[Q49] 更新单行
来源：http://dali.hfpthk.cn/Article/details/gtxcybrlrl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtdgpkajbv.html

[Q50] 批量更新
来源：http://dali.snrcjt.cn/Article/details/gtwicbyxhp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hammf.cn/Article/details/gtaagfzzmb.html

[Q51] 用子查询更新
来源：http://dali.zhengqikj.top/Article/details/gtsmbzgzvd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gtfwpkslqf.html

[Q52] 删除指定行
来源：http://dali.jqgfzy.top/Article/details/gtuulbocdx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtwznnlmdx.html

[Q53] 按条件删除
来源：http://dali.tianlin.xyz/Article/details/gtrivotvli.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gteeeibmmq.html

[Q54] 清空表
来源：http://dali.wangdashe.top/Article/details/gtzryoydrg.html

TRUNCATE TABLE logs;
来源：http://dali.cashguo.top/Article/details/gtbsdjadms.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gtulusazrp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtdxvoyfbs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtorqamwat.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtwvavyslf.html

[Q57] 行号
来源：http://dali.svipenyu.cn/Article/details/gtzjjetmqs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtpqncbvkg.html

[Q58] 累计求和
来源：http://dali.yj202588.top/Article/details/gtjhkqlrbw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtcydtgqcb.html

[Q59] 分组内累计
来源：http://dali.meibo888.top/Article/details/gtbibqxbdk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtnmgbvxdm.html

[Q60] 取上一行 / 下一行
来源：http://dali.pycfn.com/Article/details/gtohxyghrn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuetiantiany.cn/Article/details/gthdvjnpnr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtrvspbzlu.html

[Q61] 移动平均
来源：http://dali.shzxlz.cn/Article/details/gtpoelahtw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gteoxwysme.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtlwnlpbgr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtlytvepgl.html

[Q63] 开启事务
来源：http://dali.xuetiantiany.cn/Article/details/gtkzekrrnx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hysaishi.cn/Article/details/gtbnaadmor.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gteqecpxoo.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gtrziflabd.html

[Q65] 回滚事务
来源：http://dali.c1oappe.top/Article/details/gtchttpmnn.html

ROLLBACK;
来源：http://dali.fengsongda.top/Article/details/gtkfvcodki.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gtxbbhxzgr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gtarljpryy.html

[Q67] 设置隔离级别
来源：http://dali.sxryk.cn/Article/details/gtdtgqdhas.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.vqdsnc.cn/Article/details/gtlhmhjfnf.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gtfwwcgtxm.html

SAVEPOINT sp1;
来源：http://dali.dianchejie.cn/Article/details/gttciovxzm.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gtervkxrlh.html

[Q69] 查看执行计划
来源：http://dali.ppjwa.cn/Article/details/gtsnqvwvfj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgfzy.top/Article/details/gtnahasxeg.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gtbxswqikd.html

ANALYZE TABLE users;
来源：http://dali.jlsjyb.cn/Article/details/gtltuiuxku.html

[Q71] 查看建表语句
来源：http://dali.jqgufenzy.top/Article/details/gtvigueswf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gtyfiyneje.html

[Q72] 查看索引
来源：http://dali.yj202588.top/Article/details/gtghlbgdof.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtusqfiumi.html

[Q73] 查看表状态
来源：http://dali.feifeiyinyue.top/Article/details/gteyfdyhhu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.kuanghao11.cn/Article/details/gtqooplcgg.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gtafmolwdl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gzhubu.top/Article/details/gtfibrulcm.html

[Q75] 日期格式化
来源：http://dali.sweek.top/Article/details/gthijxauxt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtrmafushq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gtnpriuyxd.html

[Q76] 按天统计
来源：http://dali.sxryk.cn/Article/details/gtmmlleytq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangshuangyany.cn/Article/details/gtbkaroopu.html

[Q77] 时间加减
来源：http://dali.gaohongyu789.top/Article/details/gtmnkthxgd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shuidangran.top/Article/details/gtnavxufqj.html

[Q78] 当前时间
来源：http://dali.chenlongwang.top/Article/details/gthtybgzrw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yangfankeji.com/Article/details/gtgptnktqg.html

[Q79] 字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtplxnpldr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnqzz.top/Article/details/gtlwdkdpyn.html

[Q80] 字符串截取
来源：http://dali.dashuyun.cn/Article/details/gtcnlewuen.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gttophgsno.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtsglelrdk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtgtbeyamo.html

[Q82] 字符长度与字节长度
来源：http://dali.pycfn.com/Article/details/gtbfirisue.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtgfydtebm.html

[Q83] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtdtdvboyf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gttdsqxurs.html

[Q84] 去除首尾空格
来源：http://dali.dashuyun.cn/Article/details/gtbbxhfmyb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtxtvvybhj.html

[Q85] 数值取整
来源：http://dali.andypj.xyz/Article/details/gtbnnulfcf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gtnksajczp.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgavjkdt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gtqjcpolbl.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gtjumbjokt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywmqpttp.html

[Q88] 行转列（条件聚合）
来源：http://dali.smart0.xyz/Article/details/gtosprzhar.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gtgzbzdkfj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtdzepzjzl.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtmqctygrb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sweek.top/Article/details/gtijtezvib.html

[Q90] 生成序号列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwtxfyuo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shzxlz.cn/Article/details/gtzpkmgycy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqispvtnn.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gttqtlrwpe.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtmjrvokme.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gtcauequqp.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gteecnioyh.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gtloctrsuu.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gtkaxdfebk.html

name="Tom"; echo "$name"
来源：http://dali.daria6918.cn/Article/details/gthwajllap.html

[R03] 只读变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxzqyvbg.html

readonly PI=3.14
来源：http://dali.jinqigfzy.top/Article/details/gtursdsfns.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gtnfyphhna.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenjidiqi.icu/Article/details/gtgwiokpna.html

[R05] 参数默认值
来源：http://dali.yuanzhike.top/Article/details/gtorsucqek.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gtxsabcriy.html

[R06] 判断命令是否存在
来源：http://dali.smart0.xyz/Article/details/gtoaglzvhu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtwxuwrbzj.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gtwmpkqbxr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrvhwode.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gtrleitmyx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtreuemnqv.html

[R09] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtimkqmrix.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sweek.top/Article/details/gtgfzaokyl.html

[R10] 正则匹配
来源：http://dali.jyoumei.cn/Article/details/gtfthbbzce.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gogol.net.cn/Article/details/gtnlbwgysa.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gtadzsklqr.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gtjftyzhsh.html

start) echo "启动" ;;
来源：http://dali.jyoumei.cn/Article/details/gtexxwgrkr.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfauxoxuk.html

*)     echo "未知命令" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtzzdsijny.html


<!-- 参考信息 -->