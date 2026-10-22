代发 wailian999

[O06] 使用进程池
来源：http://dali.meibo888.top/Article/details/gtidrnisib.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xinyue.icu/Article/details/gtocrwrfns.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gtfmbrrpiu.html

JS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtfnwdszqz.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkfklsft.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cashguo.top/Article/details/gtstlidclw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gttngzlcge.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gtxizdyfpf.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gtqkrfivrm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtvhdnmexd.html

P. 常用工具函数
来源：http://dali.haohaochexian.top/Article/details/gtutjfdipj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtltsjtiny.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gtpgwqocyw.html

Py:   str(uuid.uuid4())
来源：http://dali.sxryk.cn/Article/details/gtdhtolfau.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtqcikszbj.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtphujktqw.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtoibrsvbc.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtpndnxtdf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gtpdcklifs.html

Ruby: SecureRandom.uuid
来源：http://dali.xuanzx.com/Article/details/gtnfvpkamc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xylfe.cn/Article/details/gtaeyqlfjy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guowangkeji.top/Article/details/gtnuctmfsv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sweek.top/Article/details/gtbefpeiga.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cashguo.top/Article/details/gtxojssizr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gtnhkleels.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daxiang520.top/Article/details/gtkwxwnxtt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtueueacmd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zdqjudy.top/Article/details/gtphmpxdjx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gtanbtmwwj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtsyrxjkrd.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gtsdudkevx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cucudq.cn/Article/details/gtzbmefxse.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gtoaprcetz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtuahnckep.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtbcdjsozm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gtxeekxtdf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegizxzvn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ydzc1.top/Article/details/gtvkujvarg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhiwuduotai.top/Article/details/gtiftlcbgd.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gtilfapwun.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gotoacloud.top/Article/details/gtoicgkpby.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtuvxaxrzn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtbgnsmkau.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtuydzyakc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtmmlmtrvd.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gttuqonewm.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gttfcjpesa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtkrsolqlw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gtitjkhlfo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnqzz.top/Article/details/gtwzvrfgbk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.birdmap.top/Article/details/gtupqbcfbu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jyoumei.cn/Article/details/gtyyijjqhi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gtpnnjpkiu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gthftwpwus.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtcvxzuldi.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gthqdturuw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yonumen.top/Article/details/gtdkkadmoi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gtcfqcnjgj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtyzhetaqd.html

PHP:  if (empty($x)) {}
来源：http://dali.havefunace.top/Article/details/gtskhdigby.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.birdmap.top/Article/details/gtdaadhlxv.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gtqutofytl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtxifkhzkm.html

Go:   if x == nil {}
来源：http://dali.jyoumei.cn/Article/details/gtwugtbiby.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gttfidmcuj.html

C#:   if (x is null) {}
来源：http://dali.sweek.top/Article/details/gtxxfkndsx.html

[P07] 防抖与节流
来源：http://dali.fengsongda.top/Article/details/gtwzgyufbf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuxming.cn/Article/details/gtrcdkdxxn.html

PHP:  // 手写时间戳比较
来源：http://dali.andypj.xyz/Article/details/gtgfiyzavb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtpezrokgg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtbadtyreq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gaohongyu789.top/Article/details/gtgdkvzbyg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yangfankeji.com/Article/details/gtdhlpckds.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gtryylphad.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gteemqvmdz.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gtmxiswlnr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.aibaodan.cn/Article/details/gtydmadmlc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigufen.top/Article/details/gtpkdiqmfc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shuidangran.top/Article/details/gtjhxqxqvp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtzcxuxvlt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hammf.cn/Article/details/gtrxrmdcfb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hongshengwenyu.top/Article/details/gtymuknwto.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gtjxcznags.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daria6918.cn/Article/details/gtkornywki.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdrlchxce.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsldumacr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbtztvfky.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gtvxrmapxi.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gtlwaxzqdg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gtqljfdzux.html

name VARCHAR(50) NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gtourhcugd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ybcxt.top/Article/details/gtiwcdipnq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gtmtvbjmya.html

);
来源：http://dali.zdqjudy.top/Article/details/gttsnrampi.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gtoqrrgfar.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gtqayehmbj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbhjlamu.html

user_id INT NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtpzrnavtx.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gtykdixveh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtqbzpsmqy.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtcngxvryb.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtfycqfjdz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yueranfly.top/Article/details/gtdgrchhcb.html

[Q04] 修改列类型
来源：http://dali.svipenyu.cn/Article/details/gtcmekxddu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gtsixfjgzt.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gtrshopwmr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuanzx.com/Article/details/gtcuffqbbs.html

[Q06] 删除列
来源：http://dali.iojbl.cn/Article/details/gtuizsqomg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258888.top/Article/details/gttqfoaiah.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gtkgepgqwt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.smart0.xyz/Article/details/gtrirmglav.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gtccfujaqj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gthdnrkytu.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gtwryxjrif.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtsvlhxohs.html

[Q10] 插入单行
来源：http://dali.yanxiufei.cn/Article/details/gtrqsdsdqb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtbaylrjfw.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gtgseznjen.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.birdmap.top/Article/details/gtfyrxzwkg.html

[Q12] 插入后取自增 ID
来源：http://dali.hongshengwenyu.top/Article/details/gtngmwtbjj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gtajocaczn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gtnkeoltwz.html

[Q13] 忽略重复插入
来源：http://dali.quarkkingdee.top/Article/details/gtbzlnupjy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtrqhghnfu.html

[Q14] 存在则更新（upsert）
来源：http://dali.shangyingyoupin.top/Article/details/gtjtglaabw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ybcxt.top/Article/details/gtkgdeyzzy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gtxsgecwsq.html

[Q15] 查询全部
来源：http://dali.cashguo.top/Article/details/gtfabnhwkb.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtowesvfau.html

[Q16] 查询指定列
来源：http://dali.hysaishi.cn/Article/details/gtfqwxrxwn.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gteiduzxiy.html

[Q17] 条件查询
来源：http://dali.snrcjt.cn/Article/details/gtimaxtbon.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gtpznrpcag.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtnshvaynd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ehwqpu.com/Article/details/gtnqsfnsuj.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gtvodkttuh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gtcmgrwpim.html

[Q20] IN 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtgudzbzoi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gtmzdwfffu.html

[Q21] 空值判断
来源：http://dali.cucudq.cn/Article/details/gthyxratxj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gtlhheaflp.html

[Q22] 排序
来源：http://dali.redwolf501.top/Article/details/gtrjzacnzx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cashguo.top/Article/details/gtjkhovhhj.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gtpdqvlwjt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258888.top/Article/details/gtyjmrcvhq.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gtxcdwymfx.html

SELECT DISTINCT city FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtkcoyxfah.html

[Q25] 只取前 N 条
来源：http://dali.yanxiufei.cn/Article/details/gtnhzguyfw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gtafrolswz.html

[Q26] 计数
来源：http://dali.wangdashe.top/Article/details/gteqojerez.html

SELECT COUNT(*) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtmfujjwoq.html

[Q27] 条件计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcdahjhj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirsfcijc.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gtwhcoqxcj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtkslflpxg.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gttjdxpbzp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjswwljr.html

[Q30] 分组统计
来源：http://dali.xylfe.cn/Article/details/gtokbyebup.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtcxattgbk.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gtvcpztsyh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.havefunace.top/Article/details/gtoxlmdbmo.html

[Q32] 分组拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtuzoereiw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtdpnzqzuz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ydzc1.top/Article/details/gtvtfzsquh.html

[Q33] 多列分组
来源：http://dali.cdnleiting.top/Article/details/gtsirhxdzk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrpjgiyc.html

[Q34] 每组取第一条
来源：http://dali.jlsjyb.cn/Article/details/gtbaokryhg.html

SELECT * FROM (
来源：http://dali.sxryk.cn/Article/details/gtbrevujpa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.birdmap.top/Article/details/gtuehjuvfo.html

) t WHERE rn = 1;
来源：http://dali.yvedp.cn/Article/details/gtyyeoumun.html

[Q35] 内连接
来源：http://dali.nanxuanxn.top/Article/details/gteukilpqd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtlcsglibi.html

[Q36] 左连接
来源：http://dali.sweek.top/Article/details/gtswehuitq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtzmqozwcz.html

[Q37] 右连接
来源：http://dali.fzhhl.top/Article/details/gtadaaleih.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gaohongyu789.top/Article/details/gtscgqfqak.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gtlmnxysmy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gtqxxlikqn.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gtcjtudceo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gtsreqkhlg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvobtjrop.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gtirlusexg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gtnjxpipgx.html

[Q41] 多表连接
来源：http://dali.jqgufenzy.top/Article/details/gtvgmhwaku.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gtyigupwtu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gtxgcstizk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hysaishi.cn/Article/details/gtiyltcdua.html

[Q42] 连接条件附加过滤
来源：http://dali.shzxlz.cn/Article/details/gtgqwxbnep.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hammf.cn/Article/details/gtmptcceog.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtsttfbyuk.html

[Q43] 标量子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtxgpigxbj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gtyjslthuq.html

[Q44] IN 子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtqlniqpbw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gtbonsxpnr.html

[Q45] EXISTS 判断存在
来源：http://dali.cdnleiting.top/Article/details/gttqnurqqf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtukgtwydv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gtrixlksft.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gtzxzugoox.html

[Q47] 与平均值比较
来源：http://dali.tanke756.top/Article/details/gtkbtrgdwt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gtxnxnafkk.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigfzy.top/Article/details/gtbacikbqv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guannengcc.top/Article/details/gtmejqrtjp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gtyqrywaot.html

[Q49] 更新单行
来源：http://dali.hnqzz.top/Article/details/gtaiqysfhf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtaegpoodn.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gtctkxqziu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gtronifjuf.html

[Q51] 用子查询更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbyjnfvb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.svipenyu.cn/Article/details/gtnxmmtuwt.html

[Q52] 删除指定行
来源：http://dali.c1oappe.top/Article/details/gtocgamxty.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtkpggskqv.html

[Q53] 按条件删除
来源：http://dali.chenzaomai.com/Article/details/gtcrzzmqip.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ppjwa.cn/Article/details/gtvsluigfj.html

[Q54] 清空表
来源：http://dali.9152youxi.cn/Article/details/gtocjqervc.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gtdyfvgsin.html

[Q55] 排名（并列占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtoebysuwu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gtyphqlnzr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxupqdju.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gtiftizjem.html

[Q57] 行号
来源：http://dali.zdqjudy.top/Article/details/gtxfivmntg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gthbeywqgj.html

[Q58] 累计求和
来源：http://dali.birdmap.top/Article/details/gtnbdprkun.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gtssngauhz.html

[Q59] 分组内累计
来源：http://dali.hammf.cn/Article/details/gtylbvsjkx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtrodsogvb.html

[Q60] 取上一行 / 下一行
来源：http://dali.guowangkeji.top/Article/details/gtmwivqpqh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjwsqvlv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtzvkjtmjm.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gtimwaxniq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtsltdrtqr.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gtvtnmksgu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtgqdbmmrc.html

[Q63] 开启事务
来源：http://dali.shzxlz.cn/Article/details/gtxnoshuvw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gtuqrkeiva.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gtczlhdcvc.html

COMMIT;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkygykehp.html

[Q65] 回滚事务
来源：http://dali.hnqzz.top/Article/details/gtwswuhowy.html

ROLLBACK;
来源：http://dali.xuetiantiany.cn/Article/details/gtcwnwesky.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gtudiohrst.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jianghu66.top/Article/details/gtxuhsyotv.html

[Q67] 设置隔离级别
来源：http://dali.hongshengwenyu.top/Article/details/gtrmiweqhr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hywenlv.cn/Article/details/gtdmhyvigk.html

[Q68] 保存点
来源：http://dali.andypj.xyz/Article/details/gthxkyqdvr.html

SAVEPOINT sp1;
来源：http://dali.xuanzx.com/Article/details/gtiyhoubgd.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gtvroknwpl.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gtmtbrqybw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gtteplrhvt.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gtzjluwgam.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gtiuuddjdw.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gtoqnovoir.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gtrpmmlure.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gtwxfjtpkw.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtdxtlojng.html

[Q73] 查看表状态
来源：http://dali.vqdsnc.cn/Article/details/gtpuwpxext.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gtwsixbndf.html

[Q74] 强制使用索引
来源：http://dali.tanke756.top/Article/details/gtuneqauih.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gtighoauoa.html

[Q75] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtjvqzifqn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtqjmdcoxd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fzhhl.top/Article/details/gthsageugd.html

[Q76] 按天统计
来源：http://dali.yuanzhike.top/Article/details/gtudlkrxog.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtywrrqazm.html

[Q77] 时间加减
来源：http://dali.sweek.top/Article/details/gtyyzrszwo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gttwxaapcc.html

[Q78] 当前时间
来源：http://dali.zhengqikj.top/Article/details/gturjurmxa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gtwjuzbqac.html

[Q79] 字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gttrfmgkjz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gtxpwnqwkz.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gtwqazpjsx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtvozyohoy.html

[Q81] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtzcqajmus.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cheryme.top/Article/details/gtxxiaavwa.html

[Q82] 字符长度与字节长度
来源：http://dali.chenlongwang.top/Article/details/gtommuqtkc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzbcqpvr.html

[Q83] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtkusalshg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtuzmrsopm.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gtvqynqngx.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtbplqooes.html

[Q85] 数值取整
来源：http://dali.jqgfzy.top/Article/details/gtwxatxyer.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hfpthk.cn/Article/details/gtvmmhunux.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gtrqgkluov.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhoulong.xyz/Article/details/gtqctrzphr.html

[Q87] JSON 字段做条件
来源：http://dali.gotoacloud.top/Article/details/gtcwtrpgfq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.kuanghao11.cn/Article/details/gthukwciyi.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gtvlhsktqy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gthyjejzgu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtaingedoa.html

[Q89] 判断表是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtchpagran.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gtpagsowtc.html

[Q90] 生成序号列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopjomjmm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gtyarmtjdf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtgfdmyokp.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtyqhguhyi.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxaqlkhw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gtyqxhjxwm.html

#!/usr/bin/env bash
来源：http://dali.gogol.net.cn/Article/details/gtwwyiupbr.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gtkpkokdbq.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gtqfjmuqqf.html

name="Tom"; echo "$name"
来源：http://dali.shuidangran.top/Article/details/gtmzmygvln.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gtfndvyytr.html


<!-- 参考信息 -->