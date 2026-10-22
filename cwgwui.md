代发 wailian999

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gt2fkaqxcgz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dianchejie.cn/Article/details/gt2fqotyqup.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gt2taydbygz.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gt2ustnxqgj.html

TS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gt2harevwgg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gt2ckzvplaq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2meinacgg.html

Ruby: // fork 块
来源：http://dali.yvedp.cn/Article/details/gt2nhhfevng.html

C#:   Parallel.For
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlbxfmde.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2fqpbbuux.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gt2gmoylkra.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2smsfakdl.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gt2zpynjiud.html

Py:   str(uuid.uuid4())
来源：http://dali.xziqi.cn/Article/details/gt2jngcrjqd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhongyouzk.top/Article/details/gt2ihkyzorx.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2levunqzh.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2qfgfnces.html

Java: UUID.randomUUID().toString()
来源：http://dali.ppjwa.cn/Article/details/gt2owbxgqvm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sufxvd.cn/Article/details/gt2wivtnuek.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gt2jcbbtozg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cdnleiting.top/Article/details/gt2jnyjkovw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.quarkkingdee.top/Article/details/gt2ygzglume.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gt2mofydszy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgfzy.top/Article/details/gt2jakentva.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gt2gxhvhhyu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daria6918.cn/Article/details/gt2xnaillkm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gzhubu.top/Article/details/gt2yqwomzbk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aizwys.cn/Article/details/gt2giaxiitc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.redwolf501.top/Article/details/gt2agjnskia.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gt2igltshrd.html

[P03] 生成短随机字符串
来源：http://dali.hnqzz.top/Article/details/gt2sxorpdyt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wewkiyvs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.snrcjt.cn/Article/details/gt2qjintuaw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gt2ptcojisu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gt2dfofidvj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.9152youxi.cn/Article/details/gt2fxinffkk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuanzhike.top/Article/details/gt2fywkqrbr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hfpthk.cn/Article/details/gt2lksxnxcz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.feifeiyinyue.top/Article/details/gt2rrqdahym.html

[P04] 求长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfflohze.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigfzy.top/Article/details/gt2ygspghit.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2trxizamd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjtukwkh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gt2ytzlrske.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gt2dlmtwfhx.html

Go:   len(arr);  len(m)
来源：http://dali.ehwqpu.com/Article/details/gt2bbkkuyzb.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gt2bllnsvag.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gt2shomswxq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gt2zfgaunpf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gt2dckaozdl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuetiantiany.cn/Article/details/gt2bgdzrbin.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.iojbl.cn/Article/details/gt2kevdunhy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epbufvfx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yonumen.top/Article/details/gt2doohcbpa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fengsongda.top/Article/details/gt2fanjszhw.html

Ruby: a == b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozuskkth.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gt2ebtesgzr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangshuangyany.cn/Article/details/gt2khaupbzm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gt2cqkwkelb.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2llwjjunh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gt2oelgcvik.html

TS:   if (x == null) {}
来源：http://dali.bjfxy.top/Article/details/gt2tsjsuhbp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gt2dsndooqw.html

Go:   if x == nil {}
来源：http://dali.316326.xyz/Article/details/gt2figxpsoh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.feifeiyinyue.top/Article/details/gt2surezoyz.html

C#:   if (x is null) {}
来源：http://dali.xziqi.cn/Article/details/gt2ooifhblp.html

[P07] 防抖与节流
来源：http://dali.daxiang520.top/Article/details/gt2ciktuqzt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.meibo888.top/Article/details/gt2pfoapsut.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gt2mjdcevxy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gt2pshqfiqb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gt2fluweffx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gt2diwaaend.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hammf.cn/Article/details/gt2mtgqpyey.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hammf.cn/Article/details/gt2ymcgkqdn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ycfskoxl.html

[P08] 处理浮点精度问题
来源：http://dali.xylfe.cn/Article/details/gt2nabvtdmp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gt2mnzpnyyt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xylfe.cn/Article/details/gt2anexpzow.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dianchejie.cn/Article/details/gt2xbvuxdis.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gt2clsucbxw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pengpengdd.cyou/Article/details/gt2hxgusetr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gt2pxoqpctv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cashguo.top/Article/details/gt2oaxmfmal.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gotoacloud.top/Article/details/gt2vuoqzqie.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2supcnvnl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangshuangyany.cn/Article/details/gt2rtdbawik.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2umjlerox.html

[Q01] 创建表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdpymxvb.html

CREATE TABLE users (
来源：http://dali.havefunace.top/Article/details/gt2csfdnaxu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gt2jeynqjwz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gt2qvjmhiul.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yonumen.top/Article/details/gt2pgiqosmw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yangfankeji.com/Article/details/gt2benytxpm.html

);
来源：http://dali.yj20258888.top/Article/details/gt2zefmuhgc.html

[Q02] 创建带外键的表
来源：http://dali.hnxiangtu.top/Article/details/gt2spnlawpt.html

CREATE TABLE orders (
来源：http://dali.yueranfly.top/Article/details/gt2zmitivsj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcxflpey.html

user_id INT NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gt2phqjrcpk.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gt2nbddncyg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hywenlv.cn/Article/details/gt2hhmqxygy.html

);
来源：http://dali.sufxvd.cn/Article/details/gt2pfoapwrd.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gt2waoilbhp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gneefjim.html

[Q04] 修改列类型
来源：http://dali.xylfe.cn/Article/details/gt2mikzispv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvomyqd.html

[Q05] 重命名列
来源：http://dali.tian-w.cn/Article/details/gt2helylubs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cqqwz.cn/Article/details/gt2hsndjdkr.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gt2emzlzbiy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twenbvhy.html

[Q07] 删除表
来源：http://dali.0kj1m.cn/Article/details/gt2huprigzq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj202588.top/Article/details/gt2mqnnenxv.html

[Q08] 创建普通索引
来源：http://dali.hammf.cn/Article/details/gt2fmcobshs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gt2tzyepxmp.html

[Q09] 创建唯一索引
来源：http://dali.jinqigufen.top/Article/details/gt2dxblfmwz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gt2tbbzrkbo.html

[Q10] 插入单行
来源：http://dali.xziqi.cn/Article/details/gt2zzyansss.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gt2aspofgak.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gt2syiawchy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gt2xkyhxuxc.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gt2hwidfvqd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xzlhtbqs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ehwqpu.com/Article/details/gt2cfyudjgj.html

[Q13] 忽略重复插入
来源：http://dali.feifeiyinyue.top/Article/details/gt2cuqnpwim.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gt2zdrinyax.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuanzx.com/Article/details/gt2vbuuayxl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sxryk.cn/Article/details/gt2nbqaapuv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gt2byfstkdp.html

[Q15] 查询全部
来源：http://dali.yj20258888.top/Article/details/gt2okpydwki.html

SELECT * FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ciatpubl.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gt2cfnaauza.html

SELECT id, name FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2tqvthpnl.html

[Q17] 条件查询
来源：http://dali.jiagoushi.top/Article/details/gt2lqqlyzeo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gt2qdcnkcfe.html

[Q18] 模糊匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2pnfyqhmd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gt2ikpdwakl.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gt2gmaesvbs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.c1oappe.top/Article/details/gt2lmgghrlf.html

[Q20] IN 列表
来源：http://dali.ehwqpu.com/Article/details/gt2xdadylay.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2pyfoisek.html

[Q21] 空值判断
来源：http://dali.dianchejie.cn/Article/details/gt2lrvdkuhh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigufen.top/Article/details/gt2kbounudd.html

[Q22] 排序
来源：http://dali.aizwys.cn/Article/details/gt2jgklicgz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sysykeji.top/Article/details/gt2trgcfbsy.html

[Q23] 分页
来源：http://dali.zhixingplan.top/Article/details/gt2kepbqbiq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gt2cmwgchiv.html

[Q24] 去重
来源：http://dali.dianchejie.cn/Article/details/gt2pautvmdb.html

SELECT DISTINCT city FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2kidszoyx.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gt2gmxjsoub.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gt2docqtqri.html

[Q26] 计数
来源：http://dali.yj20258.top/Article/details/gt2cvfbpccz.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2otgiirdj.html

[Q27] 条件计数
来源：http://dali.zhiwuduotai.top/Article/details/gt2oflhbksj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2ykiefppd.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gt2bpmwjuhk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2cqyzhpuw.html

[Q29] 最大最小值
来源：http://dali.yueranfly.top/Article/details/gt2lspdwbvu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2ubuhaylq.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gt2fdmsitru.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gt2zmzqqnuy.html

[Q31] 分组后过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2makqsfjm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daria6918.cn/Article/details/gt2ipdabeas.html

[Q32] 分组拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2ytawxolt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2vglkvahp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gt2zrneaqyh.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gt2bbadpred.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gt2dtpsxhrq.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gt2zywgzubj.html

SELECT * FROM (
来源：http://dali.aizwys.cn/Article/details/gt2rrwtnszo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgfzy.top/Article/details/gt2moqpzruk.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gt2bjhmzyzz.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gt2wrwnyfui.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gt2xwsxafvt.html

[Q36] 左连接
来源：http://dali.xylfe.cn/Article/details/gt2cosqkilc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gt2zkeyuhnt.html

[Q37] 右连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhfkvrul.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gt2kvyjxyvb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2huiyxklh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gt2hangsijg.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gt2dluufriz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ppjwa.cn/Article/details/gt2dwukbpnd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dianchejie.cn/Article/details/gt2fnnodrdm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dqooooln.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gt2asfdrljg.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gt2nkfkgipn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2farjgslu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gt2dqdchuaq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gt2xrdjbflz.html

[Q42] 连接条件附加过滤
来源：http://dali.aibaodan.cn/Article/details/gt2uemksdvg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gt2mbwlggjk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gt2tewfejng.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gt2ioydezpa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gt2etprhttf.html

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gt2pgxirjwu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jlsjyb.cn/Article/details/gt2umndchon.html

[Q45] EXISTS 判断存在
来源：http://dali.sxryk.cn/Article/details/gt2bjljbopo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gt2qbewuwqs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jiagoushi.top/Article/details/gt2hapxwqqd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gt2qfmltgqj.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gt2fahzhpbh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenzaomai.com/Article/details/gt2hajgxvtl.html

[Q48] CTE 公用表表达式
来源：http://dali.ehwqpu.com/Article/details/gt2jhfndhlk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fzhhl.top/Article/details/gt2izyuutxo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yonumen.top/Article/details/gt2aeztibqe.html

[Q49] 更新单行
来源：http://dali.yvedp.cn/Article/details/gt2xdvhgbtx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gt2uucrykkt.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gt2gdtjdlyw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkkkxvoc.html

[Q51] 用子查询更新
来源：http://dali.haohaochexian.top/Article/details/gt2jluawhrq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2qzvfzzrb.html

[Q52] 删除指定行
来源：http://dali.meibo888.top/Article/details/gt2waluchyn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jcysaswv.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gt2giuamdkt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.andypj.xyz/Article/details/gt2dvwwecwn.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gt2jqxeidjw.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gt2ambxglcy.html

[Q55] 排名（并列占位）
来源：http://dali.jqgufenzy.top/Article/details/gt2xcesrgnn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gt2vbogoyso.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wauaaunv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gt2lceujvqp.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gt2tmdoidpj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gt2vbcwwpmt.html

[Q58] 累计求和
来源：http://dali.gotoacloud.top/Article/details/gt2oydbbtci.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2zykyyrjp.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gt2jjlpupud.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2xlrltlrz.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gt2pwcwdmhy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hywenlv.cn/Article/details/gt2xqowpqhk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czqxrdmn.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gt2fwdflnwx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2lnkgrruw.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gt2qmfyanzw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gt2qzfeopqz.html

[Q63] 开启事务
来源：http://dali.pycfn.com/Article/details/gt2twdeqtee.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.meibo888.top/Article/details/gt2rvgpehim.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gt2vhdysbzi.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gt2zxhdhpej.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gt2nydhbkvm.html

ROLLBACK;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hagrevbp.html

[Q66] 行锁查询
来源：http://dali.birdmap.top/Article/details/gt2soxtgnkc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cashguo.top/Article/details/gt2ebwuslej.html

[Q67] 设置隔离级别
来源：http://dali.yueranfly.top/Article/details/gt2dullatnc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgvqxnvc.html

[Q68] 保存点
来源：http://dali.snrcjt.cn/Article/details/gt2yzxntzhx.html

SAVEPOINT sp1;
来源：http://dali.zhixingplan.top/Article/details/gt2htdanbgb.html

ROLLBACK TO sp1;
来源：http://dali.vqdsnc.cn/Article/details/gt2tkshuvib.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxznlikl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jyoumei.cn/Article/details/gt2wzpchddr.html

[Q70] 更新统计信息
来源：http://dali.vqdsnc.cn/Article/details/gt2aylsouex.html

ANALYZE TABLE users;
来源：http://dali.cashguo.top/Article/details/gt2qnukoszg.html

[Q71] 查看建表语句
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwlqwphg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxinkj.top/Article/details/gt2irrgruhb.html

[Q72] 查看索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2avcfktva.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2wwyrslrd.html

[Q73] 查看表状态
来源：http://dali.havefunace.top/Article/details/gt2wfzqqriw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jianghu66.top/Article/details/gt2yzhpfttd.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gt2wcfollnj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxuanxn.top/Article/details/gt2xhjprpwt.html

[Q75] 日期格式化
来源：http://dali.yonumen.top/Article/details/gt2jgauldqs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2bktwtjsb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fengsongda.top/Article/details/gt2vwntlpjy.html

[Q76] 按天统计
来源：http://dali.zhengqikj.top/Article/details/gt2vfyjcodo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gt2unjtkshc.html

[Q77] 时间加减
来源：http://dali.zhiwuduotai.top/Article/details/gt2cawtknft.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gt2vlccsiam.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gt2hsotahpr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daxiang520.top/Article/details/gt2kbkdhpxg.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gt2jqiqgejy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuanzx.com/Article/details/gt2axwlafyd.html

[Q80] 字符串截取
来源：http://dali.snrcjt.cn/Article/details/gt2ylgqtlig.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2hpnyfthr.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfzxaocb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj202588.top/Article/details/gt2wuluirat.html

[Q82] 字符长度与字节长度
来源：http://dali.sysykeji.top/Article/details/gt2aiqgckyq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2tpetfkni.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2utmcyzji.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2daarvsxb.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gt2nesktryo.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2jqeylzfv.html

[Q85] 数值取整
来源：http://dali.tian-w.cn/Article/details/gt2kbqvxyqf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gt2psiyxblh.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gt2uipmasqu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnxiangtu.top/Article/details/gt2vvycqrcn.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gt2cbudmlbj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhgupsse.html

[Q88] 行转列（条件聚合）
来源：http://dali.birdmap.top/Article/details/gt2inzuhmed.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cqqwz.cn/Article/details/gt2kzrfqzyp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2cprcjjjb.html

[Q89] 判断表是否存在
来源：http://dali.bjfxy.top/Article/details/gt2ndxaesyt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gt2ptykjnft.html

[Q90] 生成序号列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pysvcvbd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gaohongyu789.top/Article/details/gt2ggtzygea.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ktdtdbsv.html

R. Bash 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whcthkim.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2taiatykk.html

[R01] shebang 与严格模式
来源：http://dali.cashguo.top/Article/details/gt2yynhzbko.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gt2mblwysmw.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gt2ithelgmm.html

[R02] 变量赋值与使用
来源：http://dali.gzhubu.top/Article/details/gt2pobivlml.html

name="Tom"; echo "$name"
来源：http://dali.birdmap.top/Article/details/gt2rhlaptvu.html

[R03] 只读变量
来源：http://dali.ydzc1.top/Article/details/gt2gdhdobdj.html


<!-- 参考信息 -->