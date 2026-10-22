代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258.top/Article/details/gtqthowstp.html

C#:   lock (gate) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtcecrfmzt.html

[O04] 定义异步函数并等待
来源：http://dali.gaohongyu789.top/Article/details/gtyufzrqkc.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gtvaopojbl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.redwolf501.top/Article/details/gtorbovxbg.html

JS:   async function f() { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtnltaexes.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gtougipiab.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gtazrilksb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ppjwa.cn/Article/details/gtrnhdvkbq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.vqdsnc.cn/Article/details/gtspqthzaa.html

C#:   async Task F() { await G(); }
来源：http://dali.c1oappe.top/Article/details/gtotormzdu.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnxiangtu.top/Article/details/gtabudnmvh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gtnfvyerct.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhengqikj.top/Article/details/gtqbrjvmff.html

JS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gtuajuqqsk.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtwvwjukag.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258.top/Article/details/gtgagqetsy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenzaomai.com/Article/details/gtqocgqamj.html

Ruby: threads.map(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtxlpxbqle.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gtpcopeain.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gtrusrjife.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jiagoushi.top/Article/details/gtfbvpebzp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gtqnkxxlmu.html

JS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtjlaftclb.html

TS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtqrqvwpdz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fengsongda.top/Article/details/gtzsafkqbv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gtvohextwe.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gtwudytyhl.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gtldkbrzru.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqfnqzpz.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gtkkdcwaxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtelvqhtpg.html

[P01] 生成 UUID
来源：http://dali.yueranfly.top/Article/details/gtptceufhu.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gtnuafgmtu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gteazhyatg.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfialhivm.html

TS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtjbpwknig.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtcqagnvfj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuxming.cn/Article/details/gtzvacujgh.html

Ruby: SecureRandom.uuid
来源：http://dali.kuanghao11.cn/Article/details/gtdqvqqfse.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.vqdsnc.cn/Article/details/gtjebhpbml.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gtejwvliwj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gtaakocvnv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.iojbl.cn/Article/details/gthgqhplxr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daxiang520.top/Article/details/gttrqgtmvx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yangfankeji.com/Article/details/gtmmjoewho.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtvmrwiway.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gtdfhwcawq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtljxossdz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.smart0.xyz/Article/details/gttgpxwstg.html

[P03] 生成短随机字符串
来源：http://dali.meibo888.top/Article/details/gtghyhjxic.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gthvmofpul.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzbqymwb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtlcyibudo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gtcxhvorhn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yongpay.top/Article/details/gtmphnacod.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gtxnbgadbx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgufenzy.top/Article/details/gtcagngzds.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gtymywvgtt.html

[P04] 求长度
来源：http://dali.pycfn.com/Article/details/gtubmwlpks.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.andypj.xyz/Article/details/gtmjukjxap.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtoqbfwtqg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gtpzdlcuyk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtxhgvaioq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtlgavpukx.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gtkqwcqfqs.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gtenzhuahb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtthqbmudb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ydzc1.top/Article/details/gtujyzjksi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gtzwnnkjsc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gtgrtpbbcb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dashuyun.cn/Article/details/gtgmexitaj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxsbrrjw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jyoumei.cn/Article/details/gtxjjykcet.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtdozndetz.html

Ruby: a == b
来源：http://dali.xylfe.cn/Article/details/gtuqkgmdli.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hysaishi.cn/Article/details/gtnruvktpn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gteyuyicbk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gttnbypbaz.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gtpsbwwqby.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.bjfxy.top/Article/details/gtvpjwtuou.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gtwkldcqgn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxkjbymba.html

Go:   if x == nil {}
来源：http://dali.dashuyun.cn/Article/details/gtttxrvgin.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenlongwang.top/Article/details/gtnnnvtdwv.html

C#:   if (x is null) {}
来源：http://dali.hnqzz.top/Article/details/gtjciobxck.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gtnelscupn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gtdmkcymtm.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gtzwhfgrpk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtuawwcgdc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtmrjngsko.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gtcyzlpztj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gtcnilaxql.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xziqi.cn/Article/details/gtaosvmaxu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gtzvayycbe.html

[P08] 处理浮点精度问题
来源：http://dali.birdmap.top/Article/details/gtaafqykdg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.redwolf501.top/Article/details/gtfqvdqujv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.c1oappe.top/Article/details/gticqwspgv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nwbrower.top/Article/details/gtbcvtsjfq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gthvxtymvx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gtqosrfqxe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gtimetuabq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ehwqpu.com/Article/details/gtdfkarkxh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuanzx.com/Article/details/gtzafvtgcn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtuwyjwmwy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shangyingyoupin.top/Article/details/gtuhquxfhw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtnyliqrrk.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gtyvmebuhc.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtptynddtl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtowifyazg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gtpzywdmgy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnzqcufe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258.top/Article/details/gtvudxzgbl.html

);
来源：http://dali.daxiang520.top/Article/details/gtwaioohko.html

[Q02] 创建带外键的表
来源：http://dali.shzxlz.cn/Article/details/gtkameswdo.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gtvzquksje.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtkbiovtnc.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtetahylys.html

amount DECIMAL(10, 2),
来源：http://dali.gzhubu.top/Article/details/gtzbgwxvac.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangdashe.top/Article/details/gttbaymsmw.html

);
来源：http://dali.xinyue.icu/Article/details/gtblqjmslz.html

[Q03] 增加列
来源：http://dali.xziqi.cn/Article/details/gtnqdlrkst.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cdnleiting.top/Article/details/gteaynyhvs.html

[Q04] 修改列类型
来源：http://dali.yangfankeji.com/Article/details/gtwvcfbhbe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtozeybmnr.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gtdycigflh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sxryk.cn/Article/details/gtfbxmapaq.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtqlupmpdo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.kuanghao11.cn/Article/details/gtmzmkupei.html

[Q07] 删除表
来源：http://dali.iojbl.cn/Article/details/gthiapldin.html

DROP TABLE IF EXISTS orders;
来源：http://dali.quarkkingdee.top/Article/details/gtycchbryl.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gttryzhrco.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtndmdtzab.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gttordvkoj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtazjvcben.html

[Q10] 插入单行
来源：http://dali.yuanzhike.top/Article/details/gtdtsrsmos.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtzuhdzfoc.html

[Q11] 一次插入多行
来源：http://dali.dashuyun.cn/Article/details/gtighsdccg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtjzxwxgjz.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtpzakjjes.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gtninepdry.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.quarkkingdee.top/Article/details/gtweehichq.html

[Q13] 忽略重复插入
来源：http://dali.gogol.net.cn/Article/details/gthopzufut.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtspahyyju.html

[Q14] 存在则更新（upsert）
来源：http://dali.ivvv.top/Article/details/gtjagefieq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gtjdirwjru.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aizwys.cn/Article/details/gtjftqbmsk.html

[Q15] 查询全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvohnfad.html

SELECT * FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtpkwjnlsm.html

[Q16] 查询指定列
来源：http://dali.smart0.xyz/Article/details/gtzznunfyc.html

SELECT id, name FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtkmhlan.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gtlmhdpsko.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuxming.cn/Article/details/gtstmxzfuj.html

[Q18] 模糊匹配
来源：http://dali.birdmap.top/Article/details/gtfnmdafnw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jyoumei.cn/Article/details/gtgbiyfyfy.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gttteggwhi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ivvv.top/Article/details/gtlvxmhetl.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gtxrytsift.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtevsxeyxk.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gtaxineowi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aizwys.cn/Article/details/gtnkmpmqgu.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gtilkpephv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gttalbeplf.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gtsrfkjgzu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gtmikzsrxd.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gtelumbaok.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtdfwftlgg.html

[Q25] 只取前 N 条
来源：http://dali.yueranfly.top/Article/details/gtpbgtumka.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fzhhl.top/Article/details/gtlqogixmp.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gtewsldtbg.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gttjtcjwgi.html

[Q27] 条件计数
来源：http://dali.havefunace.top/Article/details/gttnbatxzr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtcdtwgahv.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gthbjbjliv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtkqgqyyee.html

[Q29] 最大最小值
来源：http://dali.tianlin.xyz/Article/details/gtuuneckan.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtxzymznoy.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gtwmiuplsi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtfxcfihlq.html

[Q31] 分组后过滤
来源：http://dali.wangdashe.top/Article/details/gtjxkiiydo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxusjmxl.html

[Q32] 分组拼接字符串
来源：http://dali.yuxming.cn/Article/details/gttehngfmi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtaoveacub.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fengsongda.top/Article/details/gtcjccsosm.html

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gthrsioorn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gtvlfzilga.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gtnrvjntts.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gtefhhqqjm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnqzz.top/Article/details/gtjweyrims.html

) t WHERE rn = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtjdkctdrx.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiessojex.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtxkkqwufo.html

[Q36] 左连接
来源：http://dali.gaohongyu789.top/Article/details/gtgimbowml.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtxjcoitgu.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gtbvrdutyv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sxryk.cn/Article/details/gtejevjkcs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuanzhike.top/Article/details/gtkqqdekat.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyghlupkh.html

[Q39] 自连接（查上下级）
来源：http://dali.cashguo.top/Article/details/gtdytmxwfi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gtavregdvg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.quarkkingdee.top/Article/details/gtrgyjackw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gtgglhuktd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sysykeji.top/Article/details/gtmvladaan.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gtxqiciwya.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gtudgtshpj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gtipvudecn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtzpnqaewb.html

[Q42] 连接条件附加过滤
来源：http://dali.yuxming.cn/Article/details/gtxohoxwnw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpjwhlpz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtetszylmm.html

[Q43] 标量子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlevoful.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hongshengwenyu.top/Article/details/gtbadiwhmw.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gtdjwoiigm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nwbrower.top/Article/details/gtnriimyaa.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gtrisjhtip.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gtlijigary.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gthgtestge.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtlzjktoud.html

[Q47] 与平均值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtcdebpeqv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gtvafjplgb.html

[Q48] CTE 公用表表达式
来源：http://dali.dianchejie.cn/Article/details/gtwknjplis.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cucudq.cn/Article/details/gtdmjosmwp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gtvlecofuz.html

[Q49] 更新单行
来源：http://dali.jiagoushi.top/Article/details/gthlcvbezx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gtenhewnec.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gtfqoxamkm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gtgcqoujwr.html

[Q51] 用子查询更新
来源：http://dali.cqqwz.cn/Article/details/gtgkzvmqgn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxinkj.top/Article/details/gtxcolqzac.html

[Q52] 删除指定行
来源：http://dali.cucudq.cn/Article/details/gtcehektfh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtchszxpgm.html

[Q53] 按条件删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylgscfbm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shuidangran.top/Article/details/gtdkrxvdhh.html

[Q54] 清空表
来源：http://dali.yuxming.cn/Article/details/gtmfaplgvx.html

TRUNCATE TABLE logs;
来源：http://dali.hnqzz.top/Article/details/gtbvrnwrrw.html

[Q55] 排名（并列占位）
来源：http://dali.smart0.xyz/Article/details/gtdhmpwigg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.birdmap.top/Article/details/gthcakycwu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gtrccqbpas.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gtivjudily.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gtpxxkimiy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gthgkczcyh.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gtwbvkaudz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtrslmljnd.html

[Q59] 分组内累计
来源：http://dali.ivvv.top/Article/details/gtwkkiwdyx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtfitvgzcw.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnqzz.top/Article/details/gtvrhluqtg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.mhx1999.top/Article/details/gtfalkpifr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gthgieuarj.html

[Q61] 移动平均
来源：http://dali.shangyingyoupin.top/Article/details/gtumdutwic.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtmqmhfkis.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gtxjuipgiq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtepmsscfo.html

[Q63] 开启事务
来源：http://dali.tian-w.cn/Article/details/gtlwmipncv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258.top/Article/details/gtqcqwjpse.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gtjvmeqmuw.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gtffrszuhr.html

[Q65] 回滚事务
来源：http://dali.sysykeji.top/Article/details/gtirrcjdxc.html

ROLLBACK;
来源：http://dali.havefunace.top/Article/details/gtxpwpskye.html

[Q66] 行锁查询
来源：http://dali.cheryme.top/Article/details/gtczhnfcxq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fengsongda.top/Article/details/gtrymrdezu.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gtoytachru.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yueranfly.top/Article/details/gtfombratb.html

[Q68] 保存点
来源：http://dali.cheryme.top/Article/details/gtvvqurvjl.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gtpdyuhsuk.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gtbxffkyyu.html

[Q69] 查看执行计划
来源：http://dali.hnxiangtu.top/Article/details/gtqtvrnuhy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gtmmdzamad.html

[Q70] 更新统计信息
来源：http://dali.ivvv.top/Article/details/gtiiigjmuv.html

ANALYZE TABLE users;
来源：http://dali.cdnleiting.top/Article/details/gtisauuwjr.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gtbpzrjmlw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnfrmslu.html

[Q72] 查看索引
来源：http://dali.0kj1m.cn/Article/details/gtsleuyywp.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtnjzszhoq.html

[Q73] 查看表状态
来源：http://dali.fzhhl.top/Article/details/gtupjxzucs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258.top/Article/details/gtmsdtwvlc.html

[Q74] 强制使用索引
来源：http://dali.xuetiantiany.cn/Article/details/gtsouollng.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sufxvd.cn/Article/details/gtdpdhnqye.html

[Q75] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtorflrhpv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvebrbppu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gtoaeonzmn.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gtsimrbxmf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zycfv.cn/Article/details/gtsmttncgw.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gtpevrdcjm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ivvv.top/Article/details/gttfsrncjx.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gtegvyfyiz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyrczwff.html

[Q79] 字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gthixfkgrp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ybcxt.top/Article/details/gtbiszrykl.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gtisurfmie.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtfaqrvzqn.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtfidmvnuq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtifzjwniv.html

[Q82] 字符长度与字节长度
来源：http://dali.meibo888.top/Article/details/gtwcqqldds.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtwalggzoe.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtqrcyxnyf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtqsmocasf.html

[Q84] 去除首尾空格
来源：http://dali.9152youxi.cn/Article/details/gtohzcdlks.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtnndclgwc.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsdrwjci.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnxiangtu.top/Article/details/gtmmdzjvqx.html


<!-- 参考信息 -->