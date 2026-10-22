代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gtznonhhwf.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtqdfphkpq.html

Java: synchronized (this) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gtptcogxyc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gtbcswfwkx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtizbkypec.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtmtzixcqe.html

[O04] 定义异步函数并等待
来源：http://dali.cucudq.cn/Article/details/gtanafbtcf.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gtrzizfcrk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvxgztdy.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gtocmnkknm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtgqloxfgj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zycfv.cn/Article/details/gtzrwraugr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gtszvatdrf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jyoumei.cn/Article/details/gtqxbjzlbg.html

C#:   async Task F() { await G(); }
来源：http://dali.daria6918.cn/Article/details/gtcqpnsvso.html

[O05] 并发执行并等待全部完成
来源：http://dali.guannengcc.top/Article/details/gteihitmln.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zdqjudy.top/Article/details/gtthtpbklu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgowhivg.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtttheasuj.html

TS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtlcefejws.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ppjwa.cn/Article/details/gthydamsrs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pengpengdd.cyou/Article/details/gtcenjkqjg.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gtymamrsnf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuxvinuo.html

[O06] 使用进程池
来源：http://dali.xziqi.cn/Article/details/gtpnoyfayd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guannengcc.top/Article/details/gtlxpjqbcl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sweek.top/Article/details/gtugcciipa.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtkurstxed.html

TS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gtuwromwve.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gtdahiohdl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xziqi.cn/Article/details/gtezoqeeza.html

Ruby: // fork 块
来源：http://dali.dashuyun.cn/Article/details/gtpjlydtwc.html

C#:   Parallel.For
来源：http://dali.jinqigufen.top/Article/details/gtpydjrbwx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtbiocbqsm.html

P. 常用工具函数
来源：http://dali.mhx1999.top/Article/details/gtrxvcfkri.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtmalsekuh.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gtlpohbjbt.html

Py:   str(uuid.uuid4())
来源：http://dali.yongpay.top/Article/details/gtlkubpljs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gtlynhkfmc.html

JS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtnjirfmaw.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gtnujxjzzj.html

Java: UUID.randomUUID().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtuphbjfsv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zycfv.cn/Article/details/gtpxioqybt.html

Ruby: SecureRandom.uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtpyjyitgp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenzaomai.com/Article/details/gtdibfuvsc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jiagoushi.top/Article/details/gtaxvqnsah.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.svipenyu.cn/Article/details/gtzvxbbjkm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gtdenzbttl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.havefunace.top/Article/details/gtgomogqlg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gtoganpnva.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aizwys.cn/Article/details/gtivwlpsqx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gtbjovxqts.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gticmnygit.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258888.top/Article/details/gtidpgndkh.html

[P03] 生成短随机字符串
来源：http://dali.xuanzx.com/Article/details/gtqdtojcfy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gtzxvgmyqi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jlsjyb.cn/Article/details/gtswajugxo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gttuhpavtq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtbafyyvnz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gtgocxlwpz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gtwkutquop.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gtcihikcxf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gttdsfrbkq.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtyemvcuwq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yongpay.top/Article/details/gtdgboynjy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfznafprt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtlbutgocg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtsagmouak.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtppkhhlkn.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gtdbcfhcye.html

Ruby: x.length;  x.size
来源：http://dali.yj20258888.top/Article/details/gtysspkepx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtxuavuuou.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxinkj.top/Article/details/gtcrjlcyba.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gtnzmqsuhq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.meibo888.top/Article/details/gtuyeieunr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guowangkeji.top/Article/details/gtodrqeodh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtkdgafabi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gtaescwnjx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtuqqmfbze.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gtjkxeqiqk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tian-w.cn/Article/details/gtitcxsytz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj202588.top/Article/details/gtzltbhlhw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljxryiuc.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gthlmgfzpl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangdashe.top/Article/details/gtxrzgfhhz.html

TS:   if (x == null) {}
来源：http://dali.smart0.xyz/Article/details/gtkdmywogi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtahuosuwk.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gtksxtmtdp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gtvrzhoqif.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gttjarzaic.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gthezmdvwv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gtvbwhadan.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gtywhblxgk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtykztttdy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtnfucpkgr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxguhreed.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gttmpkugeb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gtafogffdz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.wangshuangyany.cn/Article/details/gtlchlosmc.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gttpoehqqb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gtojthtlnc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ivvv.top/Article/details/gtccunxeme.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.haohaochexian.top/Article/details/gtfwdkkssz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtygqxttkt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gtagoimrun.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuetiantiany.cn/Article/details/gtpyrjjhkg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gttejgougb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gtdhsoozfu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnmydzquf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gthxupegqg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrfvmntxn.html

[Q01] 创建表
来源：http://dali.wangdashe.top/Article/details/gtpihyfcjz.html

CREATE TABLE users (
来源：http://dali.yuanzhike.top/Article/details/gtdjzmfmop.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtmxooxake.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gtxrmhqcos.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangshuangyany.cn/Article/details/gtvipdwkhq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.9152youxi.cn/Article/details/gtrtucrmla.html

);
来源：http://dali.gzhubu.top/Article/details/gtmyikuagk.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gtmglqhvvn.html

CREATE TABLE orders (
来源：http://dali.vqdsnc.cn/Article/details/gtndvtpedb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtfyxbrgim.html

user_id INT NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gthatemlmj.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gttxtmxzez.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gtzaumanpt.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwhbrmtf.html

[Q03] 增加列
来源：http://dali.jyoumei.cn/Article/details/gtlqodgwjy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gtbywwlohx.html

[Q04] 修改列类型
来源：http://dali.zhengqikj.top/Article/details/gttexzgwwm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yueranfly.top/Article/details/gtypjfjesx.html

[Q05] 重命名列
来源：http://dali.gotoacloud.top/Article/details/gttfscsfzb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gtqekzxrnz.html

[Q06] 删除列
来源：http://dali.hnqzz.top/Article/details/gtdcvnwouc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gtrtbxvbtx.html

[Q07] 删除表
来源：http://dali.shanyushiyangtech.top/Article/details/gthmfcmmfa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.haohaochexian.top/Article/details/gtdylkjjgb.html

[Q08] 创建普通索引
来源：http://dali.tian-w.cn/Article/details/gtipsrsqam.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtpiaqhozv.html

[Q09] 创建唯一索引
来源：http://dali.316326.xyz/Article/details/gtyhbkwcwc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gtcbtuanbd.html

[Q10] 插入单行
来源：http://dali.gogol.net.cn/Article/details/gtbdbytwyt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xinyue.icu/Article/details/gtmcopoiqv.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtzngbogqg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtutjxpngw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhoulong.xyz/Article/details/gtkpapubjf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gtasladfyo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guannengcc.top/Article/details/gtrmmvqwsz.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gtnvvkhzkc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtwttjsyni.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenlongwang.top/Article/details/gtvkosatat.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangshuangyany.cn/Article/details/gtxlspqodw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangdashe.top/Article/details/gtynikzcci.html

[Q15] 查询全部
来源：http://dali.jinqigfzy.top/Article/details/gtfsdtvgsj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtieshutiv.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gtojikgbvd.html

SELECT id, name FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtdzqhwinj.html

[Q17] 条件查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzikcbnbz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gttlcafdss.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctnuasie.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gtnwvmwgyj.html

[Q19] 范围查询
来源：http://dali.snrcjt.cn/Article/details/gtnmyirrkm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gtuqedsfnk.html

[Q20] IN 列表
来源：http://dali.nanxinkj.top/Article/details/gtlkredyto.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gtqfxntqnl.html

[Q21] 空值判断
来源：http://dali.sweek.top/Article/details/gtgtqojtwh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gtfwovckhi.html

[Q22] 排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduzxdwhh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gtejqxpqux.html

[Q23] 分页
来源：http://dali.cqqwz.cn/Article/details/gtqfoymeur.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.redwolf501.top/Article/details/gtscynlyed.html

[Q24] 去重
来源：http://dali.tian-w.cn/Article/details/gtcbspmlfo.html

SELECT DISTINCT city FROM users;
来源：http://dali.yongpay.top/Article/details/gtabasfbnj.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gtojnpqlsq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dianchejie.cn/Article/details/gtdnyhaccf.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gtwheintem.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtotgbwiiz.html

[Q27] 条件计数
来源：http://dali.wangshuangyany.cn/Article/details/gtpaimwyfp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtaxzsbkju.html

[Q28] 求和与平均
来源：http://dali.cqqwz.cn/Article/details/gtmwgplsaw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtrinxhyqa.html

[Q29] 最大最小值
来源：http://dali.snrcjt.cn/Article/details/gtwwiepbaj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtzoyijgqc.html

[Q30] 分组统计
来源：http://dali.jinqigufen.top/Article/details/gtuiosoryh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtwkdnsfgo.html

[Q31] 分组后过滤
来源：http://dali.yueranfly.top/Article/details/gtfrzlingy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.316326.xyz/Article/details/gtjtjfmbgp.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgugrdhyo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtyxrikirx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aibaodan.cn/Article/details/gtukzdxivd.html

[Q33] 多列分组
来源：http://dali.zhoulong.xyz/Article/details/gtrdxcmyin.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gttdgowvkt.html

[Q34] 每组取第一条
来源：http://dali.ywan-chungtsiang.top/Article/details/gteplumnbc.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gtfectcyiw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.svipenyu.cn/Article/details/gtwnkcxhfc.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtwgquhoyy.html

[Q35] 内连接
来源：http://dali.redwolf501.top/Article/details/gtigzxjtux.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtspqfykul.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gtyasgdapl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gthyvakavs.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gtkgyislmo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yangfankeji.com/Article/details/gtknidzijt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gtdhpflryb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.meibo888.top/Article/details/gtmjbpcwvr.html

[Q39] 自连接（查上下级）
来源：http://dali.hongshengwenyu.top/Article/details/gtwovwfkhx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuozoxxx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtjarstrfg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aizwys.cn/Article/details/gtelwquzwy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkuqjsyjf.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqejhasws.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zdqjudy.top/Article/details/gtamdhqhsi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dianchejie.cn/Article/details/gtidghgbjl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gaohongyu789.top/Article/details/gtpnubafye.html

[Q42] 连接条件附加过滤
来源：http://dali.yuanzhike.top/Article/details/gtpyxjibha.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jianghu66.top/Article/details/gtjsoozhyo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gotoacloud.top/Article/details/gtxxayauxe.html

[Q43] 标量子查询
来源：http://dali.zhongyouzk.top/Article/details/gtdwqezfeo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhengqikj.top/Article/details/gtwjbnkrng.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gtbwuyzrui.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gtbfqagpsg.html

[Q45] EXISTS 判断存在
来源：http://dali.snrcjt.cn/Article/details/gtdcgqqyev.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtieijkjgq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhiwuduotai.top/Article/details/gtxrvjfzbg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gtucgasrov.html

[Q47] 与平均值比较
来源：http://dali.jiagoushi.top/Article/details/gttagowjie.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gtscshtdgn.html

[Q48] CTE 公用表表达式
来源：http://dali.andypj.xyz/Article/details/gtgudnarnh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hysaishi.cn/Article/details/gtcyqxpkzz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gtnzfqgnvo.html

[Q49] 更新单行
来源：http://dali.cheryme.top/Article/details/gtmqulvmkk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtnadkeiyf.html

[Q50] 批量更新
来源：http://dali.sxryk.cn/Article/details/gttcaqmecw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtyfercpsk.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gtuqtujbah.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dianchejie.cn/Article/details/gtubimaiog.html

[Q52] 删除指定行
来源：http://dali.quarkkingdee.top/Article/details/gtsrsdcluf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtrgtnhwmm.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gtxcsfbcpl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gteaizlzwn.html

[Q54] 清空表
来源：http://dali.wangdashe.top/Article/details/gtgkprprgl.html

TRUNCATE TABLE logs;
来源：http://dali.sysykeji.top/Article/details/gtydsrdpgn.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gtdjmufjge.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtvicwvpno.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtiibdptzs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsiqogepi.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gtkvgfnkfl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gtyaqgnpmn.html

[Q58] 累计求和
来源：http://dali.quarkkingdee.top/Article/details/gteuydqsdf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtjimcwxol.html

[Q59] 分组内累计
来源：http://dali.cashguo.top/Article/details/gtgsuawisd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpjmeddx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gtewluvoxl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gtyudyqtoo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtccdahnne.html

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gtmzwsmiwi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sweek.top/Article/details/gtgeggjxua.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gtqrgfvyau.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtdhsvtqok.html

[Q63] 开启事务
来源：http://dali.pycfn.com/Article/details/gtzfbzvjxq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yanxiufei.cn/Article/details/gtgroizxja.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gteeshhckn.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gtougrtmsv.html

[Q65] 回滚事务
来源：http://dali.xuetiantiany.cn/Article/details/gthnqwabmt.html

ROLLBACK;
来源：http://dali.nanxinkj.top/Article/details/gtnxnysotv.html

[Q66] 行锁查询
来源：http://dali.cqqwz.cn/Article/details/gtplpqdkgs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gtzhnrcngg.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gtpzumtzpc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigfzy.top/Article/details/gtcdihafel.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gtyocsdpwz.html

SAVEPOINT sp1;
来源：http://dali.316326.xyz/Article/details/gthnqidmol.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gtzvzcmxkn.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gtbgqbtppd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqiftghax.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gtkswwrgew.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtuaskspqw.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gtghsjlfxl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gttmvqvogl.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gtxbqaclhx.html

SHOW INDEX FROM users;
来源：http://dali.iojbl.cn/Article/details/gtrbblptdl.html

[Q73] 查看表状态
来源：http://dali.xylfe.cn/Article/details/gtiylcedjv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwzugyqs.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtmvsckwwz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ybcxt.top/Article/details/gtrbvjeqaq.html

[Q75] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtyioruxvj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gtandnacea.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.birdmap.top/Article/details/gtqwjgdfmr.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gtjqwaltsc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zycfv.cn/Article/details/gtjhfqfyaj.html

[Q77] 时间加减
来源：http://dali.pengpengdd.cyou/Article/details/gtrbmjtcxk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.svipenyu.cn/Article/details/gthmaupyxd.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gttlhduqcc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gogol.net.cn/Article/details/gtzylashre.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gtpjprzsfn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.vqdsnc.cn/Article/details/gtgobfchui.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gtwbqmfxdp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtzlngyyhs.html

[Q81] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gtbuvpvdrr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj202588.top/Article/details/gtcgwsizko.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gtrymtingp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtelsjuqsl.html

[Q83] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtcynlqavr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtjvcgxylb.html


<!-- 参考信息 -->