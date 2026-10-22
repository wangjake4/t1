代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuxming.cn/Article/details/gt2ltxtimdk.html

[O03] 加锁保护共享数据
来源：http://dali.hysaishi.cn/Article/details/gt2zzxpjuzv.html

Py:   with lock: shared += 1
来源：http://dali.jqgfzy.top/Article/details/gt2ojdbbsjr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gt2nxlgpmus.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gt2qjeumudm.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gt2ksgqgegw.html

Java: synchronized (this) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gt2lciqtgjx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxinkj.top/Article/details/gt2fjygavnv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.kuanghao11.cn/Article/details/gt2nrxsgykz.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gt2wcbxadfe.html

[O04] 定义异步函数并等待
来源：http://dali.jyoumei.cn/Article/details/gt2nvofvtoo.html

Py:   async def f():⏎    await g()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pouucjmf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cdnleiting.top/Article/details/gt2yaqknitw.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gt2qmfolyjv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gt2byjyqwnb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qvidrjaj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenlongwang.top/Article/details/gt2wbirkixf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gt2vvvzxznm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2luclejvv.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgufenzy.top/Article/details/gt2mfeftkww.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aibaodan.cn/Article/details/gt2inuyjspu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cqqwz.cn/Article/details/gt2zffpkvoo.html

JS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2runvdfvz.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2cameelyx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hammf.cn/Article/details/gt2xswppyun.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xinyue.icu/Article/details/gt2qxshijmt.html

Ruby: threads.map(&:join)
来源：http://dali.chenlongwang.top/Article/details/gt2uglqyskk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ydzc1.top/Article/details/gt2foviiaxb.html

[O06] 使用进程池
来源：http://dali.aizwys.cn/Article/details/gt2yjrriauk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhoulong.xyz/Article/details/gt2bosexacm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2dezfsndi.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2aexrivvk.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gt2dbptkxzb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gt2nmblkccj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuanzhike.top/Article/details/gt2rjccanji.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gt2odwufodv.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gt2kjlpqldf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2rnpjzewd.html

P. 常用工具函数
来源：http://dali.yanxiufei.cn/Article/details/gt2jxniyfcs.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2zigtmheu.html

[P01] 生成 UUID
来源：http://dali.xuanzx.com/Article/details/gt2ohvsohty.html

Py:   str(uuid.uuid4())
来源：http://dali.zhiwuduotai.top/Article/details/gt2nncyeicq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owzkmxxg.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2bfmiwwlq.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2twthxvdj.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gt2jdxzskwk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnxiangtu.top/Article/details/gt2tnnpebwo.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gt2alulwpwx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ydzc1.top/Article/details/gt2yuhyatoc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.bjfxy.top/Article/details/gt2vhxyiqep.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yongpay.top/Article/details/gt2yegalknr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangdashe.top/Article/details/gt2kutqraln.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxinkj.top/Article/details/gt2edufvtlo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gt2fqwgsrjx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2gjjylpqt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gt2adxtjlel.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gt2nwdyzagm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.kuanghao11.cn/Article/details/gt2sohijwvs.html

[P03] 生成短随机字符串
来源：http://dali.jianghu66.top/Article/details/gt2nmqkhefl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.kuanghao11.cn/Article/details/gt2pkgowgcc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigfzy.top/Article/details/gt2ytoajtnv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gt2kxofzpft.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2iewsntbd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yongpay.top/Article/details/gt2pnysnwnc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvbwjnax.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sysykeji.top/Article/details/gt2qknfvdqr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gt2mwzjvwel.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gt2rqjlcask.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gt2bklfbogw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqzsycoi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gt2ovbhnwxt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gt2kyadqctl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fyboivdv.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gt2fqzrrmpt.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gt2olqsefyl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gt2rguaqykn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cucudq.cn/Article/details/gt2tzjmrkib.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gt2jzhonbwi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cheryme.top/Article/details/gt2jbqmtqxa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gt2ptslfhap.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gt2jtdaulds.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdtngqv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2simfypcv.html

Ruby: a == b
来源：http://dali.fengsongda.top/Article/details/gt2ktysprah.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gt2aqjwltdp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pycfn.com/Article/details/gt2lhxzfwiy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sysykeji.top/Article/details/gt2tdoxioed.html

PHP:  if (empty($x)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvbniscp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.9152youxi.cn/Article/details/gt2wxsgnsns.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfqqyxpl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gt2vninlvfy.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gt2bhojqjzq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gt2cimoesou.html

C#:   if (x is null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvzvrcvs.html

[P07] 防抖与节流
来源：http://dali.yj20258888.top/Article/details/gt2xtxvkhqh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gt2grplxzrp.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gt2dvqvkbkt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gt2pzgbjuvl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gt2pokjtacp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xziqi.cn/Article/details/gt2bmwsfepj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gt2bqccejjv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gt2umjozzjn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gt2qdqtzmnt.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gt2zxsgypgf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfqacpzz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gt2npoqnynj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhiwuduotai.top/Article/details/gt2twrlgkix.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gt2xxajkabt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gt2vtidbnco.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gt2lvywnilb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xziqi.cn/Article/details/gt2edsuenjz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gt2wdidyhpi.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2huoceuhr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwnmgqnb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2wxflrlqf.html

[Q01] 创建表
来源：http://dali.aizwys.cn/Article/details/gt2kqyaejdz.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gt2uvvlqfcz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gt2yoqbigik.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gt2dhzgyehd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.vqdsnc.cn/Article/details/gt2ykkytrpl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gogol.net.cn/Article/details/gt2hmgwfmre.html

);
来源：http://dali.yuxming.cn/Article/details/gt2odzgbwae.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gt2zcurrmzo.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gt2ounwucoo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gt2ttnhowzy.html

user_id INT NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gt2ehnautbs.html

amount DECIMAL(10, 2),
来源：http://dali.tianlin.xyz/Article/details/gt2cbgotxec.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jiagoushi.top/Article/details/gt2mvvmrofs.html

);
来源：http://dali.yj20258888.top/Article/details/gt2zlnaykxh.html

[Q03] 增加列
来源：http://dali.mhx1999.top/Article/details/gt2mkllbqoh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yvedp.cn/Article/details/gt2whhxmtjd.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unegcdvi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gt2flizbiuv.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gt2jkvgktpk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sysykeji.top/Article/details/gt2ovcuzcee.html

[Q06] 删除列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzrnjcvh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxbfcrww.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gt2ypuataqq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shzxlz.cn/Article/details/gt2llxfzpui.html

[Q08] 创建普通索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tazkupvx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gt2pgyjifxe.html

[Q09] 创建唯一索引
来源：http://dali.cucudq.cn/Article/details/gt2fvevcndu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gt2hjbmkcgm.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gt2qatvrdhg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgfzy.top/Article/details/gt2gscfejjj.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gt2wypckixr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jianghu66.top/Article/details/gt2zcgkjnrz.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigufen.top/Article/details/gt2zzdeknia.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hfpthk.cn/Article/details/gt2ahoylcik.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2noccjgfp.html

[Q13] 忽略重复插入
来源：http://dali.pengpengdd.cyou/Article/details/gt2salupshk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gt2yewsktpt.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gt2qfqkurtl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.smart0.xyz/Article/details/gt2rltmgmqi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tidncxdp.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gt2ojboutdd.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gt2xoatqjes.html

[Q16] 查询指定列
来源：http://dali.zhoulong.xyz/Article/details/gt2xcxmzhtf.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2qijmjmpv.html

[Q17] 条件查询
来源：http://dali.c1oappe.top/Article/details/gt2lxtqhejo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxrvsrci.html

[Q18] 模糊匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvjnkzmp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bnofayby.html

[Q19] 范围查询
来源：http://dali.hammf.cn/Article/details/gt2ssapjgjr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenlongwang.top/Article/details/gt2nkkmajkk.html

[Q20] IN 列表
来源：http://dali.9152youxi.cn/Article/details/gt2koefhljm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2azkgspsh.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gt2pkwcgzgh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gt2meblosor.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cofvldya.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hivfkeua.html

[Q23] 分页
来源：http://dali.dashuyun.cn/Article/details/gt2rohegana.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.guannengcc.top/Article/details/gt2qrzhufer.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gt2inodzkdl.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2ztpfjadx.html

[Q25] 只取前 N 条
来源：http://dali.aibaodan.cn/Article/details/gt2vvsouatj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gt2wkfsritr.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gt2mozdawkm.html

SELECT COUNT(*) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2cpsrlkht.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ekgvmkwy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2muutqwjl.html

[Q28] 求和与平均
来源：http://dali.hnxiangtu.top/Article/details/gt2ixwgycgh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2vxtemyvt.html

[Q29] 最大最小值
来源：http://dali.hysaishi.cn/Article/details/gt2levqjsav.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2xotswkig.html

[Q30] 分组统计
来源：http://dali.zhiwuduotai.top/Article/details/gt2kicbzlsi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gt2apihlekd.html

[Q31] 分组后过滤
来源：http://dali.shuidangran.top/Article/details/gt2fbodznqx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hammf.cn/Article/details/gt2blxlnemu.html

[Q32] 分组拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gt2gopyuqzb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gt2pprkhmvj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gt2nqljojdk.html

[Q33] 多列分组
来源：http://dali.jyoumei.cn/Article/details/gt2vdbcsyas.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.kuanghao11.cn/Article/details/gt2llcugzng.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gt2lbmwxpre.html

SELECT * FROM (
来源：http://dali.quarkkingdee.top/Article/details/gt2whtywjoe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yanxiufei.cn/Article/details/gt2mcbrhosm.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2dkpoivfz.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gt2kdfrzmnc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gt2sishrfea.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gt2wltkqeqy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gt2ijufxmks.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gt2aadoovgh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.0kj1m.cn/Article/details/gt2zwvixqti.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnocgefh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sufxvd.cn/Article/details/gt2hmjdxvyh.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zczjdexd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yonumen.top/Article/details/gt2ekxjvjbl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gt2pgqghfoo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gt2bijmksmx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gt2sajbdcnn.html

[Q41] 多表连接
来源：http://dali.jqgfzy.top/Article/details/gt2wqoyatge.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gt2aqqgepkz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ivvv.top/Article/details/gt2aosxvzbb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gt2yqnyhxpl.html

[Q42] 连接条件附加过滤
来源：http://dali.hnqzz.top/Article/details/gt2ukgapesc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aibaodan.cn/Article/details/gt2jmuyqmlq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfjgfrpj.html

[Q43] 标量子查询
来源：http://dali.chenzaomai.com/Article/details/gt2sufoaoju.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shzxlz.cn/Article/details/gt2dibowkox.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gt2vwdvptdu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gt2myywozgi.html

[Q45] EXISTS 判断存在
来源：http://dali.ydzc1.top/Article/details/gt2cytpddhv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gt2owjevwfn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gt2bhqzuhlc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmtvzumb.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gt2akizmcxb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xylfe.cn/Article/details/gt2qazcrnbo.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhnhqkpv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nwbrower.top/Article/details/gt2lldemfbk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkmogwvv.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gt2bzkqklwz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gt2kgtahuch.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gt2ugiuieos.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pycfn.com/Article/details/gt2ncynhott.html

[Q51] 用子查询更新
来源：http://dali.jqgufenzy.top/Article/details/gt2yyfgfuut.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2hhibhmeb.html

[Q52] 删除指定行
来源：http://dali.quarkkingdee.top/Article/details/gt2otkdjkof.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gt2pgzhvbhw.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gt2danbzczc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gt2azfunsrx.html

[Q54] 清空表
来源：http://dali.cashguo.top/Article/details/gt2mwbqealo.html

TRUNCATE TABLE logs;
来源：http://dali.zhengqikj.top/Article/details/gt2bxbqglvz.html

[Q55] 排名（并列占位）
来源：http://dali.jlsjyb.cn/Article/details/gt2bxbgrzlg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gt2yntqezkw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhengqikj.top/Article/details/gt2wlflyadr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gt2bljnmlaq.html

[Q57] 行号
来源：http://dali.xylfe.cn/Article/details/gt2pwubhxws.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2akzrskxk.html

[Q58] 累计求和
来源：http://dali.hywenlv.cn/Article/details/gt2pcdbloxw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gt2jvnblouj.html

[Q59] 分组内累计
来源：http://dali.shzxlz.cn/Article/details/gt2amycfgvr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2ecngmlur.html

[Q60] 取上一行 / 下一行
来源：http://dali.kuanghao11.cn/Article/details/gt2phvcuqce.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhongyouzk.top/Article/details/gt2ijozzsev.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2wuflulep.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gt2rabvybrs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2obnoudjh.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gt2udfnsaqu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2vkjaqqby.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gt2wlmvujkk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gt2ukjztvrs.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gt2wzydcwhj.html

COMMIT;
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzlfdrvj.html

[Q65] 回滚事务
来源：http://dali.mhx1999.top/Article/details/gt2zwgdaxec.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gt2gntxcccd.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qisxbrcv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbungwis.html

[Q67] 设置隔离级别
来源：http://dali.nwbrower.top/Article/details/gt2stcztidl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gt2pdwdyble.html

[Q68] 保存点
来源：http://dali.hywenlv.cn/Article/details/gt2rkipugts.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gt2qgqkngzj.html

ROLLBACK TO sp1;
来源：http://dali.shuidangran.top/Article/details/gt2tewlriqm.html

[Q69] 查看执行计划
来源：http://dali.gaohongyu789.top/Article/details/gt2ambnxmbr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gt2hbtciucy.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gt2wabywatr.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gt2kbhperkh.html

[Q71] 查看建表语句
来源：http://dali.fzhhl.top/Article/details/gt2ulpipudd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gt2mhugayvj.html

[Q72] 查看索引
来源：http://dali.yanxiufei.cn/Article/details/gt2ftwccufb.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2pktinxzo.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gt2wsjdcdbw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gt2ksiqdjbs.html

[Q74] 强制使用索引
来源：http://dali.pycfn.com/Article/details/gt2esgzxcgi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gt2owgwwggm.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2iuyjjpen.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2evbuujov.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cashguo.top/Article/details/gt2aettmukx.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dorkkjxa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gt2ykrcbziz.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gt2qltpldfm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gt2xaytnimd.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gt2unercdlh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gt2qxyftkkt.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gt2stajxdzm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gt2efqiwbnc.html

[Q80] 字符串截取
来源：http://dali.jlsjyb.cn/Article/details/gt2fusgtixx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2esohwffx.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gt2debkrxpd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2asolntgu.html


<!-- 参考信息 -->