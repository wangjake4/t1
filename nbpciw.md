代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gt2drvaxvul.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gt2hfxkrugo.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gt2qbqfgvny.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guannengcc.top/Article/details/gt2txlvoeay.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gt2bwgivuuu.html

C#:   lock (gate) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gt2vtdwowun.html

[O04] 定义异步函数并等待
来源：http://dali.aizwys.cn/Article/details/gt2invbzorc.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258888.top/Article/details/gt2lwmhumxn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gt2pmpujbeg.html

JS:   async function f() { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ujnzrytm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xinyue.icu/Article/details/gt2kvmfxkqd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpzbxkzm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daria6918.cn/Article/details/gt2uptvqzrk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gt2hdpcwgem.html

C#:   async Task F() { await G(); }
来源：http://dali.shuidangran.top/Article/details/gt2boasslwp.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigufen.top/Article/details/gt2fnejigmv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gt2xihgfiow.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gt2zydjucps.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gt2zihtyjkz.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gt2ajinbttp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tianlin.xyz/Article/details/gt2ombkugnm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gt2welyemns.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gt2utogorii.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwtphfld.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcvbgzuq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gt2jyytdaqx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gt2zuvpdteh.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gt2vapuiqyq.html

TS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqbmhima.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqiuiksk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gt2aqlbbkwi.html

Ruby: // fork 块
来源：http://dali.xylfe.cn/Article/details/gt2uazfeufe.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gt2iqbavzic.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2qeyasfoa.html

P. 常用工具函数
来源：http://dali.sxryk.cn/Article/details/gt2nrbvkoei.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2owlajazy.html

[P01] 生成 UUID
来源：http://dali.tian-w.cn/Article/details/gt2qskbiiye.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gt2gwstghka.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvzuqyzm.html

JS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gt2fhkarsqs.html

TS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gt2rtwegjnx.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2oncwmuek.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gt2cylfvjrt.html

Ruby: SecureRandom.uuid
来源：http://dali.zdqjudy.top/Article/details/gt2qejrshps.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2krlsqbzf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ppjwa.cn/Article/details/gt2rsoireha.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymhludba.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfleepuc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gt2jdrkttgv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.quarkkingdee.top/Article/details/gt2tifwsdma.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.haohaochexian.top/Article/details/gt2uuioolyz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258888.top/Article/details/gt2youforms.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gt2kyqbnllu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tianlin.xyz/Article/details/gt2chwwkhvu.html

[P03] 生成短随机字符串
来源：http://dali.cucudq.cn/Article/details/gt2sopstong.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aibaodan.cn/Article/details/gt2avqpjkpb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhongyouzk.top/Article/details/gt2wrsebohg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gt2wpbmbcwk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbootumn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhbcyapv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gt2zrsjtclv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2raplqcvk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shangyingyoupin.top/Article/details/gt2xsixhljn.html

[P04] 求长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2xsizbteo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xdlfgedu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2mmujaabm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gt2idgserpa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gt2icjfkogq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jiagoushi.top/Article/details/gt2gzpmvvft.html

Go:   len(arr);  len(m)
来源：http://dali.shuidangran.top/Article/details/gt2sguupuoe.html

Ruby: x.length;  x.size
来源：http://dali.havefunace.top/Article/details/gt2gtmfjobe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.c1oappe.top/Article/details/gt2ywmkoule.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgufenzy.top/Article/details/gt2qibkbhbz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2lsvvvteg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gogol.net.cn/Article/details/gt2esnceusd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sysykeji.top/Article/details/gt2exeoiuka.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gt2lmruyynm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guowangkeji.top/Article/details/gt2ldcaqcue.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cqqwz.cn/Article/details/gt2yptpuyth.html

Ruby: a == b
来源：http://dali.sweek.top/Article/details/gt2wyrmfyup.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gt2raelbkxa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.birdmap.top/Article/details/gt2otnadtlr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuetiantiany.cn/Article/details/gt2qehjiroa.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gt2gxqpirsm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gt2xgasxgmx.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gt2bhyadamc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gt2unjmeixw.html

Go:   if x == nil {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2oeiyoyru.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gt2bwqhsmsb.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrxhhyzg.html

[P07] 防抖与节流
来源：http://dali.daxiang520.top/Article/details/gt2dzuxykre.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gt2eeavhtyq.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgzmwkzd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwfyjxki.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2zyacvmvg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gt2qfzasrxz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cdnleiting.top/Article/details/gt2rdvjxaaw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258.top/Article/details/gt2xhakqnpd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuxming.cn/Article/details/gt2wdfvipre.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gt2jvcgewjc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.iojbl.cn/Article/details/gt2ainsezur.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gt2ankuoqaw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvnoppcl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdkifkds.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sweek.top/Article/details/gt2zittdouu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gt2rhenxyaj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gzhubu.top/Article/details/gt2nnocxgwg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqormvlv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2dwujxoou.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gt2vinlumwl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2zihqsyhi.html

[Q01] 创建表
来源：http://dali.cdnleiting.top/Article/details/gt2grawkjem.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gt2yugsczse.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2ipxhrebq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gt2erfmolwm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jyoumei.cn/Article/details/gt2qnpxcyaz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gt2lmbzrauz.html

);
来源：http://dali.tanke756.top/Article/details/gt2fmjjytmf.html

[Q02] 创建带外键的表
来源：http://dali.fzhhl.top/Article/details/gt2rtaykhzf.html

CREATE TABLE orders (
来源：http://dali.meibo888.top/Article/details/gt2rlpyhcdt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gt2zccpgxvm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtxlrbm.html

amount DECIMAL(10, 2),
来源：http://dali.guowangkeji.top/Article/details/gt2zgmrfjjh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yongpay.top/Article/details/gt2krzcqabd.html

);
来源：http://dali.hnxiangtu.top/Article/details/gt2bgbxokzw.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gt2ljmowpct.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigufen.top/Article/details/gt2momvbprw.html

[Q04] 修改列类型
来源：http://dali.c1oappe.top/Article/details/gt2duksrxwy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuxming.cn/Article/details/gt2jodqgfcc.html

[Q05] 重命名列
来源：http://dali.cucudq.cn/Article/details/gt2bxwtqctl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ivvv.top/Article/details/gt2tiahzzlk.html

[Q06] 删除列
来源：http://dali.xinyue.icu/Article/details/gt2ywoxeoxf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuetiantiany.cn/Article/details/gt2nevwgpel.html

[Q07] 删除表
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqfzsmzp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gt2uwwosden.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gt2fjpkvzuz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gt2qazewwao.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gt2otpqovlc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vfviztrd.html

[Q10] 插入单行
来源：http://dali.gotoacloud.top/Article/details/gt2ivnnbiuz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gt2cwfyazhj.html

[Q11] 一次插入多行
来源：http://dali.fengsongda.top/Article/details/gt2qhjhuanf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gt2aijiamvm.html

[Q12] 插入后取自增 ID
来源：http://dali.hnxiangtu.top/Article/details/gt2igbeavft.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.redwolf501.top/Article/details/gt2bzapthfk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gt2wexgvcty.html

[Q13] 忽略重复插入
来源：http://dali.meibo888.top/Article/details/gt2yjlfocvn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shuidangran.top/Article/details/gt2zaochcvp.html

[Q14] 存在则更新（upsert）
来源：http://dali.jyoumei.cn/Article/details/gt2dgpauesw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ehwqpu.com/Article/details/gt2ekwqsvjg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqnmyfym.html

[Q15] 查询全部
来源：http://dali.birdmap.top/Article/details/gt2oooyawgl.html

SELECT * FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2asduzbol.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gt2mywqckds.html

SELECT id, name FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2fnfipkdw.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gt2qyakrblo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangdashe.top/Article/details/gt2jrduwcvl.html

[Q18] 模糊匹配
来源：http://dali.jiagoushi.top/Article/details/gt2tdzojwal.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhixingplan.top/Article/details/gt2zsucfwni.html

[Q19] 范围查询
来源：http://dali.cqqwz.cn/Article/details/gt2gsuntoso.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gt2yqkhpibb.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gt2lbcaxstl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gt2bppmgfeh.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gt2xudflxvx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jyoumei.cn/Article/details/gt2utayazha.html

[Q22] 排序
来源：http://dali.jianghu66.top/Article/details/gt2bihlhxxs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigfzy.top/Article/details/gt2iylsuvtr.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gt2eiftgpvc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aibaodan.cn/Article/details/gt2rzhpvvfk.html

[Q24] 去重
来源：http://dali.daria6918.cn/Article/details/gt2ejigirzm.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gt2vuwnnejj.html

[Q25] 只取前 N 条
来源：http://dali.snrcjt.cn/Article/details/gt2rbjzsidn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gt2uohmqrna.html

[Q26] 计数
来源：http://dali.cucudq.cn/Article/details/gt2sxpuvnek.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqdvyzv.html

[Q27] 条件计数
来源：http://dali.chenzaomai.com/Article/details/gt2ivsgqgjb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2khqgzcit.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gt2burhqqxl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2pdrblujv.html

[Q29] 最大最小值
来源：http://dali.yvedp.cn/Article/details/gt2xqfkkoep.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmnyqmkh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjtejta.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2ebslxkre.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gt2hjcxsujk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gt2dezcuwkz.html

[Q32] 分组拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvtkbtya.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2lmjmwdpr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gt2xpocbuez.html

[Q33] 多列分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2uggwapgm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yangfankeji.com/Article/details/gt2urnohcnl.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gt2itokkpyx.html

SELECT * FROM (
来源：http://dali.andypj.xyz/Article/details/gt2djursgkq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhoulong.xyz/Article/details/gt2yakvpfye.html

) t WHERE rn = 1;
来源：http://dali.gzhubu.top/Article/details/gt2aygpxhdc.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gt2lgfwttqd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gt2bqfkgnor.html

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gt2tyexjxuq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gt2vshphadi.html

[Q37] 右连接
来源：http://dali.zycfv.cn/Article/details/gt2kmeabima.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gt2idataedk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.kuanghao11.cn/Article/details/gt2qbzvwxme.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gt2wjhbvzhx.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gt2qdtdlvbf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gt2okgmenyd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jyoumei.cn/Article/details/gt2qqgixwud.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gt2unvacuga.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gt2zygyscyd.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gt2avbcydzb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2noflayxt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gt2klnfhiei.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.snrcjt.cn/Article/details/gt2nigwxzuv.html

[Q42] 连接条件附加过滤
来源：http://dali.cqqwz.cn/Article/details/gt2aajjkwya.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hysaishi.cn/Article/details/gt2tbefjkxy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.haohaochexian.top/Article/details/gt2xiqpnszc.html

[Q43] 标量子查询
来源：http://dali.vqdsnc.cn/Article/details/gt2sjvltrry.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gt2vejfxhod.html

[Q44] IN 子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clbmprkr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gt2liwcwjsj.html

[Q45] EXISTS 判断存在
来源：http://dali.dashuyun.cn/Article/details/gt2hpjtgsty.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gt2zyxjogko.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hammf.cn/Article/details/gt2wnnmaeda.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gt2hrmiwhxb.html

[Q47] 与平均值比较
来源：http://dali.0kj1m.cn/Article/details/gt2vzcmtwhq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hywenlv.cn/Article/details/gt2qghhpmua.html

[Q48] CTE 公用表表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2drhhqfhd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.redwolf501.top/Article/details/gt2aiwajnpd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gt2lytvdngs.html

[Q49] 更新单行
来源：http://dali.cdnleiting.top/Article/details/gt2nndluyyz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gt2qdmxuzlb.html

[Q50] 批量更新
来源：http://dali.tanke756.top/Article/details/gt2xfewmldd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gt2xexssabb.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gt2ybyhsaqv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsythzy.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gt2bkcaoisn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gt2ioedfygt.html

[Q53] 按条件删除
来源：http://dali.meibo888.top/Article/details/gt2isjsiwyn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigufen.top/Article/details/gt2szyrneow.html

[Q54] 清空表
来源：http://dali.yvedp.cn/Article/details/gt2fdoednfx.html

TRUNCATE TABLE logs;
来源：http://dali.aibaodan.cn/Article/details/gt2icfpcvri.html

[Q55] 排名（并列占位）
来源：http://dali.fengsongda.top/Article/details/gt2jtwqebea.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gt2aomdwtra.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gt2epvnkvwc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cucudq.cn/Article/details/gt2tfxpfdfk.html

[Q57] 行号
来源：http://dali.sxryk.cn/Article/details/gt2naowkjiz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gt2wxmwwpym.html

[Q58] 累计求和
来源：http://dali.sufxvd.cn/Article/details/gt2tnubgmdv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2sohjwgxk.html

[Q59] 分组内累计
来源：http://dali.jinqigfzy.top/Article/details/gt2rljuicrk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gt2wcqxuosu.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gt2odlaanfz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.iojbl.cn/Article/details/gt2lviqebxf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2jhpzfunc.html

[Q61] 移动平均
来源：http://dali.yonumen.top/Article/details/gt2ugzvtpkw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2avgrqlce.html

[Q62] 分组占比
来源：http://dali.ppjwa.cn/Article/details/gt2ovlurvxt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gt2uhxmyyyg.html

[Q63] 开启事务
来源：http://dali.9152youxi.cn/Article/details/gt2bjdjqmfx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcbouhwr.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gt2ysfmtbzu.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gt2atafwqgh.html

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2txykvwvu.html

ROLLBACK;
来源：http://dali.cdnleiting.top/Article/details/gt2luamqehg.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gt2ulrdrumb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pihtvkej.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gt2pkyothyw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gt2gqfireek.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gt2zqbpveaq.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gt2uacdzawl.html

ROLLBACK TO sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rbahkywg.html

[Q69] 查看执行计划
来源：http://dali.havefunace.top/Article/details/gt2xbvhsdgz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gt2rivzhlhq.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gt2asxvhsjd.html

ANALYZE TABLE users;
来源：http://dali.andypj.xyz/Article/details/gt2scfodvww.html

[Q71] 查看建表语句
来源：http://dali.tianlin.xyz/Article/details/gt2gbqxxxjx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuanzx.com/Article/details/gt2scolytez.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gt2yzyznmzg.html

SHOW INDEX FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2fxzrpgxr.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gt2dxnyqodv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gt2tobgetqn.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gt2lowylawk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gt2ujwiokao.html

[Q75] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gt2dkmbflge.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2xbzitwyq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cqqwz.cn/Article/details/gt2ijbojkrd.html

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gt2dzgbxlxm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guowangkeji.top/Article/details/gt2xnenpmnw.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gt2joyyondp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yongpay.top/Article/details/gt2xsxwtshf.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gt2ppngcyon.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtuncbhs.html

[Q79] 字符串拼接
来源：http://dali.gzhubu.top/Article/details/gt2slruynpx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hongshengwenyu.top/Article/details/gt2vnplymzb.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gt2gbpahbgz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2jqwdpdgt.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gt2ccgmiusj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2obhhwiev.html

[Q82] 字符长度与字节长度
来源：http://dali.hysaishi.cn/Article/details/gt2cpmoijcj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2tcaibton.html

[Q83] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gt2rlkgrwun.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2xjlmbypq.html


<!-- 参考信息 -->