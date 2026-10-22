代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gt2lnkrraul.html

[O03] 加锁保护共享数据
来源：http://dali.cheryme.top/Article/details/gt2vammedbw.html

Py:   with lock: shared += 1
来源：http://dali.nwbrower.top/Article/details/gt2jcoorhpy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.haohaochexian.top/Article/details/gt2fpqtvfwv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gt2obboxktu.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2hodrvtxt.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2hgjscwrj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gt2mnzfyias.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqjymksz.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gt2uiqucxcq.html

[O04] 定义异步函数并等待
来源：http://dali.ppjwa.cn/Article/details/gt2jlivacwx.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gt2srcjmtsw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jiagoushi.top/Article/details/gt2wjruwqdm.html

JS:   async function f() { await g(); }
来源：http://dali.xuanzx.com/Article/details/gt2pxmgljif.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gt2ngrepmbv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gt2euagehpw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gt2lprjlcxa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yanxiufei.cn/Article/details/gt2bkxlwzfs.html

C#:   async Task F() { await G(); }
来源：http://dali.yangfankeji.com/Article/details/gt2ufodvkpd.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gt2nljhbaih.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2ftmixaye.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gt2jrgwhiot.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gt2gqqrxnkz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2brhdczsg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guowangkeji.top/Article/details/gt2lbtifwox.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gt2bagjheny.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gt2mcnxivng.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gt2ifhykiwh.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gt2earkacxe.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkxtkpqq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigfzy.top/Article/details/gt2xmvcmnbo.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gt2imqlktde.html

TS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gt2bxcwyseu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigfzy.top/Article/details/gt2twaejfyh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.c1oappe.top/Article/details/gt2qkcsocbq.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gt2wuboqrne.html

C#:   Parallel.For
来源：http://dali.aizwys.cn/Article/details/gt2wjtosetc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2xqgynjrd.html

P. 常用工具函数
来源：http://dali.gotoacloud.top/Article/details/gt2buousqch.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2xaqwyamt.html

[P01] 生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gt2bfkjjmxz.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvwacpse.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gt2ggeufxvb.html

JS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gt2snwjuhwc.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gt2vciznxzf.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qrurzitk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shuidangran.top/Article/details/gt2xuxqeiyd.html

Ruby: SecureRandom.uuid
来源：http://dali.hfpthk.cn/Article/details/gt2cbqrvifb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gt2rlxmmwge.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gt2avfvehiv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gt2zgugneow.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gt2wdpbnews.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gt2fngwxvde.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenlongwang.top/Article/details/gt2pewrvmke.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2bkebosxr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fengsongda.top/Article/details/gt2vjswilng.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hammf.cn/Article/details/gt2xqlsoied.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zdqjudy.top/Article/details/gt2vaayndka.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gt2nsrhdvnt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tian-w.cn/Article/details/gt2vmfskwvu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.haohaochexian.top/Article/details/gt2pokepkdh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gt2evwzcqfp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gt2pqkydekd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ivvv.top/Article/details/gt2xxkrcvvo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xinyue.icu/Article/details/gt2ehxdwjkh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2akxeazaa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenlongwang.top/Article/details/gt2xrwkgqzw.html

[P04] 求长度
来源：http://dali.ydzc1.top/Article/details/gt2tpmdkvqr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxaqaso.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2bypmkwzy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gt2fjnetcid.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gt2djkbqamn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xziqi.cn/Article/details/gt2nzncsgqq.html

Go:   len(arr);  len(m)
来源：http://dali.cdnleiting.top/Article/details/gt2kfxgyhtk.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gt2qazflsaq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.iojbl.cn/Article/details/gt2nxpsdhvx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gt2wcyoyxqx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.andypj.xyz/Article/details/gt2oojhfdib.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gt2zjtxfcnp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cqqwz.cn/Article/details/gt2hhvnwzlv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gt2mamxlmyy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gt2labcmpzf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cksgdthc.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gt2ewbsdkyg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.redwolf501.top/Article/details/gt2aggkrrbk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xinyue.icu/Article/details/gt2szkcmhov.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hnqzz.top/Article/details/gt2bqgwoecp.html

PHP:  if (empty($x)) {}
来源：http://dali.meibo888.top/Article/details/gt2kbixzufq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jyoumei.cn/Article/details/gt2rggoqyqu.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gt2nqqupmpl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2egoqnddb.html

Go:   if x == nil {}
来源：http://dali.yangfankeji.com/Article/details/gt2umiqwkmp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenlongwang.top/Article/details/gt2diwdypam.html

C#:   if (x is null) {}
来源：http://dali.redwolf501.top/Article/details/gt2ricarsct.html

[P07] 防抖与节流
来源：http://dali.316326.xyz/Article/details/gt2vzlhikna.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cheryme.top/Article/details/gt2jlnnxpxu.html

PHP:  // 手写时间戳比较
来源：http://dali.316326.xyz/Article/details/gt2oeqidgny.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gt2trwoxney.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gt2cvytjqvv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gt2kbijujed.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gzhubu.top/Article/details/gt2pqnffpqu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xziqi.cn/Article/details/gt2gcmgzety.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yvedp.cn/Article/details/gt2fhylrydg.html

[P08] 处理浮点精度问题
来源：http://dali.chenlongwang.top/Article/details/gt2jcovyzlw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gt2fcormwbx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gt2omxzfkks.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sufxvd.cn/Article/details/gt2kzrloysp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fjiurcri.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxinkj.top/Article/details/gt2rtpjtylo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgufenzy.top/Article/details/gt2qhvudfwb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhongyouzk.top/Article/details/gt2yvqufaho.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hysaishi.cn/Article/details/gt2khlelcjj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2tdoppyrm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gt2qtrsqcno.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2djctrirc.html

[Q01] 创建表
来源：http://dali.aizwys.cn/Article/details/gt2hvhkmghe.html

CREATE TABLE users (
来源：http://dali.ydzc1.top/Article/details/gt2ucdcwvsf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gt2khncinmu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gt2reinxdah.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dashuyun.cn/Article/details/gt2ooxihlsx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pengpengdd.cyou/Article/details/gt2ehmongqm.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ztokmmnj.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gt2stcfnksj.html

CREATE TABLE orders (
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dseczfym.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gt2fzxbwpif.html

user_id INT NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gt2ezfejjly.html

amount DECIMAL(10, 2),
来源：http://dali.zhoulong.xyz/Article/details/gt2ismrcxep.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gt2sbcwszfx.html

);
来源：http://dali.0kj1m.cn/Article/details/gt2sghmabty.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gt2imthmidg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gt2xmwljsxp.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttveugsc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gt2bmmwpzed.html

[Q05] 重命名列
来源：http://dali.birdmap.top/Article/details/gt2cjrddwjh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pubdcfsc.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gt2eehdlvwk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ivvv.top/Article/details/gt2pbkzanyt.html

[Q07] 删除表
来源：http://dali.bjfxy.top/Article/details/gt2doiiethj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgfzy.top/Article/details/gt2fzegqpmk.html

[Q08] 创建普通索引
来源：http://dali.chenzaomai.com/Article/details/gt2hngmkapv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2uibipyqj.html

[Q09] 创建唯一索引
来源：http://dali.birdmap.top/Article/details/gt2xgdyrdvj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gt2yixpdasb.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gt2pulsevra.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guowangkeji.top/Article/details/gt2gbhvayhg.html

[Q11] 一次插入多行
来源：http://dali.yuanzhike.top/Article/details/gt2doelhajw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ythozbyj.html

[Q12] 插入后取自增 ID
来源：http://dali.birdmap.top/Article/details/gt2igdderxg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mokitmkn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gt2bbdnmslx.html

[Q13] 忽略重复插入
来源：http://dali.gogol.net.cn/Article/details/gt2ztvoobvo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.iojbl.cn/Article/details/gt2wdkfzbgi.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gt2gkygswmo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jyoumei.cn/Article/details/gt2nqlhhymr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gt2hwqexpgv.html

[Q15] 查询全部
来源：http://dali.yangfankeji.com/Article/details/gt2lcmdauut.html

SELECT * FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2eejwtiot.html

[Q16] 查询指定列
来源：http://dali.bjfxy.top/Article/details/gt2mfrwgwex.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2ksybsugh.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gt2sislmlbk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuanzx.com/Article/details/gt2hpsjfzzp.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2ivwlejpf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangshuangyany.cn/Article/details/gt2kirqjrry.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gt2upwbqpel.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxuanxn.top/Article/details/gt2qgxzwocs.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gt2peqruclx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gt2vdbericq.html

[Q21] 空值判断
来源：http://dali.yangfankeji.com/Article/details/gt2mfnixswq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258.top/Article/details/gt2ommqgceo.html

[Q22] 排序
来源：http://dali.jianghu66.top/Article/details/gt2xibqamuh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wergezfr.html

[Q23] 分页
来源：http://dali.wangshuangyany.cn/Article/details/gt2msmqfhxo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gt2kucsunck.html

[Q24] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwjtfjle.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqagkqgm.html

[Q25] 只取前 N 条
来源：http://dali.quarkkingdee.top/Article/details/gt2bdsuwpqz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.haohaochexian.top/Article/details/gt2wgpeuyzf.html

[Q26] 计数
来源：http://dali.sufxvd.cn/Article/details/gt2jyyirwry.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2osapdost.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gt2qrrrdifj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2aestjkch.html

[Q28] 求和与平均
来源：http://dali.zhoulong.xyz/Article/details/gt2hnwulhty.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2cojnysum.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gt2fwwqnrmj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2rguoakrx.html

[Q30] 分组统计
来源：http://dali.sweek.top/Article/details/gt2voroqewb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2szxumegk.html

[Q31] 分组后过滤
来源：http://dali.dashuyun.cn/Article/details/gt2uxxwbwri.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2udedjrhj.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2jhxuljsn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2uducevee.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gt2amlufhjl.html

[Q33] 多列分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2yptxeeec.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.meibo888.top/Article/details/gt2cqoevlol.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gt2zxkumuit.html

SELECT * FROM (
来源：http://dali.feifeiyinyue.top/Article/details/gt2czrdgpjx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.birdmap.top/Article/details/gt2czkngtak.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2iebbarbc.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gt2zxvrmqbo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gt2qmpbnqiz.html

[Q36] 左连接
来源：http://dali.316326.xyz/Article/details/gt2eegtucnv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2ckyyngkt.html

[Q37] 右连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqpgqvii.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gt2uxbzyowj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gt2riolpfne.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gt2iebmmjft.html

[Q39] 自连接（查上下级）
来源：http://dali.ydzc1.top/Article/details/gt2eqxkjxby.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigfzy.top/Article/details/gt2gwftxutm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gt2lwjoerck.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhixingplan.top/Article/details/gt2wafghiss.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gt2twdotmtw.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gt2wkbolton.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdednszc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttptbyfk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shzxlz.cn/Article/details/gt2tkjvunzz.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gt2auavaqvw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gt2ujklbcwb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yueranfly.top/Article/details/gt2pdxpevmz.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gt2qbjrtjrz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gt2izrqkmfl.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gt2dktxyhju.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hywenlv.cn/Article/details/gt2tkfnghng.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2aawjxxoy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gt2lqqlfcsx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gt2gprzlzqb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gt2xcbcxfsu.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gt2iqgvdgqk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yueranfly.top/Article/details/gt2hchmpcyc.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gt2hkjebctd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwlsgwgq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shzxlz.cn/Article/details/gt2cismkddk.html

[Q49] 更新单行
来源：http://dali.dashuyun.cn/Article/details/gt2ciryxkze.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gt2tgocxdmr.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gt2mtrztqet.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.havefunace.top/Article/details/gt2eodqfnjz.html

[Q51] 用子查询更新
来源：http://dali.yonumen.top/Article/details/gt2xlqrrbfp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.mhx1999.top/Article/details/gt2woyjmvbz.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gt2ieuksgry.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gt2oygmuxhm.html

[Q53] 按条件删除
来源：http://dali.hysaishi.cn/Article/details/gt2cithnspj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oaqalcrg.html

[Q54] 清空表
来源：http://dali.fengsongda.top/Article/details/gt2qzrlgexf.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gt2bcyjrrpf.html

[Q55] 排名（并列占位）
来源：http://dali.hysaishi.cn/Article/details/gt2kdizhgah.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cashguo.top/Article/details/gt2oonybqvt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.0kj1m.cn/Article/details/gt2dhhkzxmg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gt2uwyvshvq.html

[Q57] 行号
来源：http://dali.ehwqpu.com/Article/details/gt2hjajdltn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2doznkmrb.html

[Q58] 累计求和
来源：http://dali.havefunace.top/Article/details/gt2scbwqwhq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2hccrgjbi.html

[Q59] 分组内累计
来源：http://dali.shzxlz.cn/Article/details/gt2taqzdwkw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2kplpxfem.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gt2cscgtnuj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gt2reeiwryh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2yrbbdunu.html

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gt2mfjdpkzs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2xnjrziar.html

[Q62] 分组占比
来源：http://dali.yonumen.top/Article/details/gt2wszzriil.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2lzfdkxfs.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gt2asyrrypj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aibaodan.cn/Article/details/gt2wmflwssv.html

[Q64] 提交事务
来源：http://dali.jqgfzy.top/Article/details/gt2wciqsqsb.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmqauzab.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gt2btjxxbhx.html

ROLLBACK;
来源：http://dali.sxryk.cn/Article/details/gt2tyqehcql.html

[Q66] 行锁查询
来源：http://dali.aizwys.cn/Article/details/gt2ihjmsbys.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.kuanghao11.cn/Article/details/gt2mbgbpyxb.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gt2crycscbe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hammf.cn/Article/details/gt2whaglbie.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gt2szcvdsqn.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yojmaxkx.html

ROLLBACK TO sp1;
来源：http://dali.hysaishi.cn/Article/details/gt2qpqqnbei.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gt2vmcguyth.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ppjwa.cn/Article/details/gt2awhdvayh.html

[Q70] 更新统计信息
来源：http://dali.yanxiufei.cn/Article/details/gt2jblbjpra.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gt2vicadjsi.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gt2trmuncww.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gt2abneiozu.html

[Q72] 查看索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqqokwoh.html

SHOW INDEX FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2bzgyflan.html

[Q73] 查看表状态
来源：http://dali.bjfxy.top/Article/details/gt2yjtdfgzx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pycfn.com/Article/details/gt2sozlgnhs.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gt2ezplsmrf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gt2vegefowx.html

[Q75] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gt2yhyzbqdy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2wavwhync.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xziqi.cn/Article/details/gt2qndvefzs.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gt2bfunbjzh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kugzljby.html

[Q77] 时间加减
来源：http://dali.tanke756.top/Article/details/gt2hqhftobf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gt2wvudljvk.html

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gt2krnbveqx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gt2gvaqtgcs.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwrozibl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuxming.cn/Article/details/gt2vjetdkvb.html

[Q80] 字符串截取
来源：http://dali.guannengcc.top/Article/details/gt2aowpmuxi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2jszjwswr.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmdpcdps.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.316326.xyz/Article/details/gt2slgzbaxz.html


<!-- 参考信息 -->