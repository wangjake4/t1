代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guannengcc.top/Article/details/gtvomafcpw.html

JS:   async function f() { await g(); }
来源：http://dali.xinyue.icu/Article/details/gtdoouxdqm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gteszuchwg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gtskffhaas.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aizwys.cn/Article/details/gtyjmyjgkl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gtxgakvhyy.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gtchqiuuvd.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhengqikj.top/Article/details/gtckummqbh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj202588.top/Article/details/gtkptjmotc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangshuangyany.cn/Article/details/gtzzeewdwl.html

JS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gthxcxqknb.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtkjgkyoog.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gtqknwzmld.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtposihbgh.html

Ruby: threads.map(&:join)
来源：http://dali.xinyue.icu/Article/details/gtsgfsdscy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.9152youxi.cn/Article/details/gtgetcdxgg.html

[O06] 使用进程池
来源：http://dali.cucudq.cn/Article/details/gtwyljrlrz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhongyouzk.top/Article/details/gtxixcbaoq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cdnleiting.top/Article/details/gtubpazvbn.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtmjmuaxud.html

TS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtazilnclp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yvedp.cn/Article/details/gttucexooe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.9152youxi.cn/Article/details/gtxqpfsfky.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gtkmruscut.html

C#:   Parallel.For
来源：http://dali.shanyushiyangtech.top/Article/details/gtllwlrlkk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxzpzsfhh.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gtorzswuxe.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtgwfakukj.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtdyhcvzqu.html

Py:   str(uuid.uuid4())
来源：http://dali.ydzc1.top/Article/details/gtfturzwux.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtkibywlca.html

JS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gthptnkozj.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gteksbonam.html

Java: UUID.randomUUID().toString()
来源：http://dali.snrcjt.cn/Article/details/gttllvhpry.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gotoacloud.top/Article/details/gtksodqcfe.html

Ruby: SecureRandom.uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtrftbznnr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gtzmagrnxr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daxiang520.top/Article/details/gtdfhjvzds.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtqjnfjxse.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtrehpxxdr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pycfn.com/Article/details/gtqnpytjld.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gtmvqflbaq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtkkexjksb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yanxiufei.cn/Article/details/gtbthamllt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hysaishi.cn/Article/details/gtoditgrvd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.andypj.xyz/Article/details/gtydpacxnp.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gtnbnyawka.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yanxiufei.cn/Article/details/gtekdvdjcx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxktpizcp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gthuddjwpc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtehnbshrs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtyrmygwjd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cashguo.top/Article/details/gtxolkrymm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gtllmqidxl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gtarotcivd.html

[P04] 求长度
来源：http://dali.tanke756.top/Article/details/gtdnmewzom.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gthxnnubvt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtkxrrvdvu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtkhboyovz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtlklihadk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtczedtdiu.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gtgujrjwvl.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxqstaha.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangdashe.top/Article/details/gtisjqkrnn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.andypj.xyz/Article/details/gtihahyxgu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yvedp.cn/Article/details/gtelmqffbx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gtfdnkffar.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ehwqpu.com/Article/details/gtxxjknhmn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtgdkfqffz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgufenzy.top/Article/details/gtjrmfxedg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gtfocktuii.html

Ruby: a == b
来源：http://dali.0kj1m.cn/Article/details/gtkvdrsdzy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenjidiqi.icu/Article/details/gtimmrgbzx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pengpengdd.cyou/Article/details/gtlwtplgex.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gotoacloud.top/Article/details/gtkawzilxd.html

PHP:  if (empty($x)) {}
来源：http://dali.zhengqikj.top/Article/details/gtgqexplou.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cucudq.cn/Article/details/gtpkuszhvs.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujmajiyb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtjuczcuty.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthszoeqom.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenlongwang.top/Article/details/gthxhnqcct.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gtkyexfrmv.html

[P07] 防抖与节流
来源：http://dali.svipenyu.cn/Article/details/gtohzfulyd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.havefunace.top/Article/details/gteutpcdia.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gtojhgdxia.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtgonaaasv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtxilsjxez.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtxagxcdtx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gtxxwxxezc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.haohaochexian.top/Article/details/gtglmnydow.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sysykeji.top/Article/details/gtjcwudgtg.html

[P08] 处理浮点精度问题
来源：http://dali.nwbrower.top/Article/details/gtmfsahprg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnpzxgko.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gtlrnjebaq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gtbiokdavo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gtcuegwrmq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gtbleecomg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aibaodan.cn/Article/details/gtnhhebich.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gtvzhmtawl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gthshyzsyw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtiiglyume.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gtmgzjsbfg.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjqubkhkv.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gtudfujzba.html

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gtifhrbaua.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtqccvpdlo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.birdmap.top/Article/details/gtxzaawiak.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gtnyyuhpiv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gogol.net.cn/Article/details/gtbvfpiihe.html

);
来源：http://dali.sxryk.cn/Article/details/gtdpvcwouy.html

[Q02] 创建带外键的表
来源：http://dali.xziqi.cn/Article/details/gtmjreduos.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gtzemrsuft.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbkyeeyu.html

user_id INT NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtnvwfxumq.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gtqdcntihz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.quarkkingdee.top/Article/details/gtdsfloddq.html

);
来源：http://dali.chenlongwang.top/Article/details/gtmauvkuhr.html

[Q03] 增加列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruedelcw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tanke756.top/Article/details/gtbvswvyeb.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgkneiea.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gtgvyeescs.html

[Q05] 重命名列
来源：http://dali.shanyushiyangtech.top/Article/details/gtrchnaogd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtwcouwqte.html

[Q06] 删除列
来源：http://dali.zhoulong.xyz/Article/details/gtrzwkujdx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gtbbbobbiv.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gtgkexknsg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtispqyrji.html

[Q08] 创建普通索引
来源：http://dali.sxryk.cn/Article/details/gtkakzssod.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gtqtvezowv.html

[Q09] 创建唯一索引
来源：http://dali.jqgufenzy.top/Article/details/gtgqcpbyls.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gtbctbggnq.html

[Q10] 插入单行
来源：http://dali.ppjwa.cn/Article/details/gttslimvkt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtkboohlvq.html

[Q11] 一次插入多行
来源：http://dali.mhx1999.top/Article/details/gtrjxhmqaf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gttgvxyvqk.html

[Q12] 插入后取自增 ID
来源：http://dali.yuanzhike.top/Article/details/gtmyfiufqy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangshuangyany.cn/Article/details/gtwetjyybz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhoulong.xyz/Article/details/gtlkcdrwox.html

[Q13] 忽略重复插入
来源：http://dali.hongshengwenyu.top/Article/details/gtwozxwsoc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gtcbkfljeu.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuanzx.com/Article/details/gtlrwsytht.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gtvvpwltwl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ybcxt.top/Article/details/gtfetzkqfn.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gtgvyzpfnb.html

SELECT * FROM users;
来源：http://dali.c1oappe.top/Article/details/gtgkjxoaaj.html

[Q16] 查询指定列
来源：http://dali.bjfxy.top/Article/details/gtuqdcxuep.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtsedfyxhi.html

[Q17] 条件查询
来源：http://dali.hfpthk.cn/Article/details/gtdhwajykb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxinkj.top/Article/details/gtjhfwuiqq.html

[Q18] 模糊匹配
来源：http://dali.dashuyun.cn/Article/details/gtqysilezz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gthvarkoob.html

[Q19] 范围查询
来源：http://dali.yuanzhike.top/Article/details/gtsrgkyndh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yongpay.top/Article/details/gtijcxzqun.html

[Q20] IN 列表
来源：http://dali.yj20258.top/Article/details/gtwhmfjfts.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cheryme.top/Article/details/gtebfklyws.html

[Q21] 空值判断
来源：http://dali.xinyue.icu/Article/details/gtuxqogfgj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.havefunace.top/Article/details/gtwihkgpyo.html

[Q22] 排序
来源：http://dali.gogol.net.cn/Article/details/gtbanbtpib.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yonumen.top/Article/details/gtgtxczjjg.html

[Q23] 分页
来源：http://dali.hongshengwenyu.top/Article/details/gtwregkfxg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtikfzmbft.html

[Q24] 去重
来源：http://dali.gogol.net.cn/Article/details/gtknvcezzy.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gthynsseqe.html

[Q25] 只取前 N 条
来源：http://dali.c1oappe.top/Article/details/gtaspfhonb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gtgoautwqx.html

[Q26] 计数
来源：http://dali.pycfn.com/Article/details/gtvpuhmphx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtovlqxrzv.html

[Q27] 条件计数
来源：http://dali.chenlongwang.top/Article/details/gtoodygszm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtvuargqzr.html

[Q28] 求和与平均
来源：http://dali.smart0.xyz/Article/details/gtkxvywhov.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtalmfwmzl.html

[Q29] 最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtxagznqgn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtsxejymij.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gtzyfvxhav.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gteqbdcuea.html

[Q31] 分组后过滤
来源：http://dali.tianlin.xyz/Article/details/gtlgffhprj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnqzz.top/Article/details/gtefsxvgcd.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258.top/Article/details/gteuvrppby.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtzuwsrqpb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yongpay.top/Article/details/gtitenbckz.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gtmfzmedbd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hywenlv.cn/Article/details/gtdkuswubp.html

[Q34] 每组取第一条
来源：http://dali.daria6918.cn/Article/details/gtzbmigfoe.html

SELECT * FROM (
来源：http://dali.aizwys.cn/Article/details/gtiiyyiahz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhixingplan.top/Article/details/gtunggizug.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gtnluidwmz.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gttdesjcfd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtvuryjmui.html

[Q36] 左连接
来源：http://dali.yj20258888.top/Article/details/gtailrwqln.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtfyreghle.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gtitxjhrwg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtybbbdczs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yvedp.cn/Article/details/gtsfofkmbm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenlongwang.top/Article/details/gtjfixlpzt.html

[Q39] 自连接（查上下级）
来源：http://dali.nwbrower.top/Article/details/gtvxircndm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmyruvef.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.mhx1999.top/Article/details/gtoxpyoomy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.bjfxy.top/Article/details/gtlzpppgks.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnptkpyug.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gthwerkzia.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.vqdsnc.cn/Article/details/gtodbwjgrp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.meibo888.top/Article/details/gtfqjgdrxw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zycfv.cn/Article/details/gtzesodapx.html

[Q42] 连接条件附加过滤
来源：http://dali.sufxvd.cn/Article/details/gtyizelpkw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aibaodan.cn/Article/details/gtgbumhqmh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.quarkkingdee.top/Article/details/gthnqsogwo.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlobbnpx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhengqikj.top/Article/details/gtfbfzdsfu.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gtwfwmkaxo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhengqikj.top/Article/details/gtrxjqosih.html

[Q45] EXISTS 判断存在
来源：http://dali.gotoacloud.top/Article/details/gtqtmehaox.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtssofltut.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gtbbismccs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtqbhcfodk.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gtblacaaif.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gtuzidvucw.html

[Q48] CTE 公用表表达式
来源：http://dali.xuanzx.com/Article/details/gtkduwjccx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gtjvavgame.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tianlin.xyz/Article/details/gtngdkarxx.html

[Q49] 更新单行
来源：http://dali.dianchejie.cn/Article/details/gtluxhfasi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gtalldrkrm.html

[Q50] 批量更新
来源：http://dali.jqgufenzy.top/Article/details/gtuuvpkrdm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cashguo.top/Article/details/gtriwvjivy.html

[Q51] 用子查询更新
来源：http://dali.ydzc1.top/Article/details/gtrhlbahpa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jlsjyb.cn/Article/details/gthapfnwae.html

[Q52] 删除指定行
来源：http://dali.cdnleiting.top/Article/details/gtmzixlxqh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtazghmmta.html

[Q53] 按条件删除
来源：http://dali.sysykeji.top/Article/details/gtqlatrzer.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.iojbl.cn/Article/details/gtmdwwyggi.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gtlojrwcew.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtbwbltyoc.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gtkuxpnkca.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtotxjlvmt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hfpthk.cn/Article/details/gtmwmalybe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygngiduu.html

[Q57] 行号
来源：http://dali.yj20258888.top/Article/details/gtkhbwbyxk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcisocprk.html

[Q58] 累计求和
来源：http://dali.9152youxi.cn/Article/details/gtuxiphuzi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtgljnwwsr.html

[Q59] 分组内累计
来源：http://dali.redwolf501.top/Article/details/gthoqqfmxy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtptjphyog.html

[Q60] 取上一行 / 下一行
来源：http://dali.kuanghao11.cn/Article/details/gtxbakbyfn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gtnvurjiwu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtteqbcutx.html

[Q61] 移动平均
来源：http://dali.xinyue.icu/Article/details/gtymmmqwqm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gttoqlrhso.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gtrhajqmzo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtrkziyalr.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gtnocpxlkn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nwbrower.top/Article/details/gtvloffpjk.html

[Q64] 提交事务
来源：http://dali.dianchejie.cn/Article/details/gtgzoppluq.html

COMMIT;
来源：http://dali.ppjwa.cn/Article/details/gtnxuxjujs.html

[Q65] 回滚事务
来源：http://dali.hongshengwenyu.top/Article/details/gtnqtzbvek.html

ROLLBACK;
来源：http://dali.tanke756.top/Article/details/gtehxotlzy.html

[Q66] 行锁查询
来源：http://dali.aizwys.cn/Article/details/gtijygasnq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gtssdfqorn.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gtdzsetiqj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gogol.net.cn/Article/details/gtyafqzcwp.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gtqjxxqqva.html

SAVEPOINT sp1;
来源：http://dali.sxryk.cn/Article/details/gtgoumbugp.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguacglck.html

[Q69] 查看执行计划
来源：http://dali.dashuyun.cn/Article/details/gtlvuesrjo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.redwolf501.top/Article/details/gtecawvxzj.html

[Q70] 更新统计信息
来源：http://dali.tianlin.xyz/Article/details/gtbuuhzhbn.html

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gtcwptmdph.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gtpsmqzzpn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtfafvqzju.html

[Q72] 查看索引
来源：http://dali.nanxuanxn.top/Article/details/gthjtbbmki.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gtamvrnwqy.html

[Q73] 查看表状态
来源：http://dali.tanke756.top/Article/details/gtcmrbanxs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.c1oappe.top/Article/details/gtgmepbqqm.html

[Q74] 强制使用索引
来源：http://dali.guannengcc.top/Article/details/gtncnrzbee.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ydzc1.top/Article/details/gtzgesutyn.html

[Q75] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtquaesqsg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtrdfzyvle.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gtfelfqxmr.html

[Q76] 按天统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutkgrpfr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gthajhnios.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gtorqfcial.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gtzfhrdcic.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtgqxfnlpx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtmpcybjio.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gtcpzvyhex.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gttugtkxvf.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gtdnaeewvq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtorbcnuqd.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtglnouxai.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtyuyhcnjo.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigufen.top/Article/details/gtsojijphu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtlkwemgwo.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gttxyljkjv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtdaadkjya.html

[Q84] 去除首尾空格
来源：http://dali.sweek.top/Article/details/gtjrgidvev.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtqiqzvvtt.html

[Q85] 数值取整
来源：http://dali.nanxinkj.top/Article/details/gtlgnzmhew.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtuwzeamdw.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gtudkizttn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnqzz.top/Article/details/gtzdbzoqty.html

[Q87] JSON 字段做条件
来源：http://dali.hywenlv.cn/Article/details/gtklztjnht.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrzjvimu.html


<!-- 参考信息 -->