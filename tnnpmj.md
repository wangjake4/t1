代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gtrkxxejdp.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gtedrkztav.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtvstzzrjk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gtbkspysku.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtskzoqhqu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zycfv.cn/Article/details/gtculugarr.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gtcepxdzxg.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjabxtbk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuakhxnyj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.0kj1m.cn/Article/details/gtfqdbjrfb.html

JS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gtkdnkbptr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgngmwuz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxidquxcl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guowangkeji.top/Article/details/gtezxuweca.html

Ruby: threads.map(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtziddpsic.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gtlijtscau.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gtuulzbmkw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daxiang520.top/Article/details/gtwqviuanf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.feifeiyinyue.top/Article/details/gtfyxypmib.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrgyxayo.html

TS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtqejriiuo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gthbsxtolf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daxiang520.top/Article/details/gtvxzsegif.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gtjhhulnfk.html

C#:   Parallel.For
来源：http://dali.smart0.xyz/Article/details/gtbdxgmfld.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttvsvzrix.html

P. 常用工具函数
来源：http://dali.zycfv.cn/Article/details/gtplyxjutz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfxgnpjvc.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gtwgntsjsf.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gtgzeiibjz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daxiang520.top/Article/details/gtdhvtmrwv.html

JS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtjaittmoc.html

TS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtivnfhnqx.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gttmbxcsdv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ybcxt.top/Article/details/gtynvshodr.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpkjwqxj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnajktod.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenjidiqi.icu/Article/details/gtmpwkqxdz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gtsmwwgndc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shuidangran.top/Article/details/gturtoevxv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenzaomai.com/Article/details/gtqsupyljs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yueranfly.top/Article/details/gtclgnohny.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.iojbl.cn/Article/details/gtwdkohvfi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sxryk.cn/Article/details/gtztvqikio.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gtcnscxfxj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sufxvd.cn/Article/details/gtnjrrqyel.html

[P03] 生成短随机字符串
来源：http://dali.bjfxy.top/Article/details/gtnkptiuwy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ydzc1.top/Article/details/gtlsosalwt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gaohongyu789.top/Article/details/gtmafbcctm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaifvegpi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtjtpcjyka.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gtnwpxrknq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gaohongyu789.top/Article/details/gtpoepbiix.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258.top/Article/details/gtquwuewud.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guannengcc.top/Article/details/gtpkutelmd.html

[P04] 求长度
来源：http://dali.zhongyouzk.top/Article/details/gtemyafkoi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gzhubu.top/Article/details/gtbvgdzzcf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gttvruhvrj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiktcjbsl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtiffhnocg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.iojbl.cn/Article/details/gtkpbfpumi.html

Go:   len(arr);  len(m)
来源：http://dali.kuanghao11.cn/Article/details/gtxuzvquzv.html

Ruby: x.length;  x.size
来源：http://dali.jianghu66.top/Article/details/gthnwknrke.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tian-w.cn/Article/details/gtvthscwnp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gthtnnyhyh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gtvdwdejck.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.vqdsnc.cn/Article/details/gtibeiyliv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aizwys.cn/Article/details/gtdvegvapp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gttrtiqull.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gtwvflamfk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtyxyjsixr.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gtzjiqbclo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shzxlz.cn/Article/details/gtqrtoseqy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gtdjvafoja.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmqdmnck.html

PHP:  if (empty($x)) {}
来源：http://dali.andypj.xyz/Article/details/gtxzzpsqpy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnqzz.top/Article/details/gtqtguhsia.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gtsqervees.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzsdcbqvi.html

Go:   if x == nil {}
来源：http://dali.jinqigfzy.top/Article/details/gtfvluatkp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gtcrevczpf.html

C#:   if (x is null) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjlpjarvu.html

[P07] 防抖与节流
来源：http://dali.zhengqikj.top/Article/details/gtoxssxcga.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xziqi.cn/Article/details/gtmyxhfzhk.html

PHP:  // 手写时间戳比较
来源：http://dali.ehwqpu.com/Article/details/gtbgdibvnk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtayvcamhb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtkcwxhipn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnqzz.top/Article/details/gtvqigycqb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gtepcqcxkg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daxiang520.top/Article/details/gtjvvnqvma.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dianchejie.cn/Article/details/gttvsmznle.html

[P08] 处理浮点精度问题
来源：http://dali.iojbl.cn/Article/details/gtlppusfzb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guannengcc.top/Article/details/gtkdsrdwbk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.andypj.xyz/Article/details/gtjutnvpdo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sweek.top/Article/details/gtsyaduofs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gtwjvjyvxm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gtphvyxymp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gtwetkfgde.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zdqjudy.top/Article/details/gtsttbxfdq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yueranfly.top/Article/details/gtvqyrfayz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuzyzfdu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yonumen.top/Article/details/gtgekkupyw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtedtytncb.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gtbdhekefi.html

CREATE TABLE users (
来源：http://dali.ydzc1.top/Article/details/gtyevfqzsl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtidhvtovb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjuspjhas.html

email VARCHAR(100) UNIQUE,
来源：http://dali.0kj1m.cn/Article/details/gtjiwupznb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gtljfxoynq.html

);
来源：http://dali.aizwys.cn/Article/details/gtpfpfxinc.html

[Q02] 创建带外键的表
来源：http://dali.gaohongyu789.top/Article/details/gtxnidsamc.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gtrankbdru.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtdeflhgoh.html

user_id INT NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtmgrrlfxw.html

amount DECIMAL(10, 2),
来源：http://dali.birdmap.top/Article/details/gtzqsbzuha.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gtubqsgfhe.html

);
来源：http://dali.xuanzx.com/Article/details/gtndidkpzz.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gtokxfwtup.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtlrafrqaa.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gtpyuqxcjx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigfzy.top/Article/details/gtoltraycl.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gtxmyotkof.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuetiantiany.cn/Article/details/gtumumlsdr.html

[Q06] 删除列
来源：http://dali.hywenlv.cn/Article/details/gtswsbcaei.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cdnleiting.top/Article/details/gthifevbjh.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhlvsthm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtvujzuruc.html

[Q08] 创建普通索引
来源：http://dali.zhongyouzk.top/Article/details/gtfevoyqvp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtxuznfjix.html

[Q09] 创建唯一索引
来源：http://dali.yj20258.top/Article/details/gtofpgoppk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtdjjirucm.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gtdngwihno.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyvhwijk.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gtvwxdhqcv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.c1oappe.top/Article/details/gttjkuoqff.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gtqaxhuqrm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ybcxt.top/Article/details/gtdwvpowko.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj202588.top/Article/details/gttvgtqizc.html

[Q13] 忽略重复插入
来源：http://dali.quarkkingdee.top/Article/details/gtnjubfltx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gtgizvgyzo.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigufen.top/Article/details/gtivdjtbqq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gtatwbjeux.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ehwqpu.com/Article/details/gtxhdooqgg.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gtdecyzcus.html

SELECT * FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmobhoxr.html

[Q16] 查询指定列
来源：http://dali.xuanzx.com/Article/details/gtzeofzbqn.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtvcjtdljt.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gtjstfkzgl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gthoiohxvo.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gtqqybzccf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gtkeeurdvl.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gtnjstwryp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258.top/Article/details/gtnrkuuaqy.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gtjcqkvuth.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gtrgxhcfbg.html

[Q21] 空值判断
来源：http://dali.aibaodan.cn/Article/details/gtdqmcimih.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gtxpjklzae.html

[Q22] 排序
来源：http://dali.nanxuanxn.top/Article/details/gtyywegrwm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gtvjcdcyge.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gtodgtsscx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnxiangtu.top/Article/details/gtwthafgaa.html

[Q24] 去重
来源：http://dali.snrcjt.cn/Article/details/gtnssezdfs.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangdashe.top/Article/details/gtdlzxihyf.html

[Q25] 只取前 N 条
来源：http://dali.shuidangran.top/Article/details/gtbpapzjcg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.svipenyu.cn/Article/details/gtxpdvijzv.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gtqxqslkse.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtictndphw.html

[Q27] 条件计数
来源：http://dali.kuanghao11.cn/Article/details/gtpdqxwdqf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuaocdwvi.html

[Q28] 求和与平均
来源：http://dali.cqqwz.cn/Article/details/gttgyduvqn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtukipdjpm.html

[Q29] 最大最小值
来源：http://dali.gotoacloud.top/Article/details/gtabdpkxfj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtuoqprvcl.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gtdhigwnxg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtrpxdfcmc.html

[Q31] 分组后过滤
来源：http://dali.nanxinkj.top/Article/details/gtrldfrutd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gtaguufldq.html

[Q32] 分组拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtgbbibxsc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtujrivylh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gtpmwtejuk.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gtyolsmvlq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yangfankeji.com/Article/details/gtalkfaudy.html

[Q34] 每组取第一条
来源：http://dali.hnqzz.top/Article/details/gtzpzcqvpd.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gtmakhwmzi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cucudq.cn/Article/details/gtbbfnlenc.html

) t WHERE rn = 1;
来源：http://dali.jianghu66.top/Article/details/gthbmwcvuy.html

[Q35] 内连接
来源：http://dali.ydzc1.top/Article/details/gtwinhigjm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gthkoidzed.html

[Q36] 左连接
来源：http://dali.9152youxi.cn/Article/details/gtuebasvmx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtlvzcjsgr.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gtckwulqiu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gtqzdufgwx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnueoyqk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jyoumei.cn/Article/details/gtryphplrr.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwouokwjm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.redwolf501.top/Article/details/gtpzibwhlm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gtjorgluzg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj202588.top/Article/details/gtlbnwnmkx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yvedp.cn/Article/details/gtnfkpgsbs.html

[Q41] 多表连接
来源：http://dali.havefunace.top/Article/details/gtppxtznii.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gthaalatra.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtuvmuyvaf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gtyjtghrla.html

[Q42] 连接条件附加过滤
来源：http://dali.ydzc1.top/Article/details/gtpejfpibs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gtktybjjll.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtyxrscxsr.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gtqsovnzkr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtewbyxtqx.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gtjxllwuqa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gtdtazgkpd.html

[Q45] EXISTS 判断存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmcecwgo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtctrmbkjx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nwbrower.top/Article/details/gticoxhaoe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtlemffhwi.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gtngpxkoln.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hfpthk.cn/Article/details/gtbncgrqaw.html

[Q48] CTE 公用表表达式
来源：http://dali.fzhhl.top/Article/details/gtmprmbgcr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.vqdsnc.cn/Article/details/gtmyyjyena.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtlkvpklor.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gteduujvfg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtxihlmgul.html

[Q50] 批量更新
来源：http://dali.jinqigfzy.top/Article/details/gtlextdcmx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtisshxyki.html

[Q51] 用子查询更新
来源：http://dali.gogol.net.cn/Article/details/gtkvjlicsu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jianghu66.top/Article/details/gtbsirttzw.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gtrvoizodt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gtobnlsrgh.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvkyeoew.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtppttzuue.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtbzmrwnhk.html

TRUNCATE TABLE logs;
来源：http://dali.svipenyu.cn/Article/details/gtjkvltrys.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gtxrvuytec.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtfjddvcvt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtwwcueduu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtiwlvvmlj.html

[Q57] 行号
来源：http://dali.yueranfly.top/Article/details/gthahoazwp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gthzukjwwf.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gteymsjbrw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtyjobwnol.html

[Q59] 分组内累计
来源：http://dali.zhengqikj.top/Article/details/gtexnglxqf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtvxbolfij.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gttytbgbmt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenlongwang.top/Article/details/gtseqgsqbf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgdpsrkj.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gthefnijky.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtgqllzrdb.html

[Q62] 分组占比
来源：http://dali.zhoulong.xyz/Article/details/gtivliegaa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtqppmhtll.html

[Q63] 开启事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvxuzlzs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daxiang520.top/Article/details/gtsxriljhi.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gtfxxtfypd.html

COMMIT;
来源：http://dali.feifeiyinyue.top/Article/details/gtnutkreer.html

[Q65] 回滚事务
来源：http://dali.sxryk.cn/Article/details/gtwwfcgtuc.html

ROLLBACK;
来源：http://dali.gaohongyu789.top/Article/details/gtcbrflkzc.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gtomptejhz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ppjwa.cn/Article/details/gtulzhugit.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gtdviknzwl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gtvmrrmhag.html

[Q68] 保存点
来源：http://dali.cheryme.top/Article/details/gtgbnrhaix.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtuvfufrpo.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gtfliqkhzj.html

[Q69] 查看执行计划
来源：http://dali.shuidangran.top/Article/details/gttjmjnbjl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gtxfwiutns.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwlotlsf.html

ANALYZE TABLE users;
来源：http://dali.jinqigfzy.top/Article/details/gtiaspyvle.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gtsumuapsz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fzhhl.top/Article/details/gtyrqnfved.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykdkppja.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtcrxsiuqq.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gtqkeqgavn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gtsbfsveqh.html

[Q74] 强制使用索引
来源：http://dali.svipenyu.cn/Article/details/gtwnabyjrg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.quarkkingdee.top/Article/details/gtewdrobjx.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gtuaqcozyp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemgfbimy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gtrftmbfpc.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gtwrpmdulq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xinyue.icu/Article/details/gtunqnpflz.html

[Q77] 时间加减
来源：http://dali.quarkkingdee.top/Article/details/gtendxqgip.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gtosxfvksk.html

[Q78] 当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gtjhehgxqm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258.top/Article/details/gtfgxbbyta.html

[Q79] 字符串拼接
来源：http://dali.meibo888.top/Article/details/gturamvjoh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sweek.top/Article/details/gtuontfkxc.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gthuykfqcl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtmrixxlxz.html

[Q81] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtdrxjkbmd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtspuduuwt.html

[Q82] 字符长度与字节长度
来源：http://dali.dashuyun.cn/Article/details/gtuskeqdqa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtbhpvapap.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtsannijpw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxywiibxq.html

[Q84] 去除首尾空格
来源：http://dali.yuanzhike.top/Article/details/gtkvngihsp.html

SELECT TRIM(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtirlowjzp.html

[Q85] 数值取整
来源：http://dali.smart0.xyz/Article/details/gtdqvtshza.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhoulong.xyz/Article/details/gtghfgbxjq.html

[Q86] 读取 JSON 字段
来源：http://dali.hnxiangtu.top/Article/details/gtzktozjwl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gtgksnetxi.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gtxjmfowzw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gtojpsenay.html


<!-- 参考信息 -->