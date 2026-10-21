代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gtcomrouoh.html

[O03] 加锁保护共享数据
来源：http://dali.chenzaomai.com/Article/details/gtllspdszl.html

Py:   with lock: shared += 1
来源：http://dali.pengpengdd.cyou/Article/details/gtrlsjwezq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gtghdhiehm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gtoevdmxkf.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtrvpbgmtb.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtnswglsqf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gtfsjvcagn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtrznmqarl.html

C#:   lock (gate) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gtmparvyxx.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gtrnjgwmup.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gtxekpdvrl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhixingplan.top/Article/details/gtplxajbgh.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqqgknmmn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtozgrziyq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhoulong.xyz/Article/details/gtxzzglziu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gtcbmrkdol.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.0kj1m.cn/Article/details/gtkehvzmxh.html

C#:   async Task F() { await G(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvvjedpf.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gtevfqwory.html

Py:   asyncio.gather(*tasks)
来源：http://dali.meibo888.top/Article/details/gtcmulqtuv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigfzy.top/Article/details/gtutyewmfe.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtqoefdodf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtmmmhmlzc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258.top/Article/details/gtzrzugzyc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gtuxmoghnm.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtknoljqpo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jlsjyb.cn/Article/details/gtbseyvbmp.html

[O06] 使用进程池
来源：http://dali.vqdsnc.cn/Article/details/gtoduwwelc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xylfe.cn/Article/details/gtyororqzd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj202588.top/Article/details/gtpazbpqca.html

JS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gtutumhijx.html

TS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtykuhqigx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtpfiqouom.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnxiangtu.top/Article/details/gtuztnoyst.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gtkdmabisq.html

C#:   Parallel.For
来源：http://dali.zycfv.cn/Article/details/gtaeehqucl.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtlgbfpoxy.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gtvkybwdfa.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtsthsmdhr.html

[P01] 生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtzbxjfsbl.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwvvviyt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gtemhjgzxz.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtgtolprlg.html

TS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtckblvjhk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhengqikj.top/Article/details/gtahvchjao.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtjzrxyqus.html

Ruby: SecureRandom.uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtnkcfxjde.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gtpawsdrrc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gtfingypeq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fzhhl.top/Article/details/gttxznfhgl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtkniyyqxd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigufen.top/Article/details/gtqguoqmxh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvueseoy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtcnvvxxrg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pycfn.com/Article/details/gtwtpelejk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gtwqfckfpg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinghuilouyu.cn/Article/details/gtltnrheyg.html

[P03] 生成短随机字符串
来源：http://dali.ybcxt.top/Article/details/gtvptijjus.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gtjnmbejll.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jlsjyb.cn/Article/details/gtoeieiuvm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtkscdpwci.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtyqzfggdq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fengsongda.top/Article/details/gtpydniuzl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gtygbxlpjy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtcflrszpb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.smart0.xyz/Article/details/gtloqnxubr.html

[P04] 求长度
来源：http://dali.wangdashe.top/Article/details/gtskhlhllr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccxvruab.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtrfsvvtda.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtuzhcjmwu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtduwlzayw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamfwowvd.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gteqkrlzyc.html

Ruby: x.length;  x.size
来源：http://dali.chenlongwang.top/Article/details/gthmznvryr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nwbrower.top/Article/details/gtblohfvwm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xinyue.icu/Article/details/gtharxjgdq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinghuilouyu.cn/Article/details/gtehojnokp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gtkdvzutqf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gtdaonzotf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gtmhvjllas.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gtmdxkifrb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtxhlhirxi.html

Ruby: a == b
来源：http://dali.cucudq.cn/Article/details/gtlaxxezss.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gtjzkrzwxt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tanke756.top/Article/details/gtocuybohu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dianchejie.cn/Article/details/gtzgzpgrlr.html

PHP:  if (empty($x)) {}
来源：http://dali.316326.xyz/Article/details/gtcgjwzlhd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxuanxn.top/Article/details/gtsdolhfmw.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gtejtqmoes.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtnqluexmu.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gtrmrrqajd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gtezqxoxqb.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gtfqlcxztf.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gtrbfecoim.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gtkfgxcaty.html

PHP:  // 手写时间戳比较
来源：http://dali.cashguo.top/Article/details/gtngyfdhbb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtpbucjgie.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtamkgvohf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gtaswpnvue.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhengqikj.top/Article/details/gtzlgjtdgr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.bjfxy.top/Article/details/gttxgamqgl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gtofrppbuo.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gtatbemmpb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhongyouzk.top/Article/details/gtxrwymjvk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daxiang520.top/Article/details/gtwodchuce.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gtieygndcl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtzrjpscmz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shuidangran.top/Article/details/gttprdrxkv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gtwxfuztns.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xylfe.cn/Article/details/gtlkwbsxrs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gtbvagjbvn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthznkbtwf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenjidiqi.icu/Article/details/gtqhdvvufk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjbylwxjy.html

[Q01] 创建表
来源：http://dali.cashguo.top/Article/details/gtaocyufvt.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtkuhdrxeq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtvxnziysc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtdblybyag.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gtoawdrbzy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gtkphosjjn.html

);
来源：http://dali.c1oappe.top/Article/details/gtstuzrreq.html

[Q02] 创建带外键的表
来源：http://dali.zhiwuduotai.top/Article/details/gtyqpdtbts.html

CREATE TABLE orders (
来源：http://dali.chenlongwang.top/Article/details/gtqguyqrjm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtdujclltt.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtgeupgubx.html

amount DECIMAL(10, 2),
来源：http://dali.sysykeji.top/Article/details/gtqqscjkyb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gtlbyleuvi.html

);
来源：http://dali.dashuyun.cn/Article/details/gtfgumvwal.html

[Q03] 增加列
来源：http://dali.pengpengdd.cyou/Article/details/gtzraeylbt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daria6918.cn/Article/details/gtueuzbzrk.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gtniqtrsti.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yueranfly.top/Article/details/gtifcwltty.html

[Q05] 重命名列
来源：http://dali.fengsongda.top/Article/details/gtmealjdjh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yanxiufei.cn/Article/details/gtysjlgyrm.html

[Q06] 删除列
来源：http://dali.yj202588.top/Article/details/gtzvzfmyvs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gtyyntiuqu.html

[Q07] 删除表
来源：http://dali.hammf.cn/Article/details/gtgdlglbmb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhoulong.xyz/Article/details/gtzqybkmbn.html

[Q08] 创建普通索引
来源：http://dali.ppjwa.cn/Article/details/gtjsfxdbhy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gtvljzzcrs.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdogeqoeq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gteuteqvxy.html

[Q10] 插入单行
来源：http://dali.chenzaomai.com/Article/details/gtzytnuswr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtxsqkneum.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdjeakoe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtbffjxrtd.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gtugjrcasx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guowangkeji.top/Article/details/gtcxmmofvd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sufxvd.cn/Article/details/gtquumaxcl.html

[Q13] 忽略重复插入
来源：http://dali.nanxuanxn.top/Article/details/gtefmcehwx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtsuymyphz.html

[Q14] 存在则更新（upsert）
来源：http://dali.9152youxi.cn/Article/details/gtewnzetpj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tianlin.xyz/Article/details/gtbhndhhdk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gogol.net.cn/Article/details/gtzvlixbyo.html

[Q15] 查询全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsimjpec.html

SELECT * FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtfdaqndud.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gtxgxenyet.html

SELECT id, name FROM users;
来源：http://dali.yuxming.cn/Article/details/gtcyvakksn.html

[Q17] 条件查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzwzsglv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gtyqoabnze.html

[Q18] 模糊匹配
来源：http://dali.hnxiangtu.top/Article/details/gtfncutwew.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gtmqjfmios.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gttzrmynrh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gtlgnqiefc.html

[Q20] IN 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtlvmksmzh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xziqi.cn/Article/details/gtcccfvwdo.html

[Q21] 空值判断
来源：http://dali.meibo888.top/Article/details/gtbdcifteo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gtpjfzxtnp.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gtgpwflkla.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gogol.net.cn/Article/details/gthfsnnxkb.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuchjqgbt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fzhhl.top/Article/details/gtqwnpqrdf.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gtdfcxfytc.html

SELECT DISTINCT city FROM users;
来源：http://dali.guannengcc.top/Article/details/gterizxejy.html

[Q25] 只取前 N 条
来源：http://dali.hammf.cn/Article/details/gtyagthego.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gtbvecxaij.html

[Q26] 计数
来源：http://dali.daxiang520.top/Article/details/gtrldmzfkk.html

SELECT COUNT(*) FROM users;
来源：http://dali.cheryme.top/Article/details/gtrrqyeufc.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gtwtciseqn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shzxlz.cn/Article/details/gttoumxxux.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gtsrpxgdlw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtbfoupxki.html

[Q29] 最大最小值
来源：http://dali.yvedp.cn/Article/details/gtruczjfvn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtmnfxqjxg.html

[Q30] 分组统计
来源：http://dali.birdmap.top/Article/details/gtxsmstxsj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtgvukqhsa.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gtgmpzsmam.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhengqikj.top/Article/details/gteiwkwwla.html

[Q32] 分组拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtbarrfenw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtnjefcdya.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jianghu66.top/Article/details/gthqcbnrsg.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gtuyzsfosa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gtsfgxploy.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gtzmozmrej.html

SELECT * FROM (
来源：http://dali.9152youxi.cn/Article/details/gtnkurttdh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigufen.top/Article/details/gtaiwomqub.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gtzmdbtcln.html

[Q35] 内连接
来源：http://dali.hywenlv.cn/Article/details/gtdtbrzvkz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gtpcxwbhyy.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gtbbzlrnnw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtrqukhfvd.html

[Q37] 右连接
来源：http://dali.xuetiantiany.cn/Article/details/gtlzhppybn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtavoqaazo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangshuangyany.cn/Article/details/gtnfjserkj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtspnpychm.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gtoilrmjpa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hammf.cn/Article/details/gttwnydrpc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hammf.cn/Article/details/gtlzbsmyfo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jianghu66.top/Article/details/gtwugxdxow.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenlongwang.top/Article/details/gtusnjncfp.html

[Q41] 多表连接
来源：http://dali.zhengqikj.top/Article/details/gtuvhjrqoo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ppjwa.cn/Article/details/gtkafuirvk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daxiang520.top/Article/details/gtinlptdwl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gttsnzsgwk.html

[Q42] 连接条件附加过滤
来源：http://dali.kuanghao11.cn/Article/details/gtxglvuiat.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nwbrower.top/Article/details/gtujodrrvb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zycfv.cn/Article/details/gtistkpxvz.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gtorvhkywt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gtfdhzhhxb.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gtwxxfsyuz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fengsongda.top/Article/details/gthwiakajq.html

[Q45] EXISTS 判断存在
来源：http://dali.birdmap.top/Article/details/gtyazncvtm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gtdasuoibw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shuidangran.top/Article/details/gtrauiazgc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gtyyvqogsq.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gtgoybmbty.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yueranfly.top/Article/details/gtsbgusklq.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258.top/Article/details/gtlkbzjwii.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhiwuduotai.top/Article/details/gtwqxutfkh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhixingplan.top/Article/details/gtztzwpruu.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gtgkiexpes.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtqpvrbguj.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gtoqzjhkxh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.birdmap.top/Article/details/gtpplufdpa.html

[Q51] 用子查询更新
来源：http://dali.yuxming.cn/Article/details/gttjdyxkxn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fzhhl.top/Article/details/gtkaxvfwsv.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gtaonjiezj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtrdegxtml.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gtlqsgydxg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pycfn.com/Article/details/gttdjidauv.html

[Q54] 清空表
来源：http://dali.daxiang520.top/Article/details/gtupqrmhgv.html

TRUNCATE TABLE logs;
来源：http://dali.aibaodan.cn/Article/details/gtabbjhndk.html

[Q55] 排名（并列占位）
来源：http://dali.xinyue.icu/Article/details/gtwxlqojdl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtcztqgggo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gtctgmzayh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtluybkmsq.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gtlkzqefwu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtbrurljmk.html

[Q58] 累计求和
来源：http://dali.ivvv.top/Article/details/gtkseqfxvo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtvziphrcd.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gtnhjbbbnm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgziyyswj.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gtahsyuwow.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhixingplan.top/Article/details/gthwdickoz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gttbrkabzk.html

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gtgumikfxr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtgzsodshn.html

[Q62] 分组占比
来源：http://dali.smart0.xyz/Article/details/gtxqnwugor.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrtaabkv.html

[Q63] 开启事务
来源：http://dali.jqgufenzy.top/Article/details/gthvakwceg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuetiantiany.cn/Article/details/gtzawdmgni.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtafealefz.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gtomfearxa.html

[Q65] 回滚事务
来源：http://dali.cqqwz.cn/Article/details/gtmgraevyw.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gtmdnybucb.html

[Q66] 行锁查询
来源：http://dali.sysykeji.top/Article/details/gtyglmixby.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gtmlgaaacd.html

[Q67] 设置隔离级别
来源：http://dali.hnxiangtu.top/Article/details/gtevtvbylc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cucudq.cn/Article/details/gtpsqucocm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gthmqpnfwu.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtikqrzyxo.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gtekwtqzru.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gthbwwvwha.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsbqkjov.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gtgcqkqctp.html

ANALYZE TABLE users;
来源：http://dali.yueranfly.top/Article/details/gtpdodbgwu.html

[Q71] 查看建表语句
来源：http://dali.gaohongyu789.top/Article/details/gtzdtqrswr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yueranfly.top/Article/details/gtblhgpaej.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gtkvwmxvyj.html

SHOW INDEX FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdvigddu.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gtwsnaskwb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gtsmknqgft.html

[Q74] 强制使用索引
来源：http://dali.yuxming.cn/Article/details/gtctlxkeqx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fengsongda.top/Article/details/gtnrzqfber.html

[Q75] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtlgltbrzc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtszyvarhu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gtkynismrr.html

[Q76] 按天统计
来源：http://dali.guowangkeji.top/Article/details/gtnswbhdoa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sxryk.cn/Article/details/gtoqfrznxe.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gtafhwxpqt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aizwys.cn/Article/details/gtoxudmqch.html

[Q78] 当前时间
来源：http://dali.gotoacloud.top/Article/details/gtfpqbbtxy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ivvv.top/Article/details/gtyiasogsc.html

[Q79] 字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gtekgswgmu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.316326.xyz/Article/details/gtkdtybmyx.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gtktvokzsc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtejvluqdf.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtykdwghrk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gtyadqnzfy.html


<!-- 参考信息 -->