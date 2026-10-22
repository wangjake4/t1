代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.snrcjt.cn/Article/details/gt2ffcxzwjd.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gt2jgalnnyd.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gt2echqlspt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ljfazhrw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cucudq.cn/Article/details/gt2nrzfqmws.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gt2asnjzefg.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gt2ikdjkkwl.html

Py:   async def f():⏎    await g()
来源：http://dali.zhoulong.xyz/Article/details/gt2ehthbgiv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guannengcc.top/Article/details/gt2aspzquma.html

JS:   async function f() { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gt2taqqtmts.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2oktnswti.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gt2ucxanvip.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.0kj1m.cn/Article/details/gt2qxwclvcv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gt2pxeedqji.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gt2qkmaqwen.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gt2zusewaip.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcleypiy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.vqdsnc.cn/Article/details/gt2atslrjld.html

JS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gt2rrmbdtnl.html

TS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujasvaii.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gt2ntcrnxoc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xylfe.cn/Article/details/gt2nmnoqura.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2flodtsjf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aizwys.cn/Article/details/gt2drtngmto.html

[O06] 使用进程池
来源：http://dali.shzxlz.cn/Article/details/gt2krkmmsjy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jiagoushi.top/Article/details/gt2gggcfxgk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gt2krkkxbid.html

JS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gt2vwcsfnby.html

TS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gt2lyxrbxch.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gt2vmtxexry.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenzaomai.com/Article/details/gt2zfvyfsul.html

Ruby: // fork 块
来源：http://dali.chenjidiqi.icu/Article/details/gt2onmmnbjc.html

C#:   Parallel.For
来源：http://dali.fzhhl.top/Article/details/gt2uyksudbl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2dmwgwzcx.html

P. 常用工具函数
来源：http://dali.aizwys.cn/Article/details/gt2toyhiyeh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2zifetzdh.html

[P01] 生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gt2hwkcogjq.html

Py:   str(uuid.uuid4())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdvkoxqz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gt2dnjnxuhe.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2owixslsu.html

TS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2framjzbo.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gt2eautykvn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zycfv.cn/Article/details/gt2cvfzeghe.html

Ruby: SecureRandom.uuid
来源：http://dali.andypj.xyz/Article/details/gt2ksvbjhfy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pycfn.com/Article/details/gt2aqgwuykd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gt2cmttmwco.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jlsjyb.cn/Article/details/gt2hmvhjjup.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tian-w.cn/Article/details/gt2sbgqmtca.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gt2mezkaort.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gt2dlrrpiei.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gt2qqelyqjz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yanxiufei.cn/Article/details/gt2mvxnkfmv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gt2hlijkvsu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ppjwa.cn/Article/details/gt2fjnqwjho.html

[P03] 生成短随机字符串
来源：http://dali.zycfv.cn/Article/details/gt2paxymguk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gt2nvxblryi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mmeftnoe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gt2vbkvagfw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gt2hbwmwreu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.meibo888.top/Article/details/gt2agntdbdp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gt2tarxtthb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zdqjudy.top/Article/details/gt2brdyurwx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jyoumei.cn/Article/details/gt2ixxbxyvp.html

[P04] 求长度
来源：http://dali.tanke756.top/Article/details/gt2rdhuxrai.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gt2btzhamhy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2cbzuvetf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gt2pxtpukim.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gt2pmfsvcnj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tksglvec.html

Go:   len(arr);  len(m)
来源：http://dali.gogol.net.cn/Article/details/gt2ovkfbwfo.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gt2mzsuyeic.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gt2vpcdkuoo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.redwolf501.top/Article/details/gt2jglupril.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryvfcsox.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gt2fntnhahz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tianlin.xyz/Article/details/gt2aepxxtpb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gt2twcvopuw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gt2fsshxvco.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.0kj1m.cn/Article/details/gt2qisvvghe.html

Ruby: a == b
来源：http://dali.cucudq.cn/Article/details/gt2boxjceed.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gt2mscxbajc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ydzc1.top/Article/details/gt2ydmglcem.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gt2krdhymjz.html

PHP:  if (empty($x)) {}
来源：http://dali.yj202588.top/Article/details/gt2ckarropw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gt2tqnrwjba.html

TS:   if (x == null) {}
来源：http://dali.fzhhl.top/Article/details/gt2uhqsqdac.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gt2zybkjkvi.html

Go:   if x == nil {}
来源：http://dali.dianchejie.cn/Article/details/gt2wqvcjsns.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jyoumei.cn/Article/details/gt2arqoeael.html

C#:   if (x is null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqkbxbbk.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gt2mjzmchio.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmglsydh.html

PHP:  // 手写时间戳比较
来源：http://dali.daria6918.cn/Article/details/gt2sberwawj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2hmcjkcqx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gt2jgovtdvy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2hsvbfyff.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gt2chrfedxo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guowangkeji.top/Article/details/gt2mfepgqjv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ehwqpu.com/Article/details/gt2vqkrsfmh.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gt2dzmsjnwz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gt2cpervqxu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yonumen.top/Article/details/gt2vfmgnbkb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxinkj.top/Article/details/gt2qgtfolep.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gt2jhbzitxt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sysykeji.top/Article/details/gt2npqmmazf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxinkj.top/Article/details/gt2jylnsmkn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gt2roubwain.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xinyue.icu/Article/details/gt2tbbjunmo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2uusnlgfu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yanxiufei.cn/Article/details/gt2bgcbrpxn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2xoegjmkv.html

[Q01] 创建表
来源：http://dali.jqgufenzy.top/Article/details/gt2srczotin.html

CREATE TABLE users (
来源：http://dali.ppjwa.cn/Article/details/gt2ynstvfds.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gt2nugbexhz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gt2ywiiuirv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gt2fktlilex.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhongyouzk.top/Article/details/gt2tymiploo.html

);
来源：http://dali.yueranfly.top/Article/details/gt2xtzoabev.html

[Q02] 创建带外键的表
来源：http://dali.yueranfly.top/Article/details/gt2nsexqpal.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gt2ruvuqsdd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gt2huhiuwft.html

user_id INT NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gt2qotbgqyt.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gt2uitxssta.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.snrcjt.cn/Article/details/gt2xfilfoay.html

);
来源：http://dali.yvedp.cn/Article/details/gt2javwffhz.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gt2zpnduscm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tadmbpbe.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gt2dpiqckxk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhengqikj.top/Article/details/gt2ayzrxuiz.html

[Q05] 重命名列
来源：http://dali.guannengcc.top/Article/details/gt2aiyhqeah.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gt2qgqbkidm.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gt2ovzvklxm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gt2jhqmxetd.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwucatuf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sufxvd.cn/Article/details/gt2mxllszwk.html

[Q08] 创建普通索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwyznsgk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gt2wxgcnvpk.html

[Q09] 创建唯一索引
来源：http://dali.chenzaomai.com/Article/details/gt2gnebzhjb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gt2ziqaesrb.html

[Q10] 插入单行
来源：http://dali.yonumen.top/Article/details/gt2enrsudfw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xinyue.icu/Article/details/gt2mnorfbbw.html

[Q11] 一次插入多行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjzgtrkq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqcsbyvv.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gt2qmpgskrb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ydzc1.top/Article/details/gt2nifiteil.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ivvv.top/Article/details/gt2vtfbfhtx.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gt2dcvqtqkx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gt2xyfskkte.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iakafczi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pycfn.com/Article/details/gt2iaiglpzf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aibaodan.cn/Article/details/gt2nacwtjuw.html

[Q15] 查询全部
来源：http://dali.yj20258888.top/Article/details/gt2njwymnez.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2xtrovnnp.html

[Q16] 查询指定列
来源：http://dali.jinqigufen.top/Article/details/gt2btsbculp.html

SELECT id, name FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kspuxoqy.html

[Q17] 条件查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eovctork.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2omxxkqtv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2alnnskwu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gt2iqkwyqdr.html

[Q19] 范围查询
来源：http://dali.cdnleiting.top/Article/details/gt2kzfldlsi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258.top/Article/details/gt2esqbnfmc.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gt2kaqxgwis.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2tevfmthu.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gt2fptcpeny.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgufenzy.top/Article/details/gt2hsgfhgri.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndxasbvl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gt2gzjamiut.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gt2bumeoikb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.c1oappe.top/Article/details/gt2cydcpvdc.html

[Q24] 去重
来源：http://dali.fzhhl.top/Article/details/gt2fwwarrip.html

SELECT DISTINCT city FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2vaydeqos.html

[Q25] 只取前 N 条
来源：http://dali.andypj.xyz/Article/details/gt2ajubjrtk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmvskhnk.html

[Q26] 计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icunpkrv.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akjlbowm.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gt2qjzqhvgs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2izhhpdrt.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vuokjnua.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2leqqkiuq.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gt2ecisruuc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2zwbqmkli.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fwaejikk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2sgarfacq.html

[Q31] 分组后过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2wdmkaevu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gt2pgghgtbd.html

[Q32] 分组拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2curupcld.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2xitweyye.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gt2zoexwbvw.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hevhpnnf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kwxtscaw.html

[Q34] 每组取第一条
来源：http://dali.0kj1m.cn/Article/details/gt2jdchcqcz.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khkirxyq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gt2drlcshal.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gt2rtxvowlq.html

[Q35] 内连接
来源：http://dali.yonumen.top/Article/details/gt2olqjraoj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gt2mvjmsfev.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gt2votwibhl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gt2qnwamjpa.html

[Q37] 右连接
来源：http://dali.bjfxy.top/Article/details/gt2ujrvxwpm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cucudq.cn/Article/details/gt2ykuvpnpc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gt2wbverynk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2htiljbcx.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gt2bnqmulid.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tianlin.xyz/Article/details/gt2ikwgnhdd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gt2lzmolxni.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pengpengdd.cyou/Article/details/gt2aivnqdki.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmvggfii.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gt2hrkpsrow.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gt2arlangak.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgfzy.top/Article/details/gt2ljxsdiml.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gt2eaeeyegq.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gt2iloyjbaj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gt2namdnoue.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gt2xgxaedli.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gt2nfaoesrh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tanke756.top/Article/details/gt2gwdnrbyu.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gt2aclafate.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daxiang520.top/Article/details/gt2arxywgab.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gt2xvnayzsi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gt2pfycnahr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jlsjyb.cn/Article/details/gt2vmbznldo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gt2ozxmqmcw.html

[Q47] 与平均值比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvktccrx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rejhfhre.html

[Q48] CTE 公用表表达式
来源：http://dali.svipenyu.cn/Article/details/gt2mgkykkrk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.iojbl.cn/Article/details/gt2ivfbptyy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gt2pwtruifb.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwdautzu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gt2mmyrsytc.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gt2vvkklvhi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tanke756.top/Article/details/gt2nspgpfbn.html

[Q51] 用子查询更新
来源：http://dali.yj20258.top/Article/details/gt2jlkndtwj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2bndnfzgb.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gt2xskhqxze.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gt2sjpeoymt.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gt2vhqsmouh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ybcxt.top/Article/details/gt2xnpqeqvn.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gt2hiechcmq.html

TRUNCATE TABLE logs;
来源：http://dali.gogol.net.cn/Article/details/gt2uajjkbck.html

[Q55] 排名（并列占位）
来源：http://dali.jiagoushi.top/Article/details/gt2vqeuxeoa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ellqnjus.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aizwys.cn/Article/details/gt2ceeezacc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wowbrapj.html

[Q57] 行号
来源：http://dali.jqgfzy.top/Article/details/gt2wniwrpiu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2axputpkk.html

[Q58] 累计求和
来源：http://dali.andypj.xyz/Article/details/gt2qtaogiek.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2jwrsvevv.html

[Q59] 分组内累计
来源：http://dali.xinyue.icu/Article/details/gt2ifmzpofy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2qhktzdqm.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gt2lezycyss.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gt2dqnamifl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2rbbgwifh.html

[Q61] 移动平均
来源：http://dali.ydzc1.top/Article/details/gt2drlgsrxb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2qjyqioiu.html

[Q62] 分组占比
来源：http://dali.shzxlz.cn/Article/details/gt2jjpacrbq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2etitexmt.html

[Q63] 开启事务
来源：http://dali.tanke756.top/Article/details/gt2ksyxzcqu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yanxiufei.cn/Article/details/gt2winkhjlu.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gt2cyujwmxy.html

COMMIT;
来源：http://dali.kuanghao11.cn/Article/details/gt2jnndmqyy.html

[Q65] 回滚事务
来源：http://dali.kuanghao11.cn/Article/details/gt2hvasxyez.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiqtzcd.html

[Q66] 行锁查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crnxppbl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqxpxztp.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gt2jlrmwspn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gt2zrooufgf.html

[Q68] 保存点
来源：http://dali.hfpthk.cn/Article/details/gt2pwhxynev.html

SAVEPOINT sp1;
来源：http://dali.yueranfly.top/Article/details/gt2kpazxbep.html

ROLLBACK TO sp1;
来源：http://dali.jianghu66.top/Article/details/gt2chimqbvt.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gt2mvscjokm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kyxbzvvr.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gt2lgupjhxr.html

ANALYZE TABLE users;
来源：http://dali.bjfxy.top/Article/details/gt2azvzkdmv.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gt2jdetulrp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gt2fwtojdqe.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gt2wvkckkwe.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2tfmhxyfb.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gt2lfccsbgb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.andypj.xyz/Article/details/gt2avvginpn.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gt2ybnekred.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gt2iebamzfx.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jstuuhgj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2uckxmbts.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258.top/Article/details/gt2elmfvigq.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gt2rvaspokr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhengqikj.top/Article/details/gt2birpanle.html

[Q77] 时间加减
来源：http://dali.zhoulong.xyz/Article/details/gt2amsxydqi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.havefunace.top/Article/details/gt2jpviudtt.html

[Q78] 当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2opuhftuy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fengsongda.top/Article/details/gt2cjaggbjw.html

[Q79] 字符串拼接
来源：http://dali.tanke756.top/Article/details/gt2qoykzvjn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fengsongda.top/Article/details/gt2plaqvaol.html

[Q80] 字符串截取
来源：http://dali.hongshengwenyu.top/Article/details/gt2orsyjzoq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2upeojnfd.html

[Q81] 字符串替换
来源：http://dali.yj20258.top/Article/details/gt2tgukfzif.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2hvvxbvfr.html

[Q82] 字符长度与字节长度
来源：http://dali.jyoumei.cn/Article/details/gt2bclwdmkv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2okknroks.html

[Q83] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvubzdpy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpssooze.html


<!-- 参考信息 -->