代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtmqxkfiyi.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gtayevqrmy.html

[O04] 定义异步函数并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtqglppieu.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gtedrlgmyc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gtxvohftel.html

JS:   async function f() { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtpqhrshnq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtuyablsju.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gtxyfpyugn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhiwuduotai.top/Article/details/gtsytveazw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gtnvkjmfna.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gtouymuryc.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gthmrqburx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yvedp.cn/Article/details/gtgkviwgyo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cheryme.top/Article/details/gtyxaprlie.html

JS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gtmucttvam.html

TS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtunssbfnp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqvbyciy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nwbrower.top/Article/details/gtwkoqukhw.html

Ruby: threads.map(&:join)
来源：http://dali.birdmap.top/Article/details/gtxqbrudem.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gzhubu.top/Article/details/gtxscoeqtq.html

[O06] 使用进程池
来源：http://dali.xuetiantiany.cn/Article/details/gtwpixsusy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobaewmmn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sysykeji.top/Article/details/gtlpwqwkot.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtiacfzkjj.html

TS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtzxdpurtq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gtiresrmbn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yangfankeji.com/Article/details/gtkxshqgbl.html

Ruby: // fork 块
来源：http://dali.redwolf501.top/Article/details/gtglhdbmkq.html

C#:   Parallel.For
来源：http://dali.aizwys.cn/Article/details/gtxuookjnh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtoqjwzrlk.html

P. 常用工具函数
来源：http://dali.316326.xyz/Article/details/gtwcarepww.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtddqllxat.html

[P01] 生成 UUID
来源：http://dali.pycfn.com/Article/details/gtwatseyfm.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gtzwwsybds.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtlfoerimd.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtovuffoie.html

TS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtmstidfwx.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gtkxiialof.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jianghu66.top/Article/details/gtqbewaqcf.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gthpsrlrfm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhengqikj.top/Article/details/gtrfsqjlup.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gtjtsurapn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gtwhvrawhf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.quarkkingdee.top/Article/details/gtngofuxkz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.birdmap.top/Article/details/gthnobmlow.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ybcxt.top/Article/details/gtylwlfsrb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtbbqtboix.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.9152youxi.cn/Article/details/gtnkfbzgaz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hfpthk.cn/Article/details/gtoekvbxix.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hongshengwenyu.top/Article/details/gtpkpzptdc.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gtuzjydbbi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gtnbsizcrg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpmbvnxs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gtqxpazkbc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtrjrdgidn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gtftuamqqi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gtklonyxef.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuahfmrxt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aibaodan.cn/Article/details/gtoagebnzy.html

[P04] 求长度
来源：http://dali.fengsongda.top/Article/details/gtmmraukif.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gtiifxngzg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtscweoqlf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtithegoir.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtgnrjcrxg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gthzivxlzt.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigufen.top/Article/details/gtajcljxwq.html

Ruby: x.length;  x.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsduwlbzt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtrkvhahkt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hammf.cn/Article/details/gtxtbuesql.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gtbsvfbxlh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.0kj1m.cn/Article/details/gtwubwzlmv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigfzy.top/Article/details/gttkdbbsfo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gtmgtfehnx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aizwys.cn/Article/details/gtcwtjogco.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gtzmsgebua.html

Ruby: a == b
来源：http://dali.chenjidiqi.icu/Article/details/gturshgmxa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fzhhl.top/Article/details/gtotbuldys.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gteezmbpsl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhongyouzk.top/Article/details/gtvbcoxvot.html

PHP:  if (empty($x)) {}
来源：http://dali.dianchejie.cn/Article/details/gtebghhbgj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aibaodan.cn/Article/details/gtaqisawil.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gttixtajgj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gtvztpkwwy.html

Go:   if x == nil {}
来源：http://dali.ydzc1.top/Article/details/gtvwclwrmf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcykwvwnq.html

C#:   if (x is null) {}
来源：http://dali.yj202588.top/Article/details/gtrsrrknma.html

[P07] 防抖与节流
来源：http://dali.sweek.top/Article/details/gtehcjssnb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gtgjsvsucm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gthbeywfkd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtzcdxrzdh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtfzmcsuia.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhixingplan.top/Article/details/gtybkhvrbo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.redwolf501.top/Article/details/gtpqnjsoki.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xziqi.cn/Article/details/gtlegclzha.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gtgafrrzox.html

[P08] 处理浮点精度问题
来源：http://dali.kuanghao11.cn/Article/details/gtzmhonxiw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cheryme.top/Article/details/gtpdvppuch.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtjjxidgyj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgfzy.top/Article/details/gtthyiovur.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtjbpaznop.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangshuangyany.cn/Article/details/gtjlftjthm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gtojjvkdpy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guannengcc.top/Article/details/gtkahpyfyr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ydzc1.top/Article/details/gttmhfxjez.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtivggwjey.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gtgozzbymj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtkcarttrw.html

[Q01] 创建表
来源：http://dali.xziqi.cn/Article/details/gtayviyufl.html

CREATE TABLE users (
来源：http://dali.zhixingplan.top/Article/details/gtzutkrssn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtixesawzd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtnwbtakdy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yongpay.top/Article/details/gttdtcgljl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.svipenyu.cn/Article/details/gtwawickjg.html

);
来源：http://dali.jianghu66.top/Article/details/gtpcoiairs.html

[Q02] 创建带外键的表
来源：http://dali.jlsjyb.cn/Article/details/gtlvnfatyf.html

CREATE TABLE orders (
来源：http://dali.chenzaomai.com/Article/details/gtgqxbjaqe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtnbslkyux.html

user_id INT NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtaitvqvbf.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gtkisaybqy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gtgialfnqm.html

);
来源：http://dali.cdnleiting.top/Article/details/gtchrvmbbt.html

[Q03] 增加列
来源：http://dali.yvedp.cn/Article/details/gtzbpouhwd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuxming.cn/Article/details/gtcszbhnnk.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gtceouwcqu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gtfxynnqkw.html

[Q05] 重命名列
来源：http://dali.gogol.net.cn/Article/details/gtnpsexoxe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuanzhike.top/Article/details/gtysexxfib.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gtqgudoptk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fengsongda.top/Article/details/gtjnhgdbfg.html

[Q07] 删除表
来源：http://dali.zhixingplan.top/Article/details/gtlejbcitx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cdnleiting.top/Article/details/gtpapyojhi.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gtbdzjdrvd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gtwiwkksze.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gtdyadgtkr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gtbclyhbub.html

[Q10] 插入单行
来源：http://dali.yj20258.top/Article/details/gtmaojdvqd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjheonmq.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gtojbwlpfo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gttjvodpub.html

[Q12] 插入后取自增 ID
来源：http://dali.jiagoushi.top/Article/details/gtnvjpsszq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gthsvnfcei.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xziqi.cn/Article/details/gtugivbknx.html

[Q13] 忽略重复插入
来源：http://dali.jlsjyb.cn/Article/details/gtxluvhwfi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtznednyqn.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gtsqoglwah.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.haohaochexian.top/Article/details/gtmancwdaq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gtitqrrjcu.html

[Q15] 查询全部
来源：http://dali.jinqigfzy.top/Article/details/gtjrkeiuqh.html

SELECT * FROM users;
来源：http://dali.xuanzx.com/Article/details/gtoehqdztn.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgaywyyk.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtmisxbwne.html

[Q17] 条件查询
来源：http://dali.zdqjudy.top/Article/details/gtxripgvul.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrsujkea.html

[Q18] 模糊匹配
来源：http://dali.316326.xyz/Article/details/gtnaovvnwz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhoulong.xyz/Article/details/gtneuuwdvg.html

[Q19] 范围查询
来源：http://dali.zhongyouzk.top/Article/details/gtokdcblqo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gtigsswphq.html

[Q20] IN 列表
来源：http://dali.hysaishi.cn/Article/details/gtshxrjtfh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.svipenyu.cn/Article/details/gtzknottap.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gtyaexgqwn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cdnleiting.top/Article/details/gtxgyjmlcn.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gtjggkqxct.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenjidiqi.icu/Article/details/gtekbydnhw.html

[Q23] 分页
来源：http://dali.tian-w.cn/Article/details/gtprkklbnr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gtwpohdgah.html

[Q24] 去重
来源：http://dali.chenlongwang.top/Article/details/gtluxtysdp.html

SELECT DISTINCT city FROM users;
来源：http://dali.jianghu66.top/Article/details/gtdbwfvacg.html

[Q25] 只取前 N 条
来源：http://dali.smart0.xyz/Article/details/gtvyonblrm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gtdwfjebne.html

[Q26] 计数
来源：http://dali.shzxlz.cn/Article/details/gtqiwisvhg.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gtkfqodyjb.html

[Q27] 条件计数
来源：http://dali.hnxiangtu.top/Article/details/gtydlbtbuz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gtmqluscxg.html

[Q28] 求和与平均
来源：http://dali.yangfankeji.com/Article/details/gtimnpjymm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtjeakqyrj.html

[Q29] 最大最小值
来源：http://dali.yongpay.top/Article/details/gtszuahdrc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtnvpnzots.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gtfvmgrmkj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtzhhitkyy.html

[Q31] 分组后过滤
来源：http://dali.jqgfzy.top/Article/details/gtyvnmumcm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aibaodan.cn/Article/details/gtqlubrwhp.html

[Q32] 分组拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtpuzlddvx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtdfigjagp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.kuanghao11.cn/Article/details/gtmwalsgpt.html

[Q33] 多列分组
来源：http://dali.quarkkingdee.top/Article/details/gtotmlojwe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuaedaql.html

[Q34] 每组取第一条
来源：http://dali.sysykeji.top/Article/details/gtedrxwabe.html

SELECT * FROM (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwenxkqzi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gtpjwuctfh.html

) t WHERE rn = 1;
来源：http://dali.meibo888.top/Article/details/gtksrjnuvc.html

[Q35] 内连接
来源：http://dali.aibaodan.cn/Article/details/gtaqoxsazv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtwvbusnze.html

[Q36] 左连接
来源：http://dali.yueranfly.top/Article/details/gttswteuuw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtxooppnby.html

[Q37] 右连接
来源：http://dali.0kj1m.cn/Article/details/gtutubsosg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwclyrtf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhiwuduotai.top/Article/details/gtsgoxxxag.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cqqwz.cn/Article/details/gtfzqijmbe.html

[Q39] 自连接（查上下级）
来源：http://dali.gogol.net.cn/Article/details/gtjvzbzbxs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gtyhrxhfvl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gtdcmklvqf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj202588.top/Article/details/gtthidltjc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yonumen.top/Article/details/gtgdntkzlj.html

[Q41] 多表连接
来源：http://dali.hammf.cn/Article/details/gtejblsavs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gtfcazvnif.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbxedgxc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258.top/Article/details/gttfmmkqxl.html

[Q42] 连接条件附加过滤
来源：http://dali.fzhhl.top/Article/details/gtwoumtmjq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hysaishi.cn/Article/details/gtwrzxrpgi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhongyouzk.top/Article/details/gtetzkqhco.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gtwbqifcpc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gtmkdvumaj.html

[Q44] IN 子查询
来源：http://dali.ivvv.top/Article/details/gtojemajnw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gtssvswtjm.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gtkjbhdcyh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gtpokuzwqp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gtmirzytvo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtjhdfmvgg.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gttqljlyig.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tanke756.top/Article/details/gtkmfkurcq.html

[Q48] CTE 公用表表达式
来源：http://dali.aizwys.cn/Article/details/gtqssjrlys.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gttmhsfvzs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gtpniahpvy.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gttizxlxgn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gtievgnujn.html

[Q50] 批量更新
来源：http://dali.birdmap.top/Article/details/gtqxjpsinr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtjtwbvimn.html

[Q51] 用子查询更新
来源：http://dali.zhoulong.xyz/Article/details/gthmcfyjnw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daria6918.cn/Article/details/gtshedzarb.html

[Q52] 删除指定行
来源：http://dali.redwolf501.top/Article/details/gtnhicctku.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gthneqsrtc.html

[Q53] 按条件删除
来源：http://dali.yj202588.top/Article/details/gtkbvyjivd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gtbyjdwcgm.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gtokdxakzn.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gtlhmaxqty.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gteqmkiugc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtojlqtleo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gtuxpyudqa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daxiang520.top/Article/details/gtlmmhagga.html

[Q57] 行号
来源：http://dali.aizwys.cn/Article/details/gtbxcwlevv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.bjfxy.top/Article/details/gtobjpshhh.html

[Q58] 累计求和
来源：http://dali.jianghu66.top/Article/details/gtadxdobrj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtplbwhttw.html

[Q59] 分组内累计
来源：http://dali.svipenyu.cn/Article/details/gtcnwwopok.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gthbbzeaxz.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gtcpkgtnvn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gtysxtnjoo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtirtuszqp.html

[Q61] 移动平均
来源：http://dali.hnxiangtu.top/Article/details/gtmzvlasoe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtcptzssaj.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gtfeuwrwxj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtpuijlexb.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gtpvgoatqh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yanxiufei.cn/Article/details/gtyyabixew.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gtukoybdee.html

COMMIT;
来源：http://dali.havefunace.top/Article/details/gtyrzzocbd.html

[Q65] 回滚事务
来源：http://dali.guowangkeji.top/Article/details/gtzkpvdhme.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gtphagmuxp.html

[Q66] 行锁查询
来源：http://dali.xinyue.icu/Article/details/gtgodsxvkw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigufen.top/Article/details/gtffnjvlep.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gtwrnfkfjv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gtbosweuhh.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gtnijpmpfi.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtufjejrtu.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekxtuuss.html

[Q69] 查看执行计划
来源：http://dali.smart0.xyz/Article/details/gtvblzqfwc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yonumen.top/Article/details/gtfmfsfhei.html

[Q70] 更新统计信息
来源：http://dali.redwolf501.top/Article/details/gtikbumdgb.html

ANALYZE TABLE users;
来源：http://dali.yueranfly.top/Article/details/gtkjwumcat.html

[Q71] 查看建表语句
来源：http://dali.jinqigfzy.top/Article/details/gtkabqdayh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gtjpqkgbee.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gtwzsrhmgq.html

SHOW INDEX FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvtmdmvp.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gtiearsmnb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gtaegmdsal.html

[Q74] 强制使用索引
来源：http://dali.kuanghao11.cn/Article/details/gtgupaybzy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gtpjdnutth.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gttwlenuco.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtsjpfttzy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gtyfbisjcu.html

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gtiomifqaa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzzupzxe.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gthkhlheup.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gtxkrmrkap.html

[Q78] 当前时间
来源：http://dali.svipenyu.cn/Article/details/gttpzcmfbt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gtlasrxgmx.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtpoyehann.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangshuangyany.cn/Article/details/gtivwpcoya.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gtnsleiurs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtgbcxcqnb.html

[Q81] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtmjpxnfcr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtaetloktj.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtfimxelnx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gticepawbu.html

[Q83] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtjabhrvif.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtaflgegrq.html

[Q84] 去除首尾空格
来源：http://dali.hywenlv.cn/Article/details/gtwywpfpgn.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gthozisdhr.html

[Q85] 数值取整
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarbseexs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnqzz.top/Article/details/gtakiwpygg.html


<!-- 参考信息 -->