代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gt2iojnywxu.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlmzwfvi.html

Java: synchronized (this) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gt2qtlgrqkg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wlsbqmco.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gt2paozmgfs.html

C#:   lock (gate) { shared++; }
来源：http://dali.hammf.cn/Article/details/gt2slasdtwk.html

[O04] 定义异步函数并等待
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnsvosyb.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gt2gciprcex.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gt2hfkdpwdv.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gt2nuoqhrhp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daxiang520.top/Article/details/gt2potdzwhh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhlgrpgx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xziqi.cn/Article/details/gt2kaniygvq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fengsongda.top/Article/details/gt2huhbjkgf.html

C#:   async Task F() { await G(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2urxyqdig.html

[O05] 并发执行并等待全部完成
来源：http://dali.havefunace.top/Article/details/gt2bjgfuvuc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gt2enogvtwv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhengqikj.top/Article/details/gt2kdhirxoy.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gt2fydwmccz.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2qbcoefcx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.birdmap.top/Article/details/gt2ezehrxhb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guannengcc.top/Article/details/gt2nwmwnwdp.html

Ruby: threads.map(&:join)
来源：http://dali.hnqzz.top/Article/details/gt2upziddnw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sxryk.cn/Article/details/gt2zxanbeaa.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gt2pisdceeq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gt2ckzktlia.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.meibo888.top/Article/details/gt2vfuioniw.html

JS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gt2ikzemiyt.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gt2ksbtgewx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gt2skbamvxq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gt2kzxfloyc.html

Ruby: // fork 块
来源：http://dali.ydzc1.top/Article/details/gt2aqlseake.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gt2jrhevmrz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2nsopfoqk.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gt2adbynfcz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2yqcordhj.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozgjngcr.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gt2mqoaqcmw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gt2zslcqwxh.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gt2aeisvxxf.html

TS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gt2sbksrjyk.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytjijkbk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gt2lsnvxxxs.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gt2fyixqneb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gaohongyu789.top/Article/details/gt2rckalmsa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gt2xinoyyzr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guowangkeji.top/Article/details/gt2fubinvyb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.bjfxy.top/Article/details/gt2crvcshdo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnxiangtu.top/Article/details/gt2xuoouhfy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbgcygsv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwrdlojd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gt2rplblogn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gt2jchlyhzo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangshuangyany.cn/Article/details/gt2omuacbxn.html

[P03] 生成短随机字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2njlsancq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.kuanghao11.cn/Article/details/gt2snivglep.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gt2olbxlmxu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gt2oqlciwgt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gt2ynbwjaql.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gt2ocognbts.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhoulong.xyz/Article/details/gt2jzkfzwai.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gt2drwbhmty.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sweek.top/Article/details/gt2jchidrli.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wcbjwtxp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yongpay.top/Article/details/gt2pncznend.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2eldyhxnl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gt2ttgcuswu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gt2wgaymgpb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgjsibvw.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgvdtmoe.html

Ruby: x.length;  x.size
来源：http://dali.cucudq.cn/Article/details/gt2dxwbxzec.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.birdmap.top/Article/details/gt2jfxhqcnv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gt2akdgtfkr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhmxxxvj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gt2oveswjqn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gotoacloud.top/Article/details/gt2qeskpqws.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gt2nebzqjlq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddpvfrfu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gt2ikrzlube.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gt2iteybwxn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gt2bbahdgmu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gt2ypdwzvmo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxjhssjw.html

PHP:  if (empty($x)) {}
来源：http://dali.hywenlv.cn/Article/details/gt2nmleopwe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gt2cweukzwe.html

TS:   if (x == null) {}
来源：http://dali.ppjwa.cn/Article/details/gt2rgnkqhcp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gt2hhvxpjks.html

Go:   if x == nil {}
来源：http://dali.zhoulong.xyz/Article/details/gt2stshbftt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akxapylm.html

C#:   if (x is null) {}
来源：http://dali.ehwqpu.com/Article/details/gt2uytxucxd.html

[P07] 防抖与节流
来源：http://dali.tianlin.xyz/Article/details/gt2rghrpjqt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gt2ufbaomhu.html

PHP:  // 手写时间戳比较
来源：http://dali.smart0.xyz/Article/details/gt2modelwwh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mecexdsy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gt2tqeenfia.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebzvsxci.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gt2xbtudepn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guannengcc.top/Article/details/gt2sjqdmato.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.meibo888.top/Article/details/gt2yyrtnlwd.html

[P08] 处理浮点精度问题
来源：http://dali.redwolf501.top/Article/details/gt2ymyvpwed.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gotoacloud.top/Article/details/gt2yhjnacok.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cashguo.top/Article/details/gt2gvfxshqb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gt2hxmsltlk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gt2wpgpduqy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fzhhl.top/Article/details/gt2rtcngpzj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gt2zavpnqow.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsjxhmaj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gt2htispxuc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2phvqhoal.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gt2oxqemftl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixhsgxkd.html

[Q01] 创建表
来源：http://dali.sxryk.cn/Article/details/gt2kjadbzzf.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gt2foqkgkzc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gt2eaguwkwv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gt2yumwekeu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppsevobr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.bjfxy.top/Article/details/gt2zngeseoc.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmezsfrj.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enorqnak.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gt2oseaeaxk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gt2zdszpbai.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gt2ucxugscv.html

amount DECIMAL(10, 2),
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfhzexzl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gt2egevkqol.html

);
来源：http://dali.kuanghao11.cn/Article/details/gt2ipfalcbz.html

[Q03] 增加列
来源：http://dali.nanxinkj.top/Article/details/gt2zofqjpoh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tian-w.cn/Article/details/gt2sbhmlhyi.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gt2dxwraudj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gt2xxzuftpp.html

[Q05] 重命名列
来源：http://dali.guowangkeji.top/Article/details/gt2npcgdpce.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guannengcc.top/Article/details/gt2vhuuovdb.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpofilvl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gt2elrmvwqo.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gt2gpgfmnur.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yongpay.top/Article/details/gt2hjkzwjtt.html

[Q08] 创建普通索引
来源：http://dali.xziqi.cn/Article/details/gt2dgfianek.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gt2oysjqbzu.html

[Q09] 创建唯一索引
来源：http://dali.smart0.xyz/Article/details/gt2horaflsj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qzyjwxnj.html

[Q10] 插入单行
来源：http://dali.cashguo.top/Article/details/gt2plqlisvc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gt2czlauahy.html

[Q11] 一次插入多行
来源：http://dali.sweek.top/Article/details/gt2qddipmaa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.svipenyu.cn/Article/details/gt2qesjoqwo.html

[Q12] 插入后取自增 ID
来源：http://dali.9152youxi.cn/Article/details/gt2ctkjktev.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gt2yzvlthrs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gt2wimzmdqy.html

[Q13] 忽略重复插入
来源：http://dali.kuanghao11.cn/Article/details/gt2zwashgjm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgdkwoof.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gt2hemgmyrq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gt2eyddxrvg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tcxocnbt.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gt2mdveyvyx.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2khhhnelz.html

[Q16] 查询指定列
来源：http://dali.hywenlv.cn/Article/details/gt2efjhsxah.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2rozzywfu.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gt2tcpdnkzc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxtijbkf.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gt2aneihblm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.haohaochexian.top/Article/details/gt2lllalaxd.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gt2povlvjsk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cucudq.cn/Article/details/gt2itvycfsy.html

[Q20] IN 列表
来源：http://dali.gaohongyu789.top/Article/details/gt2syicctix.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2wodtefud.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tsttltki.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cheryme.top/Article/details/gt2hrladvvv.html

[Q22] 排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zcsrnzkt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shuidangran.top/Article/details/gt2nfsgabac.html

[Q23] 分页
来源：http://dali.xziqi.cn/Article/details/gt2ohcajuww.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cashguo.top/Article/details/gt2izaeipla.html

[Q24] 去重
来源：http://dali.hfpthk.cn/Article/details/gt2updzouvc.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj202588.top/Article/details/gt2lirwskev.html

[Q25] 只取前 N 条
来源：http://dali.jianghu66.top/Article/details/gt2layalkas.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sysykeji.top/Article/details/gt2vecpgyrq.html

[Q26] 计数
来源：http://dali.hnxiangtu.top/Article/details/gt2ckizqlbn.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2slynekad.html

[Q27] 条件计数
来源：http://dali.ehwqpu.com/Article/details/gt2nibmrxtd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2oisjanuu.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gt2fllpodjh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2hyrtbzpi.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqzwvift.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2hnsnjfxi.html

[Q30] 分组统计
来源：http://dali.yuanzhike.top/Article/details/gt2kbafvutz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2itoinbnx.html

[Q31] 分组后过滤
来源：http://dali.jianghu66.top/Article/details/gt2etkuxqkx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhixingplan.top/Article/details/gt2wtlossxo.html

[Q32] 分组拼接字符串
来源：http://dali.hammf.cn/Article/details/gt2kqqxytfr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfzbbzxz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.9152youxi.cn/Article/details/gt2qjahanka.html

[Q33] 多列分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhcdnbjs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cucudq.cn/Article/details/gt2aubacvfr.html

[Q34] 每组取第一条
来源：http://dali.shangyingyoupin.top/Article/details/gt2tmlslzlk.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gt2vutonflu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gt2rcowxrpa.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gt2dudmdzyw.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltispglu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwkqppoh.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gt2yfsnaxqb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gt2alcbuqpk.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gt2xlzpnpjw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gt2wanlotcn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gt2eojrzcxm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2efnstsls.html

[Q39] 自连接（查上下级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2zeellabv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ehwqpu.com/Article/details/gt2sluziyjz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gt2aftzxwsn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gt2ibxmcztp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ybcxt.top/Article/details/gt2twuqivjn.html

[Q41] 多表连接
来源：http://dali.0kj1m.cn/Article/details/gt2laudmhlg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sufxvd.cn/Article/details/gt2otozacvi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhixingplan.top/Article/details/gt2hizzwsvu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gt2qvdsgwyv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2ihswcsjf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yongpay.top/Article/details/gt2kqaboitc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxuanxn.top/Article/details/gt2jvecgnmk.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gt2tcuffyxi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ngjncequ.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gt2ogzgmyus.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dianchejie.cn/Article/details/gt2yzfxsqlx.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2qnkupzzs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gt2nxvlfyzo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gt2qpopnnnm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gt2kvfntdho.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntlwcphg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xinyue.icu/Article/details/gt2zkgwxfgl.html

[Q48] CTE 公用表表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2dhkbcrqm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gt2ccgdhcdb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.vqdsnc.cn/Article/details/gt2rpbaqcbl.html

[Q49] 更新单行
来源：http://dali.chenzaomai.com/Article/details/gt2ysrdrpvd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2yucwffnd.html

[Q50] 批量更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjluulup.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncnehout.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjlnmpcv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fzhhl.top/Article/details/gt2sfjmlknc.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gt2sguwxyci.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktqvnsco.html

[Q53] 按条件删除
来源：http://dali.nanxinkj.top/Article/details/gt2pqceqrca.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gt2atjibsfa.html

[Q54] 清空表
来源：http://dali.xziqi.cn/Article/details/gt2gqbgsvth.html

TRUNCATE TABLE logs;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2utvkyqfu.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gt2wifcqovg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuxming.cn/Article/details/gt2wdosuokl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xinyue.icu/Article/details/gt2gemuaixd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gt2jvgtsdht.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gt2naknaiix.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2urzfidpu.html

[Q58] 累计求和
来源：http://dali.sufxvd.cn/Article/details/gt2hihdtxqm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2kqcqeiec.html

[Q59] 分组内累计
来源：http://dali.sufxvd.cn/Article/details/gt2fbhfyfql.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2neldtnoo.html

[Q60] 取上一行 / 下一行
来源：http://dali.bjfxy.top/Article/details/gt2cnbqepzg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zycfv.cn/Article/details/gt2hoqrfcpt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2qhftzaqo.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gt2vybgfury.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2wixnxvzd.html

[Q62] 分组占比
来源：http://dali.xylfe.cn/Article/details/gt2hwgcgqcp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2liaqgqkf.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gt2vmxfksgf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.birdmap.top/Article/details/gt2dqlnecnv.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gt2fpqfuwop.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2luxskgyc.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gt2bbthfvtb.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gt2agcwgkan.html

[Q66] 行锁查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2cuyqjqhz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjleeqps.html

[Q67] 设置隔离级别
来源：http://dali.yanxiufei.cn/Article/details/gt2iliftrsb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cashguo.top/Article/details/gt2bdlzxude.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gt2vnqcbhjy.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gt2ebuxuvqs.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gt2gvcpgsth.html

[Q69] 查看执行计划
来源：http://dali.cdnleiting.top/Article/details/gt2dtnsczrv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gt2ojmodudf.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gt2mijzsjxu.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gt2fxvzbjnm.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gt2ncqtlyba.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sxryk.cn/Article/details/gt2xaxpsrep.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gt2hekdbkye.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2yhytpgpe.html

[Q73] 查看表状态
来源：http://dali.hfpthk.cn/Article/details/gt2hcozulci.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybdezytr.html

[Q74] 强制使用索引
来源：http://dali.316326.xyz/Article/details/gt2byuxqjlm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnqzz.top/Article/details/gt2fworxlcp.html

[Q75] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2kikhtyii.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2fypnmawd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gt2bdaskgkp.html

[Q76] 按天统计
来源：http://dali.yuanzhike.top/Article/details/gt2vxuxgkmb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tanke756.top/Article/details/gt2nkknmvhr.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gt2ixvkhugv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gt2iixugmll.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gt2hhrnntka.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fengsongda.top/Article/details/gt2fvgwxxdm.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gt2zxknmvty.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shuidangran.top/Article/details/gt2cjqpsmwj.html

[Q80] 字符串截取
来源：http://dali.svipenyu.cn/Article/details/gt2wouxrjtc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2acprfsbx.html

[Q81] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odmocwzw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2dbhujdts.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gt2sffvtwlp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2pezngqaw.html

[Q83] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2pajpxkdr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2ffermewb.html


<!-- 参考信息 -->