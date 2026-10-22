代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gtdzlyjtuw.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtepcgfick.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtvbgcanwc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cucudq.cn/Article/details/gtbjmpmhsx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tianlin.xyz/Article/details/gtnwifjavs.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtnpangmrl.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gthrtyirbw.html

Py:   async def f():⏎    await g()
来源：http://dali.zdqjudy.top/Article/details/gtwcwqrtgo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gtiovyprtd.html

JS:   async function f() { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtvxuwzejd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gttgfqcnpt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cdnleiting.top/Article/details/gthdslguue.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtpduuiwzl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbcptnlw.html

C#:   async Task F() { await G(); }
来源：http://dali.quarkkingdee.top/Article/details/gtiuqeudry.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvhoikpe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hysaishi.cn/Article/details/gtuqxdabyt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yanxiufei.cn/Article/details/gthcbxgcuv.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gttoixspsp.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdcowxvi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ydzc1.top/Article/details/gtslfdpsua.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gtthevlroe.html

Ruby: threads.map(&:join)
来源：http://dali.hammf.cn/Article/details/gtwcsqjyce.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gtvnzccxnv.html

[O06] 使用进程池
来源：http://dali.c1oappe.top/Article/details/gtkwxdqxar.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cdnleiting.top/Article/details/gtcxwxcsuv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gthbyzofzm.html

JS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtuksqfumi.html

TS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtcwsbafdu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gtohucdphd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daria6918.cn/Article/details/gtcnzbadgp.html

Ruby: // fork 块
来源：http://dali.kuanghao11.cn/Article/details/gtlbghncha.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gtyizlzxtf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtmawauyea.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtbgjjfhcl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtijzjhyra.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gtmriyjvjp.html

Py:   str(uuid.uuid4())
来源：http://dali.redwolf501.top/Article/details/gttrtmrkwf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gtfihsxqlh.html

JS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtsaeynrwl.html

TS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtopirfrbh.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gtsufmjpmi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtyvtglewq.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gtwwhizzqy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenzaomai.com/Article/details/gtyftsoaje.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xziqi.cn/Article/details/gtmoockyvh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gtsghvplui.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhixingplan.top/Article/details/gtfqfmedco.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtttgfqhap.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.svipenyu.cn/Article/details/gtsnqrxdbv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aizwys.cn/Article/details/gtpgyjcikh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hysaishi.cn/Article/details/gtkbkvxppo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gtcwapfuja.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hongshengwenyu.top/Article/details/gtwrxxbepq.html

[P03] 生成短随机字符串
来源：http://dali.tian-w.cn/Article/details/gtwuaelmnq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtksjpixhw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.birdmap.top/Article/details/gthnuatyno.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtwkjpsymf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtxewqxelp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.haohaochexian.top/Article/details/gtnntccrig.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xinyue.icu/Article/details/gtjvslolbh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhoulong.xyz/Article/details/gtvgxryjvl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gtgvxueilb.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gtkfducbif.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.bjfxy.top/Article/details/gtvacbyqgf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkqdpdjp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtxwxeejmr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gthbebijwn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hammf.cn/Article/details/gtvuksjbdg.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gtfbmiyamr.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbejvlkkp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tanke756.top/Article/details/gtkiyhlzdo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gtcckzohfq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.mhx1999.top/Article/details/gtvmezliit.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daxiang520.top/Article/details/gtajbvyfag.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.svipenyu.cn/Article/details/gtodxolyyi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtpueijwdf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangtech.top/Article/details/gtosujugsy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtkcpmdptr.html

Ruby: a == b
来源：http://dali.bjfxy.top/Article/details/gtezozbooz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guannengcc.top/Article/details/gtdtoldzfv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangshuangyany.cn/Article/details/gtwizysqdg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gtwilppjny.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtsssbnbhz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gtidoelwnm.html

TS:   if (x == null) {}
来源：http://dali.meibo888.top/Article/details/gtkveewtns.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtokzjbeus.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gtnhggdhbk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuetiantiany.cn/Article/details/gtldmmjwlj.html

C#:   if (x is null) {}
来源：http://dali.cqqwz.cn/Article/details/gtejmnxlzi.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gtpuafqfxs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhengqikj.top/Article/details/gtvhhuufqs.html

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gtomyeipvr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtfhqwxwnw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtcxipocgq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gtddgyevzw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gtzuqivhxk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gtyhjzoewc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gteafdjwjt.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258888.top/Article/details/gtsfktvlbw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daria6918.cn/Article/details/gtgykrrknf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.meibo888.top/Article/details/gtufxlbkfj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jyoumei.cn/Article/details/gttwgzvkfv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpojgbnc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jiagoushi.top/Article/details/gtvyxgymxq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gtwaiqpetz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gtegmjnpni.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhixingplan.top/Article/details/gtvvjkviyy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtiowqiwca.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gtcwtvzhxw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthzvdtwgh.html

[Q01] 创建表
来源：http://dali.wangshuangyany.cn/Article/details/gtmnpqytty.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gtlpjebyli.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtpgwlkaha.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtuhurfaqw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gtqmliiozt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cheryme.top/Article/details/gtbpkrpyyg.html

);
来源：http://dali.cheryme.top/Article/details/gtgkurpsqw.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gtpjocipkq.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gtklnprrwq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gtzmjdkimb.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtyxiutqka.html

amount DECIMAL(10, 2),
来源：http://dali.nanxuanxn.top/Article/details/gtpemaptns.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gtrublcyao.html

);
来源：http://dali.pycfn.com/Article/details/gtrhwjlilp.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gteiyxtcxc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.bjfxy.top/Article/details/gtqhafpfwv.html

[Q04] 修改列类型
来源：http://dali.yongpay.top/Article/details/gtlczhooqb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtkzmzhsps.html

[Q05] 重命名列
来源：http://dali.yuanzhike.top/Article/details/gtaujpjnvj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gtwgoskzqy.html

[Q06] 删除列
来源：http://dali.zhengqikj.top/Article/details/gtxdsudixy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tian-w.cn/Article/details/gtakfgyisb.html

[Q07] 删除表
来源：http://dali.yuxming.cn/Article/details/gtrijibizs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ivvv.top/Article/details/gthcfpqyli.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gtdlnqpwvi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtqgvtrccc.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gtnztjzkuk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtitjidnii.html

[Q10] 插入单行
来源：http://dali.yonumen.top/Article/details/gtihvtqsbu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258.top/Article/details/gtfhrbgedd.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gtrdifdsdg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtdptaeweg.html

[Q12] 插入后取自增 ID
来源：http://dali.cdnleiting.top/Article/details/gtetbunftt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jianghu66.top/Article/details/gtjmvglrdp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangdashe.top/Article/details/gtajuierre.html

[Q13] 忽略重复插入
来源：http://dali.jqgufenzy.top/Article/details/gtisiqqueg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtzeavolyp.html

[Q14] 存在则更新（upsert）
来源：http://dali.pengpengdd.cyou/Article/details/gtnagbfvbf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gtdeuwuyzk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.0kj1m.cn/Article/details/gtmfyxaooz.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gtawhnorhn.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtdjzpijlw.html

[Q16] 查询指定列
来源：http://dali.xinyue.icu/Article/details/gtsybssxcv.html

SELECT id, name FROM users;
来源：http://dali.tian-w.cn/Article/details/gtclpalnow.html

[Q17] 条件查询
来源：http://dali.jianghu66.top/Article/details/gttdnlgfqz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtefcvoliu.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtrspsjhtx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtylfwyxoj.html

[Q19] 范围查询
来源：http://dali.jianghu66.top/Article/details/gtxiqzjqss.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqvqjvtk.html

[Q20] IN 列表
来源：http://dali.yonumen.top/Article/details/gtfsgbbuoe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gzhubu.top/Article/details/gtqhnflgxm.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnosjccw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ydzc1.top/Article/details/gtyhbitdfw.html

[Q22] 排序
来源：http://dali.yongpay.top/Article/details/gtigzslpbc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fzhhl.top/Article/details/gtuvphgjva.html

[Q23] 分页
来源：http://dali.xziqi.cn/Article/details/gtfhweahnq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fengsongda.top/Article/details/gtrupblzzn.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gtwiakpttn.html

SELECT DISTINCT city FROM users;
来源：http://dali.yvedp.cn/Article/details/gtdtqgggxx.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gtwdutudzc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.snrcjt.cn/Article/details/gtbcoolhya.html

[Q26] 计数
来源：http://dali.zdqjudy.top/Article/details/gtduugpifg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtpviewqrr.html

[Q27] 条件计数
来源：http://dali.sysykeji.top/Article/details/gtltlkohyz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtrfeexqeb.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gtqienwdrq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtvdixtxka.html

[Q29] 最大最小值
来源：http://dali.shuidangran.top/Article/details/gtoojlknyz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtryctihfi.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gtjpycynvo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtoxtbgwey.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gthatxdfzy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gtwytvputw.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtdmxflxpl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtxkhisebp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gtzvozexwk.html

[Q33] 多列分组
来源：http://dali.yuanzhike.top/Article/details/gtjlwmmyxx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gttievatir.html

[Q34] 每组取第一条
来源：http://dali.fengsongda.top/Article/details/gtajkeetak.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtdarpwwnw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.vqdsnc.cn/Article/details/gtfwjvessy.html

) t WHERE rn = 1;
来源：http://dali.sysykeji.top/Article/details/gtlblfsfqn.html

[Q35] 内连接
来源：http://dali.jinqigfzy.top/Article/details/gtrrnsgqnx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtvchfxefs.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gtwwduvlnq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtbzyzowjn.html

[Q37] 右连接
来源：http://dali.snrcjt.cn/Article/details/gtninknbbb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.0kj1m.cn/Article/details/gtiofwmwph.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnqzz.top/Article/details/gtqokanhxq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnqzz.top/Article/details/gtwjcvrwob.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtyinnqutl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258.top/Article/details/gtlczknhxd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gtjtxolwnx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jqgfzy.top/Article/details/gtxuivrpis.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gtxtnvucyc.html

[Q41] 多表连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtomztzdtz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhongyouzk.top/Article/details/gtthirimys.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenlongwang.top/Article/details/gtradkbsdu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gtdizhuwwg.html

[Q42] 连接条件附加过滤
来源：http://dali.iojbl.cn/Article/details/gtmfhiiyxu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gtaetmgrkv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jlsjyb.cn/Article/details/gtncfontwt.html

[Q43] 标量子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtgaiyzzkd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtudgqbhwa.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gtlnznikke.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gtvfphtlnw.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiinjdlfk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.bjfxy.top/Article/details/gtkwicogkv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfqtjbxu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gthkmnltoc.html

[Q47] 与平均值比较
来源：http://dali.zhengqikj.top/Article/details/gtxhftjzoy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.kuanghao11.cn/Article/details/gtpwsegmyc.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gtljsfgmjk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fengsongda.top/Article/details/gtzgrtfsmn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gthqnaadgk.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gtzcvnpito.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtjhyroezz.html

[Q50] 批量更新
来源：http://dali.nanxinkj.top/Article/details/gtsgcedpqq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbphbwfg.html

[Q51] 用子查询更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxrsvewo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gtpvdivuoz.html

[Q52] 删除指定行
来源：http://dali.redwolf501.top/Article/details/gtnkfzoerk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtbnyuzfrt.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gtjhnhwvyb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gtojjtoaap.html

[Q54] 清空表
来源：http://dali.havefunace.top/Article/details/gtyetpmavn.html

TRUNCATE TABLE logs;
来源：http://dali.c1oappe.top/Article/details/gtgtsjjmbe.html

[Q55] 排名（并列占位）
来源：http://dali.c1oappe.top/Article/details/gtylogwbrm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtssaqmgid.html

[Q56] 密集排名（并列不占位）
来源：http://dali.meibo888.top/Article/details/gtthemiorw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtzlpyluyn.html

[Q57] 行号
来源：http://dali.daxiang520.top/Article/details/gtzixxlnjm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtnpkylawc.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gtialijrhs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gthekmusmz.html

[Q59] 分组内累计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapelwvpq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtxmdigiqe.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnxiangtu.top/Article/details/gtodzzyjfm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258888.top/Article/details/gtwgddygng.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtdghfkkkf.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gtaelgzfau.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gteyvymkio.html

[Q62] 分组占比
来源：http://dali.pycfn.com/Article/details/gtlyvetkjz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtckhvkzkb.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gtckygsjut.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.meibo888.top/Article/details/gtrdjjbtdb.html

[Q64] 提交事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtundzdhac.html

COMMIT;
来源：http://dali.jinqigufen.top/Article/details/gthxgxzzlm.html

[Q65] 回滚事务
来源：http://dali.hywenlv.cn/Article/details/gtajkxbpfr.html

ROLLBACK;
来源：http://dali.jinghuilouyu.cn/Article/details/gtndlrjwdo.html

[Q66] 行锁查询
来源：http://dali.xylfe.cn/Article/details/gthpamrynr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdpfklxo.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gtfgrgvmog.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gtbwoiboyx.html

[Q68] 保存点
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckjmffpk.html

SAVEPOINT sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtdbzklotz.html

ROLLBACK TO sp1;
来源：http://dali.shuidangran.top/Article/details/gtoxlvtguj.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gtyliunusi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.meibo888.top/Article/details/gtkjvxewle.html

[Q70] 更新统计信息
来源：http://dali.zhoulong.xyz/Article/details/gthngxbhbx.html

ANALYZE TABLE users;
来源：http://dali.chenzaomai.com/Article/details/gtvwijfrnh.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gtdbpxlemt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gtmgjtwtas.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gtwbhheaso.html

SHOW INDEX FROM users;
来源：http://dali.cashguo.top/Article/details/gtumxafacd.html

[Q73] 查看表状态
来源：http://dali.yuxming.cn/Article/details/gtjnlvtvmc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gtowocjutg.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gtikrtafqg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gtfzzdcmrb.html

[Q75] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtcznfkien.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtiqeueoyd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jianghu66.top/Article/details/gtkqvpdmxv.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gteobhcnar.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gtqvmtdhqp.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gtolkcjttu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258888.top/Article/details/gtjelwhjkm.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtrxarmgtk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gtahersuvi.html

[Q79] 字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtiziboxeo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gtzqodmgjx.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gttaszchik.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gtoyibolsd.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtwhpwdodp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtlnjkwmum.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgfzy.top/Article/details/gtrnjvpwaf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtvrepfupo.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtqvknsvyg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtwslfscnm.html


<!-- 参考信息 -->