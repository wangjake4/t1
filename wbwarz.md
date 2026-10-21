代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gtlyplphmh.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gtkypldyvp.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gtwykshcch.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gtrhtkiexy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgufenzy.top/Article/details/gtywxpwmza.html

JS:   async function f() { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtebhryfdx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ydzc1.top/Article/details/gtmzfhpfcb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.vqdsnc.cn/Article/details/gtcyffmbwq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gtkcrdmvns.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gtitgdtyzp.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gtgakonxjg.html

[O05] 并发执行并等待全部完成
来源：http://dali.quarkkingdee.top/Article/details/gtcfoypurf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hfpthk.cn/Article/details/gtgcxympie.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gtkzfxqkve.html

JS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtkmlkkbdy.html

TS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gtnjrlvfnc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.quarkkingdee.top/Article/details/gtewrdttjo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gtaozimfoj.html

Ruby: threads.map(&:join)
来源：http://dali.ivvv.top/Article/details/gtcsrxoeev.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258.top/Article/details/gtpfeqpius.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gtelitepii.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dianchejie.cn/Article/details/gtbjilmauw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cdnleiting.top/Article/details/gtataxqqhi.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtrqzmaylw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtdyvgwyza.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gtxrudamft.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.haohaochexian.top/Article/details/gtwknkefny.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gtkjareykb.html

C#:   Parallel.For
来源：http://dali.snrcjt.cn/Article/details/gtbhqoiwrp.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtpnzrxnpz.html

P. 常用工具函数
来源：http://dali.sysykeji.top/Article/details/gtosxiuabf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtkbnybiuz.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gteylsfafk.html

Py:   str(uuid.uuid4())
来源：http://dali.feifeiyinyue.top/Article/details/gtongvzfqo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hammf.cn/Article/details/gtmtszhvcq.html

JS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtfwrknmar.html

TS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtwayzbhca.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gtoqukfnkx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtwowusnps.html

Ruby: SecureRandom.uuid
来源：http://dali.xuanzx.com/Article/details/gtdmesujlq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gtvdaphmpo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gzhubu.top/Article/details/gtsrfxpmzs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gtdayzggxw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shuidangran.top/Article/details/gtqkrgsndl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ybcxt.top/Article/details/gtobwiojmk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pengpengdd.cyou/Article/details/gtauiqyavv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtircjyajf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gttrwmqnaz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtilyiawll.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gtpoaryois.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gtgpfbhbbe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gtwiwereyi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.birdmap.top/Article/details/gtqmvtrhmz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuaoxwhj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtbsuztaxj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangdashe.top/Article/details/gtdmxylwyh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gtkxmquekv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhongyouzk.top/Article/details/gtvcievjfl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtfunesyyn.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gtuomendnl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ivvv.top/Article/details/gtikdhedin.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gthbhkhcbv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gtkikcwzzm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtophxmpnw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqdmhfno.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gtabggxtny.html

Ruby: x.length;  x.size
来源：http://dali.cashguo.top/Article/details/gtirfretsy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgfzy.top/Article/details/gtpnvhljdb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gtsbpdpmeh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ehwqpu.com/Article/details/gtcrlcthvj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sweek.top/Article/details/gtkvjoejej.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhengqikj.top/Article/details/gtyqmpfdoq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gtrnipkvdc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.smart0.xyz/Article/details/gtehpqvcku.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guannengcc.top/Article/details/gtmzuqgjro.html

Ruby: a == b
来源：http://dali.chenlongwang.top/Article/details/gtmgqakote.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxyxsnmj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jlsjyb.cn/Article/details/gtccbwohyc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gtgaqcpvqp.html

PHP:  if (empty($x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxdbdrlq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jiagoushi.top/Article/details/gtmblsnivi.html

TS:   if (x == null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtitmpwvbi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkeimdtjf.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gtiedtfxyj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gtvkaraklj.html

C#:   if (x is null) {}
来源：http://dali.hnxiangtu.top/Article/details/gtekbitaui.html

[P07] 防抖与节流
来源：http://dali.ydzc1.top/Article/details/gtqjjfvaqv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guannengcc.top/Article/details/gtmbrngyyt.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gtqnevmyap.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtywlwmfxk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtcchjnwpn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gtfycdlepg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgsnmlpe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.iojbl.cn/Article/details/gtxcrjiaox.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gtaibkjloi.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gtduxzudhw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gttbtnqoco.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.birdmap.top/Article/details/gtjsgftilt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhongyouzk.top/Article/details/gteqywutcz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtgpjgiefh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhiwuduotai.top/Article/details/gtkgolagbp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gtpjdzdsme.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gtnojvlnvl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gtwybppuae.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqntegmym.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinghuilouyu.cn/Article/details/gtzafoxpxf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtesneathl.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gtmehmisvd.html

CREATE TABLE users (
来源：http://dali.ybcxt.top/Article/details/gtdduzwfcv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtuhuqpbrx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtponrnasd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgufenzy.top/Article/details/gtfoegggds.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sufxvd.cn/Article/details/gtgdcynspm.html

);
来源：http://dali.cashguo.top/Article/details/gtomyrlsgq.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gtruksxskc.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gtulakxmjx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtiwvaqhat.html

user_id INT NOT NULL,
来源：http://dali.yj202588.top/Article/details/gtzpxetnry.html

amount DECIMAL(10, 2),
来源：http://dali.ydzc1.top/Article/details/gtcezborch.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxinkj.top/Article/details/gtnfpwuxof.html

);
来源：http://dali.hammf.cn/Article/details/gtiarjreow.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gthytwneth.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gtzwqiqqhs.html

[Q04] 修改列类型
来源：http://dali.yonumen.top/Article/details/gtkgdzhubg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtsgdgzgiy.html

[Q05] 重命名列
来源：http://dali.hammf.cn/Article/details/gtfbdpqgzq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xinyue.icu/Article/details/gtpmjszdvk.html

[Q06] 删除列
来源：http://dali.hammf.cn/Article/details/gtpxrajoeg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.havefunace.top/Article/details/gteadvfhto.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gtkdvnyvyf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.haohaochexian.top/Article/details/gtgyqzclsf.html

[Q08] 创建普通索引
来源：http://dali.hfpthk.cn/Article/details/gtmqkzlktn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtyfhnwebc.html

[Q09] 创建唯一索引
来源：http://dali.chenjidiqi.icu/Article/details/gtgekeesql.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtolvdcucq.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gtufeixprq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtuvlyvbji.html

[Q11] 一次插入多行
来源：http://dali.sweek.top/Article/details/gtsbfgvcun.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtonjtboap.html

[Q12] 插入后取自增 ID
来源：http://dali.tianlin.xyz/Article/details/gtpqjzbmbl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangshuangyany.cn/Article/details/gtqjtgseqf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gtzghdcvxb.html

[Q13] 忽略重复插入
来源：http://dali.iojbl.cn/Article/details/gtvadrrlhm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtwgqnqlmp.html

[Q14] 存在则更新（upsert）
来源：http://dali.fzhhl.top/Article/details/gtdkhokzru.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxuanxn.top/Article/details/gtzdboidrk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sufxvd.cn/Article/details/gtkuxbuljz.html

[Q15] 查询全部
来源：http://dali.chenjidiqi.icu/Article/details/gtazoftuyt.html

SELECT * FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtwtremkgr.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gtuqpkskam.html

SELECT id, name FROM users;
来源：http://dali.sweek.top/Article/details/gttwlwqcls.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gtdthtpdna.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.mhx1999.top/Article/details/gtwsylildh.html

[Q18] 模糊匹配
来源：http://dali.cucudq.cn/Article/details/gtvebagorz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gtouodttqd.html

[Q19] 范围查询
来源：http://dali.cdnleiting.top/Article/details/gtuytrvjvm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtjamlyasa.html

[Q20] IN 列表
来源：http://dali.cqqwz.cn/Article/details/gtscbdhivd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtayhzqrld.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gtyiunjqfz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gtrwzkuazk.html

[Q22] 排序
来源：http://dali.aibaodan.cn/Article/details/gtoixfecrv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aizwys.cn/Article/details/gthumlrvef.html

[Q23] 分页
来源：http://dali.feifeiyinyue.top/Article/details/gtzgmdczzn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.snrcjt.cn/Article/details/gtdemmdazt.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gtvomqbhdr.html

SELECT DISTINCT city FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtjajjttgq.html

[Q25] 只取前 N 条
来源：http://dali.haohaochexian.top/Article/details/gtgylnykjq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.haohaochexian.top/Article/details/gtymgjyaji.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gtgetjdahb.html

SELECT COUNT(*) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtbfkaxofh.html

[Q27] 条件计数
来源：http://dali.jyoumei.cn/Article/details/gtvtlkpfol.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gturhejmiy.html

[Q28] 求和与平均
来源：http://dali.ydzc1.top/Article/details/gtbsjbvucw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtfifsopan.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gtxdacnavc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gttwfnxsyj.html

[Q30] 分组统计
来源：http://dali.zhiwuduotai.top/Article/details/gtnmyxnpia.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gttofahxre.html

[Q31] 分组后过滤
来源：http://dali.guannengcc.top/Article/details/gtoakjooma.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gtvionskdq.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gteyjxdelq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtwjswfzmb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gtxantbiko.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gtihhdeemq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sysykeji.top/Article/details/gtstmjweli.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gtoacevwad.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gtuwlxwjks.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ydzc1.top/Article/details/gtkcovdhcy.html

) t WHERE rn = 1;
来源：http://dali.bjfxy.top/Article/details/gtzvkkbzlx.html

[Q35] 内连接
来源：http://dali.yongpay.top/Article/details/gtebeynqdi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gtfnijacfs.html

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gtmabnktfm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtadnchspb.html

[Q37] 右连接
来源：http://dali.nanxinkj.top/Article/details/gtqpzvjgsh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gtmgrvwwko.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhongyouzk.top/Article/details/gtwryoxhon.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cashguo.top/Article/details/gtmmiysbsr.html

[Q39] 自连接（查上下级）
来源：http://dali.bjfxy.top/Article/details/gtvbysmexq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gtkfqpvocx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gtpqocholy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jqgfzy.top/Article/details/gtjwxeveyx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnqzz.top/Article/details/gtgtmwfjsa.html

[Q41] 多表连接
来源：http://dali.zhiwuduotai.top/Article/details/gtpxftbiqa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ydzc1.top/Article/details/gtsvjyjntc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgfzy.top/Article/details/gtraydfwdw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.0kj1m.cn/Article/details/gtxnjowcbu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gtascvqwcl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258888.top/Article/details/gtpyquyiod.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258888.top/Article/details/gtxuozwqly.html

[Q43] 标量子查询
来源：http://dali.pycfn.com/Article/details/gtboookztb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gtxcmqxijx.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxaamfao.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigfzy.top/Article/details/gtgufpczja.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzmolqzy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtafychpfm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hfpthk.cn/Article/details/gtbisrrdnz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtgfyobbfa.html

[Q47] 与平均值比较
来源：http://dali.ppjwa.cn/Article/details/gtsebfyslj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cdnleiting.top/Article/details/gtzrucgwdz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gtxqmkrmli.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gtolhaeuip.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gtcpzjqadx.html

[Q49] 更新单行
来源：http://dali.hammf.cn/Article/details/gtqowemohh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtcamjvjam.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gtwfznvrgx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gtrqcxckex.html

[Q51] 用子查询更新
来源：http://dali.zycfv.cn/Article/details/gtfrlzgrng.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jianghu66.top/Article/details/gteosrdngr.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gtexujltcf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbfuajzz.html

[Q53] 按条件删除
来源：http://dali.dianchejie.cn/Article/details/gtewcojehq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtqlwypbfu.html

[Q54] 清空表
来源：http://dali.andypj.xyz/Article/details/gtimweifqh.html

TRUNCATE TABLE logs;
来源：http://dali.hnqzz.top/Article/details/gtgnvbopfo.html

[Q55] 排名（并列占位）
来源：http://dali.fengsongda.top/Article/details/gtcysiluvu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtsavszane.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daria6918.cn/Article/details/gtbqswevor.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtzglkpfjg.html

[Q57] 行号
来源：http://dali.birdmap.top/Article/details/gtsbfadscr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtjjyodsun.html

[Q58] 累计求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxxwfgjt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtatihhlxo.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gtwuurtaog.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtulhhijxe.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gtksauntpi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.andypj.xyz/Article/details/gtkfjumodl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gtfspevxji.html

[Q61] 移动平均
来源：http://dali.mhx1999.top/Article/details/gtzejammom.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtgkdqbxyj.html

[Q62] 分组占比
来源：http://dali.yonumen.top/Article/details/gtfftcxjqt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtjwqxqugm.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gtsemprzvy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.redwolf501.top/Article/details/gtcfkfiesq.html

[Q64] 提交事务
来源：http://dali.snrcjt.cn/Article/details/gtymquadha.html

COMMIT;
来源：http://dali.gzhubu.top/Article/details/gtwdffmoyz.html

[Q65] 回滚事务
来源：http://dali.yueranfly.top/Article/details/gtagpkycre.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gtherzasdx.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gtjrxgkbkz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yangfankeji.com/Article/details/gtbvrncipf.html

[Q67] 设置隔离级别
来源：http://dali.jinqigfzy.top/Article/details/gtzaqkswbm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258888.top/Article/details/gtushsnrrz.html

[Q68] 保存点
来源：http://dali.yangfankeji.com/Article/details/gtwgntukwd.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvqasvkr.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gtzlhvwffg.html

[Q69] 查看执行计划
来源：http://dali.gaohongyu789.top/Article/details/gttmaprrsb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gtgpcytiwj.html

[Q70] 更新统计信息
来源：http://dali.zycfv.cn/Article/details/gtipiacysd.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gtrysoampw.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gtwowilidk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuanzx.com/Article/details/gtzbyaaite.html

[Q72] 查看索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvwpaavw.html

SHOW INDEX FROM users;
来源：http://dali.c1oappe.top/Article/details/gtmbvouuus.html

[Q73] 查看表状态
来源：http://dali.gaohongyu789.top/Article/details/gtmxgcsrxq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gthtbhmfyh.html

[Q74] 强制使用索引
来源：http://dali.nwbrower.top/Article/details/gtfgubaoio.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cqqwz.cn/Article/details/gtjoefmsez.html

[Q75] 日期格式化
来源：http://dali.meibo888.top/Article/details/gttzemjyta.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtdakbrbjn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cdnleiting.top/Article/details/gtruziltxd.html

[Q76] 按天统计
来源：http://dali.chenzaomai.com/Article/details/gtsfgvdajc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xinyue.icu/Article/details/gtjldymupa.html

[Q77] 时间加减
来源：http://dali.tanke756.top/Article/details/gtkericlqk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aizwys.cn/Article/details/gtytoahapa.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gtzwnwurfm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhoulong.xyz/Article/details/gtqgfqydcv.html

[Q79] 字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gthsgdqfqd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gtraxpxfrb.html

[Q80] 字符串截取
来源：http://dali.ppjwa.cn/Article/details/gtikpfvoet.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtjgaceltn.html

[Q81] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gtxarxlvqo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gtptqzbyzi.html

[Q82] 字符长度与字节长度
来源：http://dali.jiagoushi.top/Article/details/gthjjifhil.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtbdbmwwxe.html

[Q83] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtbopvtzvh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gttpkqzxkv.html

[Q84] 去除首尾空格
来源：http://dali.yj20258888.top/Article/details/gthchmxjui.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtspgmfhce.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gtlldomaci.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jyoumei.cn/Article/details/gtwidfulqs.html


<!-- 参考信息 -->