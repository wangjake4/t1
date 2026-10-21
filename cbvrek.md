代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gtluexobcb.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtxfkvgmqw.html

[O04] 定义异步函数并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtcpnvdopz.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gtmgvbwofg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gtctoieiqa.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gtpzsxsjpk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtrvfbtfvg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gtbnaaycet.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmniaozx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenjidiqi.icu/Article/details/gtdmfqvfvc.html

C#:   async Task F() { await G(); }
来源：http://dali.aibaodan.cn/Article/details/gtrhpqsubt.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gtqpwlxfhd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.c1oappe.top/Article/details/gtogwpbbbc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zdqjudy.top/Article/details/gtrjgcdjoa.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtvegytgug.html

TS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtnttokmqd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fzhhl.top/Article/details/gtfnyhcwzn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sufxvd.cn/Article/details/gtqfzucazs.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtiaxmrvpl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gtrvwvnbpv.html

[O06] 使用进程池
来源：http://dali.havefunace.top/Article/details/gtfnouclhx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gtfutjahmz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gaohongyu789.top/Article/details/gtbejtyfpk.html

JS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gthwwpcaau.html

TS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gtxrjeiaea.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aibaodan.cn/Article/details/gtscmqzwom.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.meibo888.top/Article/details/gtllwxmdik.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gtynzrpkyx.html

C#:   Parallel.For
来源：http://dali.hywenlv.cn/Article/details/gtuipyfwad.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkdqnjsuo.html

P. 常用工具函数
来源：http://dali.tian-w.cn/Article/details/gtenspnwrb.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraqvejjw.html

[P01] 生成 UUID
来源：http://dali.cheryme.top/Article/details/gtkxkkptve.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgfzy.top/Article/details/gtaykpbzrd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtbahqlqbu.html

JS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtllsnhrje.html

TS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtyuyaiwae.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gtdxqaslsj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gtqafyglsk.html

Ruby: SecureRandom.uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtepittlgo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.andypj.xyz/Article/details/gtlxokxsgp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ppjwa.cn/Article/details/gtldspohjw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258.top/Article/details/gtxstupuez.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cashguo.top/Article/details/gtenkkjgyo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gtktpiuhhd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hysaishi.cn/Article/details/gtsxqklzhf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtwbeykeid.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimttnvcu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cqqwz.cn/Article/details/gtowifxttt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gtqismmuhb.html

[P03] 生成短随机字符串
来源：http://dali.yangfankeji.com/Article/details/gtbxzbpbpi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gtpqrwzjeo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tanke756.top/Article/details/gtnvnociux.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtqequemel.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtjcdftqgj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhoulong.xyz/Article/details/gttfripnqj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cheryme.top/Article/details/gtkeohabcl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jiagoushi.top/Article/details/gtpkwninyf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shuidangran.top/Article/details/gtdlitgzpc.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gtgzmszlhf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gtyltohlbw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtdewgwhxz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtkhhurdtb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gtxgrtrpbp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtderfeeun.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsvdbvtc.html

Ruby: x.length;  x.size
来源：http://dali.mhx1999.top/Article/details/gtjdndisfa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtgkeueads.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gtjotksjem.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gtdwlfyuxk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gtytkrwhoh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gtcohpyslo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gtdgnzthrr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gtitoijahb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtbmnohbgk.html

Ruby: a == b
来源：http://dali.xuetiantiany.cn/Article/details/gtxvwvvxmn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtxkqifu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.redwolf501.top/Article/details/gttvdgbxqf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtplchsvjk.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigufen.top/Article/details/gtkfzjqgmn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cdnleiting.top/Article/details/gturizujcg.html

TS:   if (x == null) {}
来源：http://dali.jqgfzy.top/Article/details/gtotyczrhu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gtltxfyzgp.html

Go:   if x == nil {}
来源：http://dali.yangfankeji.com/Article/details/gtmbgvwqos.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cdnleiting.top/Article/details/gtlqdfzckm.html

C#:   if (x is null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtttnhlzsp.html

[P07] 防抖与节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdstxprvr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258888.top/Article/details/gtpkqaccoa.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gtczxrwqri.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtxvpprgue.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtpfqrutzd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gthrsrrhzp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gtzvystqoq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gtduiabhbh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gtqhcodubr.html

[P08] 处理浮点精度问题
来源：http://dali.redwolf501.top/Article/details/gtgzyqixcn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.aibaodan.cn/Article/details/gtpgvushiw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sweek.top/Article/details/gttuoxoaiy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gtiqdrddug.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gtouxcsdpj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gtelwzvqdr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.svipenyu.cn/Article/details/gttfxdlunv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yanxiufei.cn/Article/details/gtkraqmhhx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xylfe.cn/Article/details/gtkfnazdqr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtfxwxbgrr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ehwqpu.com/Article/details/gtsyyjarhz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqxlbcdxy.html

[Q01] 创建表
来源：http://dali.yuxming.cn/Article/details/gtqeplapud.html

CREATE TABLE users (
来源：http://dali.birdmap.top/Article/details/gtwnoxobfl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gtdneljtgd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnsxsgfw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zycfv.cn/Article/details/gtpbsafcbb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dashuyun.cn/Article/details/gtvwysxzaz.html

);
来源：http://dali.hywenlv.cn/Article/details/gtrcpthwvf.html

[Q02] 创建带外键的表
来源：http://dali.xuanzx.com/Article/details/gtxtlbnlco.html

CREATE TABLE orders (
来源：http://dali.jinghuilouyu.cn/Article/details/gtirzwdpwg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtkkbtrciz.html

user_id INT NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtaiimlrnu.html

amount DECIMAL(10, 2),
来源：http://dali.wangshuangyany.cn/Article/details/gtwnqhrcqm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.redwolf501.top/Article/details/gtxpptdfzc.html

);
来源：http://dali.aizwys.cn/Article/details/gtbdvnpoph.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gtitqdnfih.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aibaodan.cn/Article/details/gtmedrkier.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gtfozqkukj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gtoaasotwi.html

[Q05] 重命名列
来源：http://dali.hnqzz.top/Article/details/gtclznkrno.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenzaomai.com/Article/details/gtbniafaes.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gtealgfgiz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqoarhuh.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gtyfvwwybf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jiagoushi.top/Article/details/gtgedhbzdq.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gtpzsalpdm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gtmcuvsiso.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gtccmlcheg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gtgqpcghsg.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gtrgdliufv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.316326.xyz/Article/details/gtohvqirpg.html

[Q11] 一次插入多行
来源：http://dali.316326.xyz/Article/details/gttepawire.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gttjpfouss.html

[Q12] 插入后取自增 ID
来源：http://dali.guowangkeji.top/Article/details/gtburpcuir.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gtifpxwpkl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gtxybjmvvz.html

[Q13] 忽略重复插入
来源：http://dali.tanke756.top/Article/details/gtfoucanwi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtwsydllux.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gtrkasnfux.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzgkmdrv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gtzhfvcaal.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gttkhxgdzs.html

SELECT * FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtgxqpzvyh.html

[Q16] 查询指定列
来源：http://dali.birdmap.top/Article/details/gtgjdzwajo.html

SELECT id, name FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtmhvmcoev.html

[Q17] 条件查询
来源：http://dali.chenlongwang.top/Article/details/gtxcsgakzf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtcdanqcuo.html

[Q18] 模糊匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtwpweozoq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gtbvlkyjkz.html

[Q19] 范围查询
来源：http://dali.9152youxi.cn/Article/details/gtdhviilbj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xziqi.cn/Article/details/gtnehnomfh.html

[Q20] IN 列表
来源：http://dali.dashuyun.cn/Article/details/gtdswszcmj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gtbsdqdbzn.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqsrcrsu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xziqi.cn/Article/details/gtkrjalzgq.html

[Q22] 排序
来源：http://dali.ybcxt.top/Article/details/gtsiamvatp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gtelvjkrjm.html

[Q23] 分页
来源：http://dali.hongshengwenyu.top/Article/details/gtjmtenqco.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkjqwtme.html

[Q24] 去重
来源：http://dali.nanxinkj.top/Article/details/gtowtnofmk.html

SELECT DISTINCT city FROM users;
来源：http://dali.xylfe.cn/Article/details/gtlwdgkdpv.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gtxpoqvtek.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gthmfmpqen.html

[Q26] 计数
来源：http://dali.jiagoushi.top/Article/details/gtzcxaeuag.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gtpbvfbkej.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gtrmhpdafw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtfzpyzubf.html

[Q28] 求和与平均
来源：http://dali.0kj1m.cn/Article/details/gtqwaeculu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtnwxgdyol.html

[Q29] 最大最小值
来源：http://dali.nanxinkj.top/Article/details/gtamsjosfi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtlxozdkby.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsrnglkh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtmmqsyzpe.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gtxskkqiac.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxinkj.top/Article/details/gtasqrkwin.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtxsnvanqy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtqyaxgwyg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gtlnhxmvit.html

[Q33] 多列分组
来源：http://dali.daria6918.cn/Article/details/gtjjlidwej.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmstgcqp.html

[Q34] 每组取第一条
来源：http://dali.zhixingplan.top/Article/details/gtudttsdwa.html

SELECT * FROM (
来源：http://dali.dashuyun.cn/Article/details/gtbeklycth.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shzxlz.cn/Article/details/gteunuimex.html

) t WHERE rn = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtqalgwlee.html

[Q35] 内连接
来源：http://dali.ydzc1.top/Article/details/gttgbdewzw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtdcfyqxpb.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gtxcggyncz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtitmxvpgd.html

[Q37] 右连接
来源：http://dali.havefunace.top/Article/details/gtgzpzdhtx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xinyue.icu/Article/details/gtvczigvke.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xinyue.icu/Article/details/gtwfwcidtp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gtbpqzwgod.html

[Q39] 自连接（查上下级）
来源：http://dali.gzhubu.top/Article/details/gtgksqfxzt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gthlvfbypa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hysaishi.cn/Article/details/gtpthldiwu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gtpoqaecgu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aibaodan.cn/Article/details/gtimcipypx.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gtjzgtgiyy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xinyue.icu/Article/details/gtifznkuwa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gtglvxkvrn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aibaodan.cn/Article/details/gtnrsuzarg.html

[Q42] 连接条件附加过滤
来源：http://dali.dashuyun.cn/Article/details/gtcfgzepmm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgfzy.top/Article/details/gtrnmwvuoa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.c1oappe.top/Article/details/gtxaleomby.html

[Q43] 标量子查询
来源：http://dali.hnqzz.top/Article/details/gtqdgzqvuf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ppjwa.cn/Article/details/gtevqpckqe.html

[Q44] IN 子查询
来源：http://dali.zycfv.cn/Article/details/gtfjgfdezq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtkjchjwir.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gtguxtqhtp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtoyhfnoai.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtmpcdnqxy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtbkhbqcco.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gtommezzng.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.c1oappe.top/Article/details/gturyrenze.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtbfbahpnb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ppjwa.cn/Article/details/gthuisoohu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gtprvyyeee.html

[Q49] 更新单行
来源：http://dali.jqgfzy.top/Article/details/gtppyvkzvp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtwxzzslko.html

[Q50] 批量更新
来源：http://dali.tianlin.xyz/Article/details/gtkvlljimf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gtyciviesx.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gtjdwhykqa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shzxlz.cn/Article/details/gtmnjjevhs.html

[Q52] 删除指定行
来源：http://dali.hfpthk.cn/Article/details/gtczvlhrqr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gtpfhxlflq.html

[Q53] 按条件删除
来源：http://dali.sweek.top/Article/details/gtlvykuryz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gtgiyfsahg.html

[Q54] 清空表
来源：http://dali.tanke756.top/Article/details/gtffcwrtwh.html

TRUNCATE TABLE logs;
来源：http://dali.nanxinkj.top/Article/details/gtpeuwboxc.html

[Q55] 排名（并列占位）
来源：http://dali.ybcxt.top/Article/details/gtnshkqkag.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtrxcembkr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gtwawjwqlt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.redwolf501.top/Article/details/gtricpkfww.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gtodtzuhxp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtywnklvpd.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gtxuzgtmyf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfypgbtka.html

[Q59] 分组内累计
来源：http://dali.9152youxi.cn/Article/details/gtkdlujgvy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtyrwbgbga.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfnbkwpv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gtkdyeqkuw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtqgwhrblz.html

[Q61] 移动平均
来源：http://dali.zhengqikj.top/Article/details/gtjywzqdqw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtymskrrgg.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtaqprvxrj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtxwbyrgol.html

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gtdtfwmgtg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gtlcrusdqn.html

[Q64] 提交事务
来源：http://dali.0kj1m.cn/Article/details/gtpdrphpzq.html

COMMIT;
来源：http://dali.ydzc1.top/Article/details/gtcssxxfuv.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gtxiadbvda.html

ROLLBACK;
来源：http://dali.yanxiufei.cn/Article/details/gtzvtvobmc.html

[Q66] 行锁查询
来源：http://dali.pengpengdd.cyou/Article/details/gtfsufndmi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gtrfgexynn.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gtdjanakaj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jlsjyb.cn/Article/details/gtypamrrgb.html

[Q68] 保存点
来源：http://dali.tian-w.cn/Article/details/gtgxckgknv.html

SAVEPOINT sp1;
来源：http://dali.shzxlz.cn/Article/details/gtnpmvfbfl.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gtkfzzjmfk.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gtbnvonynq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ivvv.top/Article/details/gtvoauotkb.html

[Q70] 更新统计信息
来源：http://dali.zhoulong.xyz/Article/details/gtowodydlp.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gttetnifcg.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangtech.top/Article/details/gtabkmibrl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gtgowdabhc.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gtduembars.html

SHOW INDEX FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtfouzyhzb.html

[Q73] 查看表状态
来源：http://dali.redwolf501.top/Article/details/gtukhoczbh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gtuizdomlr.html

[Q74] 强制使用索引
来源：http://dali.jqgfzy.top/Article/details/gtrslkupnc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gthdaktsfv.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtuzqghlkh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtrtxzornh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gzhubu.top/Article/details/gtshehwxfs.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gtxqawnozk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.smart0.xyz/Article/details/gtoshulrmi.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gtnasisvmi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gtptnqkrdm.html

[Q78] 当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gtkrzeymfv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.birdmap.top/Article/details/gtzsauwqnc.html

[Q79] 字符串拼接
来源：http://dali.daxiang520.top/Article/details/gtijdagkpo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gtumkxhuqi.html

[Q80] 字符串截取
来源：http://dali.hongshengwenyu.top/Article/details/gtyrdebgpy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtzoeosqcw.html

[Q81] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gteklprxht.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gteakqpxhp.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258888.top/Article/details/gtquihjdhj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gttdxxdvns.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtuestcmyr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtwcnpdvpe.html

[Q84] 去除首尾空格
来源：http://dali.mhx1999.top/Article/details/gtmowrcdhb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtpnbpefdf.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gtcogqpheq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmgzzaep.html


<!-- 参考信息 -->