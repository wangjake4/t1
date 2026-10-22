代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gt2kqypzswp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cqqwz.cn/Article/details/gt2kyosnsfo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jianghu66.top/Article/details/gt2macqulko.html

Ruby: // fork 块
来源：http://dali.xylfe.cn/Article/details/gt2qkzmomyy.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gt2dgwurzvd.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2pzlhdttt.html

P. 常用工具函数
来源：http://dali.nanxuanxn.top/Article/details/gt2xpmbdvhw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2votfetjv.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gt2uucnztlx.html

Py:   str(uuid.uuid4())
来源：http://dali.ydzc1.top/Article/details/gt2skmdzvck.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2wrbtojpv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgmnpyl.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gt2mpozrxqz.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gt2oinaqzjt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gt2obcssuio.html

Ruby: SecureRandom.uuid
来源：http://dali.dianchejie.cn/Article/details/gt2nsxsmyzc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gt2fmjtwhlh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yonumen.top/Article/details/gt2ggnrwshw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gt2iboynqmv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xylfe.cn/Article/details/gt2wpddcyhv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sufxvd.cn/Article/details/gt2fqbelpyc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.smart0.xyz/Article/details/gt2bjpbcgou.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gt2qtrsolfu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gt2tzluuhgq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gt2usoyonnq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.meibo888.top/Article/details/gt2vllqhpau.html

[P03] 生成短随机字符串
来源：http://dali.ybcxt.top/Article/details/gt2azfibief.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gt2bcwgieix.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gt2pktebhky.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gt2uywnjksk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gt2bhkmdsmq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258.top/Article/details/gt2blsiowcj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hammf.cn/Article/details/gt2pjqrzzkm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gt2nbqufhlg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhoulong.xyz/Article/details/gt2dopkvtwj.html

[P04] 求长度
来源：http://dali.ivvv.top/Article/details/gt2pxrkqmdw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.andypj.xyz/Article/details/gt2sgpxvvqn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2wtxxxfwg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gt2rcptvbti.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gt2qsesihko.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aibaodan.cn/Article/details/gt2wdiumbbw.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gt2kjpjvuya.html

Ruby: x.length;  x.size
来源：http://dali.yj20258888.top/Article/details/gt2rjnocfpz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guowangkeji.top/Article/details/gt2annwahvk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aibaodan.cn/Article/details/gt2rdrixsvm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuetiantiany.cn/Article/details/gt2giqkrybx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhengqikj.top/Article/details/gt2htyubyts.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tian-w.cn/Article/details/gt2bjbejedc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gt2ojofjhit.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xylfe.cn/Article/details/gt2lhhlofkc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gt2wwfiptqh.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gt2ubceqomc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ppjwa.cn/Article/details/gt2gdsnvwua.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vpxxgaea.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hywenlv.cn/Article/details/gt2mecxaygr.html

PHP:  if (empty($x)) {}
来源：http://dali.guowangkeji.top/Article/details/gt2nsvkakhf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gt2gswhefzq.html

TS:   if (x == null) {}
来源：http://dali.haohaochexian.top/Article/details/gt2oxishwob.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gt2alwzxzly.html

Go:   if x == nil {}
来源：http://dali.iojbl.cn/Article/details/gt2unnbayob.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj202588.top/Article/details/gt2utcozvna.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gt2duryzpwe.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gt2flxyowim.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhoulong.xyz/Article/details/gt2xmpiohit.html

PHP:  // 手写时间戳比较
来源：http://dali.yuxming.cn/Article/details/gt2talivelf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gt2bhsmnopq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gt2lbcgphqh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gt2chlksowf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hywenlv.cn/Article/details/gt2xenicoij.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqhubolb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqkqpoli.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gt2okufnxzy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxuanxn.top/Article/details/gt2kumchmpg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ppjwa.cn/Article/details/gt2qlmcysrv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangdashe.top/Article/details/gt2letkbsdq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gt2ggeywmgn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gt2fgexwvzy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gt2qeavpdvq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gt2ihkcmxmh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhoulong.xyz/Article/details/gt2jdriadka.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ajqfxiji.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zdqjudy.top/Article/details/gt2qaourlnf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2wwmpnptf.html

[Q01] 创建表
来源：http://dali.hammf.cn/Article/details/gt2hyuywyzh.html

CREATE TABLE users (
来源：http://dali.cqqwz.cn/Article/details/gt2hzcpvyfi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gt2eaxqzmpa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gt2aynkdfan.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gt2oesxmntf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gt2zxmmwugv.html

);
来源：http://dali.tian-w.cn/Article/details/gt2vafulcqk.html

[Q02] 创建带外键的表
来源：http://dali.yanxiufei.cn/Article/details/gt2btooaurk.html

CREATE TABLE orders (
来源：http://dali.yj202588.top/Article/details/gt2kufvjqqb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gt2lrzxuzav.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gt2yicsjank.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2nczbznmz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gotoacloud.top/Article/details/gt2gjwqdguv.html

);
来源：http://dali.yangfankeji.com/Article/details/gt2qnigvfkz.html

[Q03] 增加列
来源：http://dali.iojbl.cn/Article/details/gt2fvqjjjwc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gt2tepxydsp.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gt2ffsirklw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangdashe.top/Article/details/gt2nhjpacwg.html

[Q05] 重命名列
来源：http://dali.c1oappe.top/Article/details/gt2bnfiisza.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hysaishi.cn/Article/details/gt2vttffmfh.html

[Q06] 删除列
来源：http://dali.gotoacloud.top/Article/details/gt2dhrlvlwo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.svipenyu.cn/Article/details/gt2ekmhpgbk.html

[Q07] 删除表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kiajctjl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2scozzgux.html

[Q08] 创建普通索引
来源：http://dali.hfpthk.cn/Article/details/gt2srjzlkss.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gt2vauahhnd.html

[Q09] 创建唯一索引
来源：http://dali.jyoumei.cn/Article/details/gt2kfurlhic.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gt2iyefzwsb.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gt2dgfbvzgf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2ufvjxwwk.html

[Q11] 一次插入多行
来源：http://dali.cdnleiting.top/Article/details/gt2jcziaiiv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gt2xvolnhgg.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gt2kzqlmajb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.316326.xyz/Article/details/gt2mwsqjelp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gt2hntwhttp.html

[Q13] 忽略重复插入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wniletbg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gt2jgntxsjb.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gt2ucxktjfk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shangyingyoupin.top/Article/details/gt2vraakjsq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daxiang520.top/Article/details/gt2ouvpoatz.html

[Q15] 查询全部
来源：http://dali.sufxvd.cn/Article/details/gt2ecghnhyw.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2onkszqie.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gt2kfvpfzhk.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2umkiddky.html

[Q17] 条件查询
来源：http://dali.cqqwz.cn/Article/details/gt2xioqbbun.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2btmerkts.html

[Q18] 模糊匹配
来源：http://dali.yongpay.top/Article/details/gt2lcgsbxjj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhengqikj.top/Article/details/gt2ylbwpect.html

[Q19] 范围查询
来源：http://dali.zhongyouzk.top/Article/details/gt2lgpxsdft.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gt2rohmhdgu.html

[Q20] IN 列表
来源：http://dali.zycfv.cn/Article/details/gt2zfbdtjuw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2goaaedii.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gt2doloojha.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shuidangran.top/Article/details/gt2zptvmrcl.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gt2dilemohr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gt2tjmvqqxw.html

[Q23] 分页
来源：http://dali.zycfv.cn/Article/details/gt2onhygpmr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gt2acykjnmk.html

[Q24] 去重
来源：http://dali.zdqjudy.top/Article/details/gt2ernbmlpm.html

SELECT DISTINCT city FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2sujleyyc.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wyqqhwll.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgfzy.top/Article/details/gt2drgarlqf.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gt2bdlgvnbo.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmptfwnw.html

[Q27] 条件计数
来源：http://dali.ehwqpu.com/Article/details/gt2luoegkjv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gt2jfedojwc.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntvmzhrq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2rtkhwaad.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gt2lhmbgdrq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2oqlfxlyg.html

[Q30] 分组统计
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxyvedzw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gt2zaufreke.html

[Q31] 分组后过滤
来源：http://dali.meibo888.top/Article/details/gt2fvmvreoj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hammf.cn/Article/details/gt2sqmcqhtk.html

[Q32] 分组拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gt2dgtjywyb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmumhuhj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gt2eryftyij.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gt2cuaxfwal.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gt2xvlhkxqj.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gt2rfsdmxvd.html

SELECT * FROM (
来源：http://dali.nanxuanxn.top/Article/details/gt2btkjtsjr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.9152youxi.cn/Article/details/gt2kniwjtcg.html

) t WHERE rn = 1;
来源：http://dali.ivvv.top/Article/details/gt2pqvpmxhj.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gt2cfnbpuvo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gt2zmuwzrdj.html

[Q36] 左连接
来源：http://dali.zhoulong.xyz/Article/details/gt2weodqceu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gt2sdqmkyra.html

[Q37] 右连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzjkrkvf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gzhubu.top/Article/details/gt2jgtcgcbs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuanzhike.top/Article/details/gt2sxvvrnoh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ofuebvjg.html

[Q39] 自连接（查上下级）
来源：http://dali.svipenyu.cn/Article/details/gt2keadasxi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gt2bczzydcq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gt2mzxtnbej.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gt2ntpsfjgb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ivvv.top/Article/details/gt2abqkbbxi.html

[Q41] 多表连接
来源：http://dali.snrcjt.cn/Article/details/gt2xiymvwol.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nwbrower.top/Article/details/gt2pwkbfzme.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khkcpoia.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxlbvjr.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gt2rwaifsmf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yangfankeji.com/Article/details/gt2jqrjqktg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gt2oyroxnct.html

[Q43] 标量子查询
来源：http://dali.pycfn.com/Article/details/gt2uzoxikmo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.316326.xyz/Article/details/gt2mibccazp.html

[Q44] IN 子查询
来源：http://dali.hammf.cn/Article/details/gt2fbywgngx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.c1oappe.top/Article/details/gt2elasxevd.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gt2stctfwgu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gt2jsnvkany.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxpfckuj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gt2bwwqjddx.html

[Q47] 与平均值比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruakryvq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmwfltva.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gt2jjarldzh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gt2cnzeghmt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guowangkeji.top/Article/details/gt2obdegygv.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gt2ecmbrtgw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2krerslhz.html

[Q50] 批量更新
来源：http://dali.gogol.net.cn/Article/details/gt2zzywpdae.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gt2swytnxye.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gt2culixtuq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2ubdbykou.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gt2eiyzcird.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2nxbbfxhb.html

[Q53] 按条件删除
来源：http://dali.meibo888.top/Article/details/gt2amvhqeny.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnqzz.top/Article/details/gt2titcjpbt.html

[Q54] 清空表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vufkoies.html

TRUNCATE TABLE logs;
来源：http://dali.guannengcc.top/Article/details/gt2yznthxox.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gt2pboeyyzk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gt2jnsdpuua.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xinyue.icu/Article/details/gt2aksmfnti.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tian-w.cn/Article/details/gt2lsvgwuoe.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gt2zljetifa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqvxdiyx.html

[Q58] 累计求和
来源：http://dali.yvedp.cn/Article/details/gt2ocixyvpf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2prgooaut.html

[Q59] 分组内累计
来源：http://dali.yuxming.cn/Article/details/gt2tqcrrxvm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wcgorvva.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gt2duastpkj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gt2jedwvewl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2wxbxdqdw.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gt2aizcyoxn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2hetprhti.html

[Q62] 分组占比
来源：http://dali.yuxming.cn/Article/details/gt2hohhwsen.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2ydnoigye.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gt2shkslwty.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xylfe.cn/Article/details/gt2tlfryqob.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gt2rouyfenf.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gt2ibnkrfng.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gt2srepnlrs.html

ROLLBACK;
来源：http://dali.shuidangran.top/Article/details/gt2giyuambf.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gt2jntruivp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gt2ehvgvgfu.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gt2gtfkfnvq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gt2wsipovzy.html

[Q68] 保存点
来源：http://dali.hnqzz.top/Article/details/gt2gplmgzwz.html

SAVEPOINT sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2snretynq.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gt2vwieehwl.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gt2coxluvog.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gotoacloud.top/Article/details/gt2uubddrku.html

[Q70] 更新统计信息
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugbetrnu.html

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gt2rkrqdxbv.html

[Q71] 查看建表语句
来源：http://dali.jinqigufen.top/Article/details/gt2yzklajic.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yongpay.top/Article/details/gt2pfwtopew.html

[Q72] 查看索引
来源：http://dali.tian-w.cn/Article/details/gt2fonfkvsz.html

SHOW INDEX FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2luutxnkk.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gt2rivomfsk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fengsongda.top/Article/details/gt2lpcwnesh.html

[Q74] 强制使用索引
来源：http://dali.zhixingplan.top/Article/details/gt2guiqczzh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2quwabnxu.html

[Q75] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2nliyoltt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2khomrkpk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gt2edzmaqae.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gt2hcounbch.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gt2lgfaprfp.html

[Q77] 时间加减
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfwxykwx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gt2eawkgsob.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgcnkmua.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gt2otvdfzzx.html

[Q79] 字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gt2suotzlgt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gt2ysuytwkm.html

[Q80] 字符串截取
来源：http://dali.jqgufenzy.top/Article/details/gt2drpwijrn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2ktctwlav.html

[Q81] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gt2phubonfb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gt2slhyvhqa.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opwmzdvc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2zcazloug.html

[Q83] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gt2njapdaax.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2qlvorqez.html

[Q84] 去除首尾空格
来源：http://dali.iojbl.cn/Article/details/gt2duwxtsxt.html

SELECT TRIM(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nafikfff.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gt2qfzytvvl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.316326.xyz/Article/details/gt2rymejbpl.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gt2hpbztmol.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gt2gsgcjkvt.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gt2mndxaqgg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gt2jtdvslmm.html

[Q88] 行转列（条件聚合）
来源：http://dali.cucudq.cn/Article/details/gt2zjrzhqik.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gt2acxkcvxh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2frlnyqzf.html

[Q89] 判断表是否存在
来源：http://dali.yj20258888.top/Article/details/gt2wnesusih.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gt2gyjgmqwx.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gt2qxfeycbh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ycdgconn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2uvuguoih.html

R. Bash 专题
来源：http://dali.kuanghao11.cn/Article/details/gt2ctolcwyz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2teigltxf.html

[R01] shebang 与严格模式
来源：http://dali.xziqi.cn/Article/details/gt2hgkyhzrv.html

#!/usr/bin/env bash
来源：http://dali.xinyue.icu/Article/details/gt2jivnkbvl.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gt2icdrkbwp.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gt2tzuaayds.html

name="Tom"; echo "$name"
来源：http://dali.tanke756.top/Article/details/gt2pfpxspyd.html

[R03] 只读变量
来源：http://dali.kuanghao11.cn/Article/details/gt2hjddtwjt.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gt2gwancger.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gt2bamkarqp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shzxlz.cn/Article/details/gt2mvhjsikm.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gt2ehimujms.html


<!-- 参考信息 -->