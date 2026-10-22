代发 wailian999

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gt2ebyhwnkj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.316326.xyz/Article/details/gt2xndbcuvt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gt2ckxozeog.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdqlyfhe.html

TS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gt2jzdhbeso.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zdqjudy.top/Article/details/gt2tkhxubip.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxmafpuz.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gt2bezskevx.html

C#:   Parallel.For
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdzurkpm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2qhuhjbss.html

P. 常用工具函数
来源：http://dali.guannengcc.top/Article/details/gt2uaqfsdgb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2wbptmvft.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gt2voavrfwx.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gt2encarxci.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cdnleiting.top/Article/details/gt2mjkpbwnu.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gt2rgvynnkv.html

TS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gt2eenxrrmo.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgfzy.top/Article/details/gt2odvtsdvz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gt2osrjqtbj.html

Ruby: SecureRandom.uuid
来源：http://dali.cdnleiting.top/Article/details/gt2qklnsgza.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jianghu66.top/Article/details/gt2izljhirn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gt2aqjjqmpz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gt2gtwrltrd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gt2nzwlilwj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2ntfkyhbe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yongpay.top/Article/details/gt2rqidrbkv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gt2wliggswl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.snrcjt.cn/Article/details/gt2uuvldntl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnqzz.top/Article/details/gt2hpxdstia.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gt2ivmdspus.html

[P03] 生成短随机字符串
来源：http://dali.0kj1m.cn/Article/details/gt2mgfbfjkw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gt2fwtaxoby.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gt2vwlvzlfh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gt2mfizykaq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iywearrh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gt2ixgifmvo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gt2irtzrist.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfrvkmd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gt2gmwthafm.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gt2zxdzmwpe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.iojbl.cn/Article/details/gt2rbxymieo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gt2dcqfiran.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvknylph.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zxwxhiff.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2adqcsezi.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gt2vghrrzfg.html

Ruby: x.length;  x.size
来源：http://dali.cheryme.top/Article/details/gt2xoqpofvx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ivvv.top/Article/details/gt2stzpjpme.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ehwqpu.com/Article/details/gt2ymppwuji.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dianchejie.cn/Article/details/gt2zxpzslya.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbalkgsw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gaohongyu789.top/Article/details/gt2pzujhesr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gt2mvswwanu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhixingplan.top/Article/details/gt2mfafvolc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2nclcnwnn.html

Ruby: a == b
来源：http://dali.nanxinkj.top/Article/details/gt2wbdzlrxx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sxryk.cn/Article/details/gt2qjkhlstx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.9152youxi.cn/Article/details/gt2bbrjibxu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gt2swvmalfq.html

PHP:  if (empty($x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2hnrctpet.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258.top/Article/details/gt2djubrfic.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gt2qdhskohj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2tqgfqmtp.html

Go:   if x == nil {}
来源：http://dali.gotoacloud.top/Article/details/gt2cfopfzer.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gt2dqepignb.html

C#:   if (x is null) {}
来源：http://dali.meibo888.top/Article/details/gt2jstalkiq.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gt2hzroqvqf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xylfe.cn/Article/details/gt2dwgwedry.html

PHP:  // 手写时间戳比较
来源：http://dali.shzxlz.cn/Article/details/gt2kyeidazk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gt2emwqejfn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gt2yhsebfij.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gt2syiwmbaq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xylfe.cn/Article/details/gt2qpgcnrdy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gt2bhsixals.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gt2cozhqzse.html

[P08] 处理浮点精度问题
来源：http://dali.chenjidiqi.icu/Article/details/gt2cstnhhps.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnqzz.top/Article/details/gt2gnkuwlyu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2mejbwkrb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj202588.top/Article/details/gt2iwqwsxvk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2voqkymph.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.9152youxi.cn/Article/details/gt2agmdmerz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gt2othrwkud.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vulbgobm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gt2iiksqrqn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ubtotrlb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gt2bgahfqec.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2pslgeekp.html

[Q01] 创建表
来源：http://dali.yanxiufei.cn/Article/details/gt2qccphlwf.html

CREATE TABLE users (
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jajabmoa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gt2nhkdtawy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ivvv.top/Article/details/gt2wnsnbbke.html

email VARCHAR(100) UNIQUE,
来源：http://dali.quarkkingdee.top/Article/details/gt2iedpmbcy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gogol.net.cn/Article/details/gt2whnbkogg.html

);
来源：http://dali.hnqzz.top/Article/details/gt2dobahewu.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gt2kqpksnqd.html

CREATE TABLE orders (
来源：http://dali.cqqwz.cn/Article/details/gt2slboussv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gt2dxnfmxvm.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gt2abyagsrv.html

amount DECIMAL(10, 2),
来源：http://dali.hnqzz.top/Article/details/gt2hijcnipi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrudrwze.html

);
来源：http://dali.fzhhl.top/Article/details/gt2rsvvnwgv.html

[Q03] 增加列
来源：http://dali.havefunace.top/Article/details/gt2gifodwru.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.birdmap.top/Article/details/gt2wanykmgr.html

[Q04] 修改列类型
来源：http://dali.quarkkingdee.top/Article/details/gt2jjndtqfi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.birdmap.top/Article/details/gt2ksatbgsc.html

[Q05] 重命名列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxftouzd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ybcxt.top/Article/details/gt2djinqfzh.html

[Q06] 删除列
来源：http://dali.yangfankeji.com/Article/details/gt2kcsdzwpm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cashguo.top/Article/details/gt2xzjocnzk.html

[Q07] 删除表
来源：http://dali.fzhhl.top/Article/details/gt2llenggzg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jiagoushi.top/Article/details/gt2dyvmmoqs.html

[Q08] 创建普通索引
来源：http://dali.fzhhl.top/Article/details/gt2ntsdavij.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gt2byvbwylg.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gt2wdcfgson.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlwpkmoy.html

[Q10] 插入单行
来源：http://dali.ehwqpu.com/Article/details/gt2dbibduqu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgfzy.top/Article/details/gt2byffymfj.html

[Q11] 一次插入多行
来源：http://dali.cdnleiting.top/Article/details/gt2hvxdxmqt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cdnleiting.top/Article/details/gt2pjomxgkb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjzqeehu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cqqwz.cn/Article/details/gt2mfezfkiw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gt2njjopfpm.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gt2ahtwnqpf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hfpthk.cn/Article/details/gt2rtgnpqbf.html

[Q14] 存在则更新（upsert）
来源：http://dali.quarkkingdee.top/Article/details/gt2nwbkkgmy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gt2mgshqvcm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangshuangyany.cn/Article/details/gt2faszmnbq.html

[Q15] 查询全部
来源：http://dali.9152youxi.cn/Article/details/gt2hmbllbbs.html

SELECT * FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2uoxzwcpp.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gt2kbbecpjg.html

SELECT id, name FROM users;
来源：http://dali.yj20258.top/Article/details/gt2wpssqbrt.html

[Q17] 条件查询
来源：http://dali.wangdashe.top/Article/details/gt2zdytqvvg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2htjjqzov.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewurasnq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fzhhl.top/Article/details/gt2kpkhidhc.html

[Q19] 范围查询
来源：http://dali.yangfankeji.com/Article/details/gt2zqkdydug.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gotoacloud.top/Article/details/gt2mfsatifo.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gt2wajekxqd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gt2gjjyunqa.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gt2hswvkuvl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ehwqpu.com/Article/details/gt2rdqmdgwt.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rawllgzb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sweek.top/Article/details/gt2rasyzzek.html

[Q23] 分页
来源：http://dali.316326.xyz/Article/details/gt2iewkisrx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqgkrwbo.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gt2eelmplya.html

SELECT DISTINCT city FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2mgjajant.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvhjwecc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gt2cntmyvvr.html

[Q26] 计数
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxjnzxcv.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2ccogvouh.html

[Q27] 条件计数
来源：http://dali.tian-w.cn/Article/details/gt2hufeovmr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2aotsiewh.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gt2nwnotonu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2xmqqgiqb.html

[Q29] 最大最小值
来源：http://dali.tianlin.xyz/Article/details/gt2rzzihcts.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2wlgleoce.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gt2rimwxptc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gt2pejjvqrx.html

[Q31] 分组后过滤
来源：http://dali.jinqigufen.top/Article/details/gt2zfftwjmk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zujufqcg.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gt2pmajlyty.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2wqbdrsdp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sweek.top/Article/details/gt2kmzkkpyr.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gt2mxrtokoh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuetiantiany.cn/Article/details/gt2maqvywzp.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gt2npqhzbzz.html

SELECT * FROM (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ewxbiwgx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gogol.net.cn/Article/details/gt2xorwypuw.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gt2lfxmwyrw.html

[Q35] 内连接
来源：http://dali.ydzc1.top/Article/details/gt2uboqexdt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gt2jbnoczvf.html

[Q36] 左连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmsadltu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gt2ssxtecen.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gt2wooiwmdm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gt2lptjaegk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgpoystj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenlongwang.top/Article/details/gt2jnzhoeue.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2rtpaedpy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ppjwa.cn/Article/details/gt2agqsnxfx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxixisif.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.bjfxy.top/Article/details/gt2cgspnixq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gt2mdfipwac.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gt2lefllksc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.snrcjt.cn/Article/details/gt2gowcvmkt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tanke756.top/Article/details/gt2jnjuqlie.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gt2qkhekbpu.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gt2lxxrgyib.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gt2atxpbfoj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kkdyghys.html

[Q43] 标量子查询
来源：http://dali.0kj1m.cn/Article/details/gt2epjwczkv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sweek.top/Article/details/gt2llhmrmeo.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gt2eawvbbbq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gt2ozmawsbe.html

[Q45] EXISTS 判断存在
来源：http://dali.tanke756.top/Article/details/gt2sbonydqh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gt2veffobmx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gt2przoynrb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gt2nkhvvcab.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gtspzjyk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj202588.top/Article/details/gt2dcqyiesf.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gt2wkzgdwcz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gt2oggqxhww.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jiagoushi.top/Article/details/gt2bnrhcose.html

[Q49] 更新单行
来源：http://dali.daxiang520.top/Article/details/gt2mprgwqof.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2omruglpf.html

[Q50] 批量更新
来源：http://dali.gogol.net.cn/Article/details/gt2maxnnyis.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pycfn.com/Article/details/gt2qvcbmycz.html

[Q51] 用子查询更新
来源：http://dali.daria6918.cn/Article/details/gt2gdhbtvkh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xziqi.cn/Article/details/gt2dcweujvb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gbumqtfr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xynizzkw.html

[Q53] 按条件删除
来源：http://dali.fengsongda.top/Article/details/gt2urrjtvmi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.andypj.xyz/Article/details/gt2rnkackcx.html

[Q54] 清空表
来源：http://dali.yj202588.top/Article/details/gt2uduhbtuy.html

TRUNCATE TABLE logs;
来源：http://dali.yj202588.top/Article/details/gt2tffleaen.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gt2lbidosfe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzegicqo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gt2lyzrklkj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gt2bdyzzfsk.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obmmnnyh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2ianxkmid.html

[Q58] 累计求和
来源：http://dali.xuanzx.com/Article/details/gt2bbhpjrxq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2oajiqkbw.html

[Q59] 分组内累计
来源：http://dali.zycfv.cn/Article/details/gt2rvpoxcpm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2ecnostmk.html

[Q60] 取上一行 / 下一行
来源：http://dali.pengpengdd.cyou/Article/details/gt2sadetfeq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ivvv.top/Article/details/gt2ocyavhhm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2jvxngunc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hodulboy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2jwnmluwz.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gt2uzxlbnxz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2dklwpvmh.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gt2zxbiqodi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ehwqpu.com/Article/details/gt2usahlgwl.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gt2ygemwekk.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gt2pfyxkpsv.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gt2zumxlgxm.html

ROLLBACK;
来源：http://dali.redwolf501.top/Article/details/gt2gcvnjclf.html

[Q66] 行锁查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wisbyafn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gt2xgogmhal.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gt2vxcbhulj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gt2edgmsxte.html

[Q68] 保存点
来源：http://dali.hnxiangtu.top/Article/details/gt2odcmgsug.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gt2iipquqvs.html

ROLLBACK TO sp1;
来源：http://dali.snrcjt.cn/Article/details/gt2fyqdkvvm.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gt2ekxhtpfp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gt2axlaqwmg.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gt2gntlyxok.html

ANALYZE TABLE users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fowncqkd.html

[Q71] 查看建表语句
来源：http://dali.chenlongwang.top/Article/details/gt2zmkgjkmm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gt2wbwjvjjf.html

[Q72] 查看索引
来源：http://dali.nwbrower.top/Article/details/gt2fmhkwrea.html

SHOW INDEX FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrpvvnjz.html

[Q73] 查看表状态
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygewighe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.iojbl.cn/Article/details/gt2sevwjles.html

[Q74] 强制使用索引
来源：http://dali.chenlongwang.top/Article/details/gt2uzjztnow.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjitorlc.html

[Q75] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gt2daxopyjs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2qlpyotqb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shangyingyoupin.top/Article/details/gt2znkoikhh.html

[Q76] 按天统计
来源：http://dali.nwbrower.top/Article/details/gt2khoqoagc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gt2ntaqaimd.html

[Q77] 时间加减
来源：http://dali.smart0.xyz/Article/details/gt2nsvuitws.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.iojbl.cn/Article/details/gt2vqhhkxnp.html

[Q78] 当前时间
来源：http://dali.hysaishi.cn/Article/details/gt2nzazztyx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gt2duzzewva.html

[Q79] 字符串拼接
来源：http://dali.iojbl.cn/Article/details/gt2hglkacak.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gt2vibjbgtb.html

[Q80] 字符串截取
来源：http://dali.jinqigfzy.top/Article/details/gt2acghomhr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2tfulnhpv.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqlsmkmj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2ysshsfqe.html

[Q82] 字符长度与字节长度
来源：http://dali.haohaochexian.top/Article/details/gt2olhsjkgc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2hzpwxahr.html

[Q83] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pnzyqmke.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2sfvufoqy.html

[Q84] 去除首尾空格
来源：http://dali.snrcjt.cn/Article/details/gt2vlmvnzsg.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2yrnzeiov.html

[Q85] 数值取整
来源：http://dali.sufxvd.cn/Article/details/gt2efrusctm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gt2gkqylzpk.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gt2lroatwni.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gt2vjygiryc.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gt2atfoejkk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gt2udtojvdq.html

[Q88] 行转列（条件聚合）
来源：http://dali.hfpthk.cn/Article/details/gt2kcgskknf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hammf.cn/Article/details/gt2zrtbgtag.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2ysfiueuo.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwlgcfqy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bmpwilvb.html

[Q90] 生成序号列
来源：http://dali.ehwqpu.com/Article/details/gt2ekjvuarr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tadxihjc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivyaesfv.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gt2czhsreuo.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2cbrmouto.html

[R01] shebang 与严格模式
来源：http://dali.mhx1999.top/Article/details/gt2qdlllinp.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gt2rxfwigvz.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gt2glslaicd.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gt2yrssceoq.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gt2pjrnnryt.html

[R03] 只读变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahytluxs.html


<!-- 参考信息 -->