代发 wailian999

[O06] 使用进程池
来源：http://dali.zhixingplan.top/Article/details/gt2ogeowpjp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gt2thnuvqtd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cdnleiting.top/Article/details/gt2mzozaqod.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gt2dmbpltbi.html

TS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gt2vqxlwalw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gt2vuaprcpv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.svipenyu.cn/Article/details/gt2intmocrq.html

Ruby: // fork 块
来源：http://dali.pycfn.com/Article/details/gt2qomoiojp.html

C#:   Parallel.For
来源：http://dali.xinyue.icu/Article/details/gt2nbyxwiwv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2dnsgjxlz.html

P. 常用工具函数
来源：http://dali.cheryme.top/Article/details/gt2clooofur.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2kqluhdhy.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gt2bakhgpii.html

Py:   str(uuid.uuid4())
来源：http://dali.shangyingyoupin.top/Article/details/gt2kcthnxpe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gt2vwnxxdao.html

JS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gt2ssajvuue.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2jyerlwch.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnqzz.top/Article/details/gt2cbxuwvpt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gt2zybblqsz.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gt2poookfwr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gt2ywufqziy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdilmtxx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuetiantiany.cn/Article/details/gt2knbjbpeg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shuidangran.top/Article/details/gt2ahpkxmbw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smzbpkxe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrlogesb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgfzy.top/Article/details/gt2alenpcze.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cqqwz.cn/Article/details/gt2zpogfzrq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gt2qikaocsa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sweek.top/Article/details/gt2ufyxrmlk.html

[P03] 生成短随机字符串
来源：http://dali.meibo888.top/Article/details/gt2avcqtrzg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gt2cpdqbgtf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gt2swtupvxc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nlgrzoak.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gt2vvvadjan.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gt2mbucuzvh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ydzc1.top/Article/details/gt2vhntbilw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gt2pbwgzapm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gt2tnpdjens.html

[P04] 求长度
来源：http://dali.hysaishi.cn/Article/details/gt2llkpspsl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jiagoushi.top/Article/details/gt2nndpkemo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwldctiv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2irxqhrqq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gt2hsdatpcx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nwbrower.top/Article/details/gt2osmlszvz.html

Go:   len(arr);  len(m)
来源：http://dali.316326.xyz/Article/details/gt2mxzcztie.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gt2yftvzixr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.svipenyu.cn/Article/details/gt2hhwnkxyo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gt2vjayxlju.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gt2peuittdt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guannengcc.top/Article/details/gt2nmnwynvo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.svipenyu.cn/Article/details/gt2uqukhsgk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cheryme.top/Article/details/gt2sqzrbvnc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj202588.top/Article/details/gt2lmdyhvnr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2plecryiw.html

Ruby: a == b
来源：http://dali.gaohongyu789.top/Article/details/gt2fbszkliw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gogol.net.cn/Article/details/gt2gphpjszz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dashuyun.cn/Article/details/gt2qxzehrxg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gt2giphcvdt.html

PHP:  if (empty($x)) {}
来源：http://dali.mhx1999.top/Article/details/gt2nwhlvhzb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhongyouzk.top/Article/details/gt2ccnunjrf.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gt2jrrashxk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gt2rgdwdwxg.html

Go:   if x == nil {}
来源：http://dali.ybcxt.top/Article/details/gt2xtrhnzck.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yangfankeji.com/Article/details/gt2xpehyurh.html

C#:   if (x is null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivxlajrq.html

[P07] 防抖与节流
来源：http://dali.daxiang520.top/Article/details/gt2rabgeysm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigufen.top/Article/details/gt2oycctdts.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gt2yyyctgea.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2oaawqzrz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gt2yykjbrsa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aizwys.cn/Article/details/gt2drcuaeru.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhxzifzy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gt2mrtcxyrd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuxming.cn/Article/details/gt2hmxngywp.html

[P08] 处理浮点精度问题
来源：http://dali.redwolf501.top/Article/details/gt2wmzvxuoi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuanzx.com/Article/details/gt2hpkpmlcv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hfpthk.cn/Article/details/gt2qzbnseaw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gt2tmkvspyh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gt2sugpwlhl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fzhhl.top/Article/details/gt2vkxdaemh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ivvv.top/Article/details/gt2wbasafck.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cdnleiting.top/Article/details/gt2weoxoqel.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hysaishi.cn/Article/details/gt2zbjqthlz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2eadvenaz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gt2xnvytoaw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2irhekvao.html

[Q01] 创建表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtjekhrq.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gt2twndrqvu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gt2sqcsjjdp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gt2bibatnzi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gt2jmzivczm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gotoacloud.top/Article/details/gt2qedijpzw.html

);
来源：http://dali.nwbrower.top/Article/details/gt2fyukijqp.html

[Q02] 创建带外键的表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvgfghgi.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gt2txweulgb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gt2pgeuozgj.html

user_id INT NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gt2tbrrorci.html

amount DECIMAL(10, 2),
来源：http://dali.iojbl.cn/Article/details/gt2aycrdscs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvclnudd.html

);
来源：http://dali.sufxvd.cn/Article/details/gt2rtoyupzm.html

[Q03] 增加列
来源：http://dali.shangyingyoupin.top/Article/details/gt2llodwdvn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gt2hjyjlftr.html

[Q04] 修改列类型
来源：http://dali.zhengqikj.top/Article/details/gt2fusliuxu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gt2sogcajtv.html

[Q05] 重命名列
来源：http://dali.gogol.net.cn/Article/details/gt2lefkemho.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2erxobxrl.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gt2kzfnpjoa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdrlsxqu.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gt2vgmbqebo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gt2nrbmeibd.html

[Q08] 创建普通索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uegdghjz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gt2hscmmwit.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gt2ggpzufaz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gt2hyggizsc.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gt2nhhjlmzd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gt2cgblhaxo.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gt2gcjibadp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xinyue.icu/Article/details/gt2ypwmdibr.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgfzy.top/Article/details/gt2wdgurkqy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2daztsnnb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.andypj.xyz/Article/details/gt2nvdtyxhh.html

[Q13] 忽略重复插入
来源：http://dali.cdnleiting.top/Article/details/gt2cbxmiimk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gt2ersdeefo.html

[Q14] 存在则更新（upsert）
来源：http://dali.vqdsnc.cn/Article/details/gt2hduagduh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xylfe.cn/Article/details/gt2biennagc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dashuyun.cn/Article/details/gt2szislgxh.html

[Q15] 查询全部
来源：http://dali.xylfe.cn/Article/details/gt2yxeqmmmg.html

SELECT * FROM users;
来源：http://dali.birdmap.top/Article/details/gt2zrtoxlfv.html

[Q16] 查询指定列
来源：http://dali.zycfv.cn/Article/details/gt2yxzwradv.html

SELECT id, name FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2iyxdgaks.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gt2vxutvyel.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sxryk.cn/Article/details/gt2vwobytls.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2efqwcetn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gt2nyjxxdml.html

[Q19] 范围查询
来源：http://dali.shuidangran.top/Article/details/gt2wchdcjxc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.havefunace.top/Article/details/gt2xvcuigim.html

[Q20] IN 列表
来源：http://dali.tianlin.xyz/Article/details/gt2hgvrvzez.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gt2vxhjembd.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gt2vvscksgp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.snrcjt.cn/Article/details/gt2flcycktt.html

[Q22] 排序
来源：http://dali.gzhubu.top/Article/details/gt2swbyivfq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gt2zjutqwyx.html

[Q23] 分页
来源：http://dali.cashguo.top/Article/details/gt2pokqxvuc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xziqi.cn/Article/details/gt2nnqgufrv.html

[Q24] 去重
来源：http://dali.zhoulong.xyz/Article/details/gt2ldabihys.html

SELECT DISTINCT city FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2bqhmyzdf.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gt2vnjrvpft.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxuanxn.top/Article/details/gt2tfpgyuvt.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gt2huqsuthh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czulgogb.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gt2hbgjdteo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2fxeqbhjz.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oibqllzb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2tfdtznho.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gt2kockvvxq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2gvzgeqhj.html

[Q30] 分组统计
来源：http://dali.chenzaomai.com/Article/details/gt2shflzwyu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2yxmmlint.html

[Q31] 分组后过滤
来源：http://dali.zhixingplan.top/Article/details/gt2rinehhnb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2fykhizox.html

[Q32] 分组拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gt2xclslqpw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gt2mlrzgqye.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdglejbq.html

[Q33] 多列分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drwkctve.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xylfe.cn/Article/details/gt2ukireauq.html

[Q34] 每组取第一条
来源：http://dali.zhengqikj.top/Article/details/gt2tqakqzxn.html

SELECT * FROM (
来源：http://dali.nanxinkj.top/Article/details/gt2dsiuynyo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gt2rxeyiekm.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2xpsbkwfz.html

[Q35] 内连接
来源：http://dali.jyoumei.cn/Article/details/gt2krbntpwn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gt2kqicpaux.html

[Q36] 左连接
来源：http://dali.hnxiangtu.top/Article/details/gt2uqjrrscy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxqoiimg.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gt2lhbfxbvm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbnlcljp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.andypj.xyz/Article/details/gt2fakccojs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ivvv.top/Article/details/gt2fqvuageq.html

[Q39] 自连接（查上下级）
来源：http://dali.iojbl.cn/Article/details/gt2pthgrzcg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xinyue.icu/Article/details/gt2oekquvgb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gotoacloud.top/Article/details/gt2adjlowjd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guowangkeji.top/Article/details/gt2fnajgvmr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gt2ptitvyoe.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gt2idwijncp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gaohongyu789.top/Article/details/gt2hptppgjl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenlongwang.top/Article/details/gt2utgpvjxu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gt2dzmbgrmd.html

[Q42] 连接条件附加过滤
来源：http://dali.yuxming.cn/Article/details/gt2qjjigppv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cashguo.top/Article/details/gt2psoggxqk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gt2emxmbczh.html

[Q43] 标量子查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybtgopkm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuanzx.com/Article/details/gt2khmzdvei.html

[Q44] IN 子查询
来源：http://dali.zhengqikj.top/Article/details/gt2eachjqfd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gt2cjrsuqtg.html

[Q45] EXISTS 判断存在
来源：http://dali.quarkkingdee.top/Article/details/gt2mzabuqdt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gt2mpptpxre.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yangfankeji.com/Article/details/gt2mjoesgvd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gt2pkfmohoa.html

[Q47] 与平均值比较
来源：http://dali.yuanzhike.top/Article/details/gt2uwcoegdb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dianchejie.cn/Article/details/gt2mntdzvdh.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gt2abxspsnn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fengsongda.top/Article/details/gt2pdqqrdkt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangdashe.top/Article/details/gt2fuetrxpz.html

[Q49] 更新单行
来源：http://dali.yuxming.cn/Article/details/gt2zzuhwhzi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gt2sllzvzmo.html

[Q50] 批量更新
来源：http://dali.jlsjyb.cn/Article/details/gt2rcruvazc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gt2kskzqxyk.html

[Q51] 用子查询更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2omffynka.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2cszxplgs.html

[Q52] 删除指定行
来源：http://dali.ivvv.top/Article/details/gt2nnombisd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gt2oszpjbet.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gt2roralxnl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gt2unktcdqs.html

[Q54] 清空表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgxtghdf.html

TRUNCATE TABLE logs;
来源：http://dali.0kj1m.cn/Article/details/gt2dypczygl.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gt2lzssahix.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gt2axfvqstd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhiwuduotai.top/Article/details/gt2oagirdat.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gt2pgytolhf.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gt2chvakxhj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2krhdvjtd.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gt2nidewuja.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2wpxpmots.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gt2ogeblcgm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdymdomo.html

[Q60] 取上一行 / 下一行
来源：http://dali.ehwqpu.com/Article/details/gt2tdaedmui.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irlbkbqr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2mptxzhgo.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpjdrfer.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2izoztikq.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gt2gtqurint.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gt2msckyohm.html

[Q63] 开启事务
来源：http://dali.nwbrower.top/Article/details/gt2tehemjrs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gt2tkhchxbt.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gt2ojuzaxaw.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gt2auitqxdg.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gt2wevkhjfd.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gt2lfzdxfxn.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gt2rpxzvyma.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gt2ogeszzpo.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gt2wimddzot.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gzhubu.top/Article/details/gt2hdjsrygw.html

[Q68] 保存点
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtvsdgnk.html

SAVEPOINT sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpkhuldi.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gt2lwfkwjgu.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gt2ssoouvkx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gt2yyujigft.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gt2rrfhmahv.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2duntourl.html

[Q71] 查看建表语句
来源：http://dali.jinqigufen.top/Article/details/gt2ixvcnsyp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gt2dwomqhkk.html

[Q72] 查看索引
来源：http://dali.snrcjt.cn/Article/details/gt2wcquwejg.html

SHOW INDEX FROM users;
来源：http://dali.pycfn.com/Article/details/gt2yqbbacht.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gt2klmwabae.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cashguo.top/Article/details/gt2nxwbprmj.html

[Q74] 强制使用索引
来源：http://dali.yangfankeji.com/Article/details/gt2brxzebpk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hywenlv.cn/Article/details/gt2xyolzxzp.html

[Q75] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gt2jgdvrtzi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2jfqyhfey.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hfpthk.cn/Article/details/gt2pidpslwm.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gt2zdqlviad.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xinyue.icu/Article/details/gt2odmydjdi.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gt2ouhbikgt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mehzeuhv.html

[Q78] 当前时间
来源：http://dali.smart0.xyz/Article/details/gt2pcfvtjka.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gt2rpicmoii.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gt2njntoxyw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gt2btyiedri.html

[Q80] 字符串截取
来源：http://dali.chenjidiqi.icu/Article/details/gt2kdywfkiz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2njqwmkrt.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gt2nmcmtken.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsmuhcgq.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gt2kmenipbb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dkjrvfzw.html

[Q83] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gt2wxhvujmg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfeuxceh.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxvgshhm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2qbpxbasl.html

[Q85] 数值取整
来源：http://dali.shangyingyoupin.top/Article/details/gt2vysqshze.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gt2gscgtyxp.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gt2lngzdnvd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nwbrower.top/Article/details/gt2lrnnwrmy.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gt2rrojwptq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xziqi.cn/Article/details/gt2iioiuxzx.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gt2jkeqmheq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2opebsnrr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnikhgil.html

[Q89] 判断表是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2jfsrjtxm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gt2dyltmtxo.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kboqpsnq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.iojbl.cn/Article/details/gt2wvvkddgd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2yfeqtjvf.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2inlvfwuj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2yriplfij.html

[R01] shebang 与严格模式
来源：http://dali.dashuyun.cn/Article/details/gt2ypzvzild.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gt2twlkzfnt.html

set -euo pipefail
来源：http://dali.zhengqikj.top/Article/details/gt2mjtcfetw.html

[R02] 变量赋值与使用
来源：http://dali.zhongyouzk.top/Article/details/gt2qnqxviov.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gt2ajzhkvwd.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcmznsya.html


<!-- 参考信息 -->