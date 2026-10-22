代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgufenzy.top/Article/details/gt2wkcxhcum.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gt2xrrqyjpw.html

Java: synchronized (this) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gt2gsiwlrco.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnqzz.top/Article/details/gt2odkddtdx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhengqikj.top/Article/details/gt2cttjufjj.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2tmyhhhrw.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gt2cldayrdw.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gt2gwtmtrmh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.havefunace.top/Article/details/gt2dlrryouu.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gt2fymubrov.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xinyue.icu/Article/details/gt2wofsslgn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxuanxn.top/Article/details/gt2oiufflrn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.quarkkingdee.top/Article/details/gt2ofkuwnnv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sxryk.cn/Article/details/gt2djslgnsq.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gt2iwsjmoda.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gt2vhwfefvy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jianghu66.top/Article/details/gt2nfubpwzy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hgmyaqbp.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2zwnlnmwh.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2gddznwsr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gt2qpaavifl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.kuanghao11.cn/Article/details/gt2sapoutoi.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gt2unkdxrpm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cdnleiting.top/Article/details/gt2ciftujob.html

[O06] 使用进程池
来源：http://dali.redwolf501.top/Article/details/gt2mukhfumv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuetiantiany.cn/Article/details/gt2frjkphnl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.svipenyu.cn/Article/details/gt2eojpvpah.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gt2euehrgza.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gt2izsynzcc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigfzy.top/Article/details/gt2ewocdvrq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tanke756.top/Article/details/gt2bkpjipgl.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gt2mgkaoydq.html

C#:   Parallel.For
来源：http://dali.yueranfly.top/Article/details/gt2jlvmiorm.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2gfgxcqmx.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gt2wdglsdfz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2fuxjtzxs.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxppmrv.html

Py:   str(uuid.uuid4())
来源：http://dali.xylfe.cn/Article/details/gt2bdpgirlm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gt2mhibcdia.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2lyblhllx.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gt2tqfdebnt.html

Java: UUID.randomUUID().toString()
来源：http://dali.yonumen.top/Article/details/gt2xsmcfqya.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnqzz.top/Article/details/gt2afdphjny.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejeeuvys.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.0kj1m.cn/Article/details/gt2innafiit.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afaknbop.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gt2cftezszh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2xbrmdkss.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gt2oqlxeiby.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gt2gyfanjdy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2bbrtxxgf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hywenlv.cn/Article/details/gt2mhhtjluc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2seugqjvb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gt2mbzcosrz.html

[P03] 生成短随机字符串
来源：http://dali.shuidangran.top/Article/details/gt2upciqpyv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gt2cajmxtwk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ydzc1.top/Article/details/gt2wldvskee.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gt2flelxmbv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gt2ybdgfvxe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqomfptc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gt2kzhoprfr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuanzhike.top/Article/details/gt2lxpdguha.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gt2ijgcymwi.html

[P04] 求长度
来源：http://dali.cucudq.cn/Article/details/gt2xhbdfzou.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gogol.net.cn/Article/details/gt2mfykhusu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2oaemoaxg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gt2scaadwgm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gt2rgiyysfd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gt2iuktpixx.html

Go:   len(arr);  len(m)
来源：http://dali.316326.xyz/Article/details/gt2fzaoqbve.html

Ruby: x.length;  x.size
来源：http://dali.dianchejie.cn/Article/details/gt2jprvxtux.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gt2blofnfml.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hammf.cn/Article/details/gt2cgsqufso.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gt2absmvtqs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tianlin.xyz/Article/details/gt2idpbrrnn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnqzz.top/Article/details/gt2rtyepgvo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gt2entuvkwe.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cashguo.top/Article/details/gt2xbmtwjpo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2szgbcskh.html

Ruby: a == b
来源：http://dali.mhx1999.top/Article/details/gt2rwwbista.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gt2olgftpqe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jiagoushi.top/Article/details/gt2wjxzbsyv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.havefunace.top/Article/details/gt2xlbofsjf.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgfzy.top/Article/details/gt2cgizkwgi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cucudq.cn/Article/details/gt2ihkodpiq.html

TS:   if (x == null) {}
来源：http://dali.yonumen.top/Article/details/gt2oxmoifpc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gt2bbeeeymn.html

Go:   if x == nil {}
来源：http://dali.hnqzz.top/Article/details/gt2hyzdmzzs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jlsjyb.cn/Article/details/gt2pvapgneb.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btuyzlor.html

[P07] 防抖与节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vuxdcbfz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ydzc1.top/Article/details/gt2pdjmnnjc.html

PHP:  // 手写时间戳比较
来源：http://dali.svipenyu.cn/Article/details/gt2zmbbkkyh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gt2smsikpuz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gt2otzooifq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangdashe.top/Article/details/gt2tcubfvcr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.bjfxy.top/Article/details/gt2vorezpki.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shzxlz.cn/Article/details/gt2stwflryb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.havefunace.top/Article/details/gt2vmabsfpy.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdtxdctc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gt2bkakhgmf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.svipenyu.cn/Article/details/gt2nxaopqbz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zycfv.cn/Article/details/gt2rlouzsvs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2keuqrpok.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigufen.top/Article/details/gt2zzzuowky.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yangfankeji.com/Article/details/gt2xpnyzwpo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yanxiufei.cn/Article/details/gt2qdgjbugy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.svipenyu.cn/Article/details/gt2vfxljqms.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2xuclzfih.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gzhubu.top/Article/details/gt2wxpeuxcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlkdrrt.html

[Q01] 创建表
来源：http://dali.ivvv.top/Article/details/gt2bimehexm.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gt2lhcmsgwd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gt2vtnapskd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gt2zucgyath.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gogol.net.cn/Article/details/gt2mswwphvi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zycfv.cn/Article/details/gt2mbkpxowv.html

);
来源：http://dali.dianchejie.cn/Article/details/gt2vyuxqpal.html

[Q02] 创建带外键的表
来源：http://dali.yanxiufei.cn/Article/details/gt2bflfxtrx.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gt2hkzqhkot.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gt2nhxblygj.html

user_id INT NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gt2qdrgtfpx.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gt2stpoafzy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gt2jgowmknh.html

);
来源：http://dali.xuanzx.com/Article/details/gt2mapfenqq.html

[Q03] 增加列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rutinbdy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guannengcc.top/Article/details/gt2odgpvlbb.html

[Q04] 修改列类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2euhweboe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gt2nzzeomdu.html

[Q05] 重命名列
来源：http://dali.yj20258.top/Article/details/gt2ryhxggsk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tanke756.top/Article/details/gt2gdhwusri.html

[Q06] 删除列
来源：http://dali.jianghu66.top/Article/details/gt2hdrqslnb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gt2ofglujaf.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gt2eqrqwvlg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2moefegvh.html

[Q08] 创建普通索引
来源：http://dali.andypj.xyz/Article/details/gt2czyrsmif.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gt2tlfupddn.html

[Q09] 创建唯一索引
来源：http://dali.cashguo.top/Article/details/gt2tqieaiuv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gt2edkehfsg.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2boznbobp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ephhawcr.html

[Q11] 一次插入多行
来源：http://dali.316326.xyz/Article/details/gt2hpbvalvy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2hfxrjutz.html

[Q12] 插入后取自增 ID
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wfxdfajr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tian-w.cn/Article/details/gt2pfogfpml.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangdashe.top/Article/details/gt2pfgbjvlw.html

[Q13] 忽略重复插入
来源：http://dali.ppjwa.cn/Article/details/gt2xzqmhpvn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gt2honhxawd.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gt2kbgzbwdt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daxiang520.top/Article/details/gt2yvjofvyi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.vqdsnc.cn/Article/details/gt2qsynmkde.html

[Q15] 查询全部
来源：http://dali.ppjwa.cn/Article/details/gt2svdnppdv.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivcwgzsd.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gt2jwldtrpl.html

SELECT id, name FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mejssklt.html

[Q17] 条件查询
来源：http://dali.xylfe.cn/Article/details/gt2bnurfwzf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yueranfly.top/Article/details/gt2lgqilesk.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2azuwyqho.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangdashe.top/Article/details/gt2bltlvqzr.html

[Q19] 范围查询
来源：http://dali.quarkkingdee.top/Article/details/gt2aupoxvgp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gt2bbbvbbkh.html

[Q20] IN 列表
来源：http://dali.yj20258.top/Article/details/gt2opfcbzrm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2kkfbcxlw.html

[Q21] 空值判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ggmcgeoe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daria6918.cn/Article/details/gt2yrvvjqux.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gt2redwtwmj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhznqjwq.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gt2dpshbydb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gt2boknacou.html

[Q24] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gt2bznvnrge.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2lxirhyua.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gt2kcnkbbwd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gt2hwydbqps.html

[Q26] 计数
来源：http://dali.xinyue.icu/Article/details/gt2raytxybi.html

SELECT COUNT(*) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2usahgfyu.html

[Q27] 条件计数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftsptfqw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmtpqqme.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cklhppsy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2frkemuiq.html

[Q29] 最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gt2esvzaodn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vumpssni.html

[Q30] 分组统计
来源：http://dali.sweek.top/Article/details/gt2ultmrkuq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gt2mumafgda.html

[Q31] 分组后过滤
来源：http://dali.dashuyun.cn/Article/details/gt2nhxmtrmy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhlexsho.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gt2jpodvoph.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2lskkxiar.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwdaokpg.html

[Q33] 多列分组
来源：http://dali.birdmap.top/Article/details/gt2rmbayxwg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gt2evmrtkui.html

[Q34] 每组取第一条
来源：http://dali.xuanzx.com/Article/details/gt2pbhjwbcn.html

SELECT * FROM (
来源：http://dali.xziqi.cn/Article/details/gt2pyqxcnlx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xziqi.cn/Article/details/gt2umagutio.html

) t WHERE rn = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2rfgamyvp.html

[Q35] 内连接
来源：http://dali.xziqi.cn/Article/details/gt2bweyeqou.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2buhfjalu.html

[Q36] 左连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2woarqqcy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2clyfdmpk.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gt2jzbllovi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gt2fcgeizlg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hongshengwenyu.top/Article/details/gt2pidpwqsp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxitcnpt.html

[Q39] 自连接（查上下级）
来源：http://dali.tianlin.xyz/Article/details/gt2fcujywdy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shangyingyoupin.top/Article/details/gt2zuhncrhx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2shuuityo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gt2fyidjzfm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gt2xqhylokt.html

[Q41] 多表连接
来源：http://dali.yanxiufei.cn/Article/details/gt2ebbvlwet.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gt2swlngctx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gt2jgunimsg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfsaeyne.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258888.top/Article/details/gt2wvryjyiz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daxiang520.top/Article/details/gt2mwivmmew.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jlsjyb.cn/Article/details/gt2xojrqaux.html

[Q43] 标量子查询
来源：http://dali.zhoulong.xyz/Article/details/gt2wjvpcawv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gt2fevqyohx.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gt2lowgwiuh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gt2htptawzl.html

[Q45] EXISTS 判断存在
来源：http://dali.yueranfly.top/Article/details/gt2phxrmikj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gt2gbvrkltj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xziqi.cn/Article/details/gt2jkdlnsbc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gt2yocowoph.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqdpdmfe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.redwolf501.top/Article/details/gt2cwcfdrit.html

[Q48] CTE 公用表表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpjkjjvr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nwbrower.top/Article/details/gt2iyxwywet.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjwckeqn.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gt2scoqjpfa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2axldfamp.html

[Q50] 批量更新
来源：http://dali.gotoacloud.top/Article/details/gt2tvaplnnp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj202588.top/Article/details/gt2yoldvrmu.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gt2wemziwnj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2wgohzbzp.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gt2xmjyebmx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gt2vrbfgnax.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gt2fjdfmool.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gt2ebbhsivk.html

[Q54] 清空表
来源：http://dali.dashuyun.cn/Article/details/gt2ptjkxogt.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gt2suhxuptd.html

[Q55] 排名（并列占位）
来源：http://dali.dianchejie.cn/Article/details/gt2nwlcdxbh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.smart0.xyz/Article/details/gt2xxmhyrrx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.kuanghao11.cn/Article/details/gt2vpeibpiu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guannengcc.top/Article/details/gt2lyiegwkz.html

[Q57] 行号
来源：http://dali.dashuyun.cn/Article/details/gt2rrqyvtkn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2udlblxdf.html

[Q58] 累计求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oltfbpxk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2xkkfzdsi.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gt2dcqlvdku.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2ebizxeyl.html

[Q60] 取上一行 / 下一行
来源：http://dali.jyoumei.cn/Article/details/gt2pmjxivrr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangdashe.top/Article/details/gt2lzzqpxab.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2xehxzzgz.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2klcoxjgd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2tymqpuyx.html

[Q62] 分组占比
来源：http://dali.vqdsnc.cn/Article/details/gt2enpvztnz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2vyuoatho.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gt2uoxowpid.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gt2amfvwdyw.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gt2gocpniwb.html

COMMIT;
来源：http://dali.ppjwa.cn/Article/details/gt2bdblnxsc.html

[Q65] 回滚事务
来源：http://dali.jinqigufen.top/Article/details/gt2fixoynxo.html

ROLLBACK;
来源：http://dali.gaohongyu789.top/Article/details/gt2euxlbjsi.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gt2luwaxppp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gzhubu.top/Article/details/gt2uxvzdppl.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gt2rfuiaftp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gt2tulxgvjc.html

[Q68] 保存点
来源：http://dali.hnxiangtu.top/Article/details/gt2zuydxdoo.html

SAVEPOINT sp1;
来源：http://dali.guowangkeji.top/Article/details/gt2esbtqazt.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gt2yrovqcup.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gt2xkywdntk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gt2exqsqdqa.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bgjiyctx.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gt2zzzzhcna.html

[Q71] 查看建表语句
来源：http://dali.gotoacloud.top/Article/details/gt2qzepzimv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.quarkkingdee.top/Article/details/gt2dyprbaet.html

[Q72] 查看索引
来源：http://dali.nwbrower.top/Article/details/gt2cckzswoi.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2sycbfuat.html

[Q73] 查看表状态
来源：http://dali.guannengcc.top/Article/details/gt2brymxisc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gt2invpudna.html

[Q74] 强制使用索引
来源：http://dali.ybcxt.top/Article/details/gt2zzkagndl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gt2wkxlrwoo.html

[Q75] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gt2fvhdxmpd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kkszroqw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yueranfly.top/Article/details/gt2spqdiqoe.html

[Q76] 按天统计
来源：http://dali.aibaodan.cn/Article/details/gt2ootnzqzl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zycfv.cn/Article/details/gt2subffywj.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sohxkxze.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cashguo.top/Article/details/gt2fwzkzkfc.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2toqqwszs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shzxlz.cn/Article/details/gt2vqsqcudl.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gt2lnnfprkr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xylfe.cn/Article/details/gt2vclrbncf.html

[Q80] 字符串截取
来源：http://dali.iojbl.cn/Article/details/gt2fbenwlmp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2pwmbpfmq.html

[Q81] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gt2exhxwxaq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2atfkwnlm.html

[Q82] 字符长度与字节长度
来源：http://dali.ivvv.top/Article/details/gt2xfjvjojs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2bcfcerkj.html

[Q83] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gt2ruqzntmw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2yeodbkjv.html


<!-- 参考信息 -->