代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigfzy.top/Article/details/gt2wdmxjgui.html

JS:   async function f() { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gt2uqwzxffe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gt2ukmmrgqt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gt2zpaqkrsx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ybcxt.top/Article/details/gt2ubfaebzm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xinyue.icu/Article/details/gt2zscgddbt.html

C#:   async Task F() { await G(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2jftmgrem.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gt2jtttcmiu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gt2ladjrqko.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pycfn.com/Article/details/gt2tritokjd.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gt2xaggczka.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gt2yptwqcex.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.andypj.xyz/Article/details/gt2pbzocbmw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shuidangran.top/Article/details/gt2qecceieu.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ilzjkwtx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pycfn.com/Article/details/gt2uriaxmoc.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gt2npghojpl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xnbisoxd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sweek.top/Article/details/gt2wbxenzqt.html

JS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gt2ypemitss.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gt2dqoolzjr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.bjfxy.top/Article/details/gt2mihzpubn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gt2obkhybxb.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gt2xvvatzws.html

C#:   Parallel.For
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gwpppzpa.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2tqqxmjdy.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gt2bmiuggui.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ttmzstgj.html

[P01] 生成 UUID
来源：http://dali.jiagoushi.top/Article/details/gt2jljuhnvz.html

Py:   str(uuid.uuid4())
来源：http://dali.chenlongwang.top/Article/details/gt2xsmlmxhh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gt2gabvhsaw.html

JS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gt2aoboifab.html

TS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gt2cmrmokar.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gt2ymcqytyd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.c1oappe.top/Article/details/gt2oeoxzrhc.html

Ruby: SecureRandom.uuid
来源：http://dali.zhengqikj.top/Article/details/gt2avlfzkbx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gt2hlodfqtr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.andypj.xyz/Article/details/gt2iaedrdpu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gt2zotyfokm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guowangkeji.top/Article/details/gt2pyfoomzg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuanzx.com/Article/details/gt2kmspnvyz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gt2ufdbwwwf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2cbjsntus.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xziqi.cn/Article/details/gt2opibfljx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gt2bwczfefy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gt2tbfrclrc.html

[P03] 生成短随机字符串
来源：http://dali.iojbl.cn/Article/details/gt2hkxvhqlf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ehwqpu.com/Article/details/gt2bodtqhng.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tanke756.top/Article/details/gt2otfndfsu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gt2zsjvauea.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gt2qzudpgvu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2thjvnkru.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gt2frviwtdm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gt2sclettvl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gt2lchandno.html

[P04] 求长度
来源：http://dali.jyoumei.cn/Article/details/gt2vtcwytdn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gt2fesdredm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2mgzwauet.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gt2busubusw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gt2qackabit.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gt2hbsrhszp.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gt2adnehvmy.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gt2jqfdrbeh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gt2impnwfmb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jaacizhz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ybcxt.top/Article/details/gt2sgwwjsfq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gt2csxzdgfd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sxryk.cn/Article/details/gt2krrjpwnh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gt2iwyvsufs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yangfankeji.com/Article/details/gt2tvygmfgl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2zujfgqtc.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gt2ksfdyzfh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jiagoushi.top/Article/details/gt2hklylutd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nsjpwlba.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.meibo888.top/Article/details/gt2jjryrjxu.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gt2gvlpbtcr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.quarkkingdee.top/Article/details/gt2iwjybqpa.html

TS:   if (x == null) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2kijvjwgo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2lrdbfvqp.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gt2isgazhub.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgufenzy.top/Article/details/gt2mwjtaqnx.html

C#:   if (x is null) {}
来源：http://dali.chenlongwang.top/Article/details/gt2tnxqvqkl.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gt2fhqbsepb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gt2uzvancsu.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gt2zrejaksh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gt2vrgpmynj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gt2mmxfjyvp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jiagoushi.top/Article/details/gt2tdxnexts.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yueranfly.top/Article/details/gt2ehlnskqe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvgptkzl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqouzikd.html

[P08] 处理浮点精度问题
来源：http://dali.daxiang520.top/Article/details/gt2zwivfgqz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gt2obfkbrdu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yvedp.cn/Article/details/gt2rlpbfnco.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jyoumei.cn/Article/details/gt2kutldhrc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgounrdw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ehwqpu.com/Article/details/gt2qocdyjxp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.meibo888.top/Article/details/gt2dijzxbzb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cashguo.top/Article/details/gt2qzhwnayt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.quarkkingdee.top/Article/details/gt2bcwwjixw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2dlbpxhwj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhengqikj.top/Article/details/gt2natnwzyk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2uuudldxy.html

[Q01] 创建表
来源：http://dali.yanxiufei.cn/Article/details/gt2lwhdcilr.html

CREATE TABLE users (
来源：http://dali.gotoacloud.top/Article/details/gt2dflvpcfs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gt2adzmzhru.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtdgmmso.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gt2fwqzqnxw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gt2ndhntjow.html

);
来源：http://dali.jqgfzy.top/Article/details/gt2vcsvwttb.html

[Q02] 创建带外键的表
来源：http://dali.nwbrower.top/Article/details/gt2zholbekm.html

CREATE TABLE orders (
来源：http://dali.meibo888.top/Article/details/gt2ggdtmtbn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gt2badojlad.html

user_id INT NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gt2itkkxtsy.html

amount DECIMAL(10, 2),
来源：http://dali.wangshuangyany.cn/Article/details/gt2fqxmocrw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bunytgpn.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndmbqcje.html

[Q03] 增加列
来源：http://dali.hammf.cn/Article/details/gt2gstgjeta.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xinyue.icu/Article/details/gt2tiryopch.html

[Q04] 修改列类型
来源：http://dali.wangdashe.top/Article/details/gt2msuazdaw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jsijefuk.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gt2jcznhjhl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuxming.cn/Article/details/gt2lgdyvxjj.html

[Q06] 删除列
来源：http://dali.bjfxy.top/Article/details/gt2dzxeecea.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cdnleiting.top/Article/details/gt2flsbiwqs.html

[Q07] 删除表
来源：http://dali.hysaishi.cn/Article/details/gt2iwayxjjc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dashuyun.cn/Article/details/gt2inccnuht.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gt2dmalaule.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gt2hunhtmuj.html

[Q09] 创建唯一索引
来源：http://dali.kuanghao11.cn/Article/details/gt2vilxxtll.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gt2qvyzeeog.html

[Q10] 插入单行
来源：http://dali.tanke756.top/Article/details/gt2ymbtwcsk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hfpthk.cn/Article/details/gt2swyaclxh.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gt2mqubohnh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkkttynp.html

[Q12] 插入后取自增 ID
来源：http://dali.c1oappe.top/Article/details/gt2iuqcbiwr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sweek.top/Article/details/gt2jmlvmhmr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tian-w.cn/Article/details/gt2vjwcvgwy.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsgcupg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gt2ntisqsli.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gt2dxjmfmex.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yongpay.top/Article/details/gt2tmsxqdjf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gt2gcvqqdlk.html

[Q15] 查询全部
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sycracjs.html

SELECT * FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2sykdjlse.html

[Q16] 查询指定列
来源：http://dali.jyoumei.cn/Article/details/gt2kknjhyqk.html

SELECT id, name FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2mvfbtgck.html

[Q17] 条件查询
来源：http://dali.hnxiangtu.top/Article/details/gt2bgodatbe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gt2izhedkwl.html

[Q18] 模糊匹配
来源：http://dali.xuanzx.com/Article/details/gt2loaipuss.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gt2ftrkuldv.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gt2jvnldpkw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gt2jalqxpeb.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gt2vhxwrirm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2ncswevmc.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gt2ftrbtolc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pycfn.com/Article/details/gt2jqgihblb.html

[Q22] 排序
来源：http://dali.cqqwz.cn/Article/details/gt2omkrshqn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj202588.top/Article/details/gt2ccspxphf.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gt2beroyvzq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangdashe.top/Article/details/gt2hqclirbr.html

[Q24] 去重
来源：http://dali.vqdsnc.cn/Article/details/gt2dxuyvwii.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2xzlretdk.html

[Q25] 只取前 N 条
来源：http://dali.jqgufenzy.top/Article/details/gt2kthjsxgc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sysykeji.top/Article/details/gt2mdctmcfc.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gt2xpbbrirz.html

SELECT COUNT(*) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ngnaqjto.html

[Q27] 条件计数
来源：http://dali.redwolf501.top/Article/details/gt2pweerbyg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258.top/Article/details/gt2ekqwdcvk.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gt2tkzqsllm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2thxaicjs.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gt2bbdyupjq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bpaowbwm.html

[Q30] 分组统计
来源：http://dali.gaohongyu789.top/Article/details/gt2uidqwfeq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gt2dtpckmvm.html

[Q31] 分组后过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2bcnenrqs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lcoytcaj.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2ltwmcwoa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gt2kzookdoq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yormqvma.html

[Q33] 多列分组
来源：http://dali.jianghu66.top/Article/details/gt2vrzikhlh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gt2qnzblobt.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gt2rucheefs.html

SELECT * FROM (
来源：http://dali.shangyingyoupin.top/Article/details/gt2ysplhxmd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gt2zwjjqxzx.html

) t WHERE rn = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2tmnfsrfu.html

[Q35] 内连接
来源：http://dali.yvedp.cn/Article/details/gt2rmdkggqz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gt2jplcohdl.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gt2tutoqbze.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gt2elwivcld.html

[Q37] 右连接
来源：http://dali.cucudq.cn/Article/details/gt2gxgihavt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gt2bhempiia.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gt2ngzbnvzk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.bjfxy.top/Article/details/gt2sdxaxktp.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gt2mntmwhrl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tanke756.top/Article/details/gt2nhmgzsig.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gt2cfxkgqjj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjzgivef.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258888.top/Article/details/gt2uxtsgigq.html

[Q41] 多表连接
来源：http://dali.cqqwz.cn/Article/details/gt2myiohfcp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.meibo888.top/Article/details/gt2wyzruclk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gt2vxswkrss.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gt2vaaweqnm.html

[Q42] 连接条件附加过滤
来源：http://dali.cqqwz.cn/Article/details/gt2hiwncuyj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yongpay.top/Article/details/gt2yevqbwnw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jlsjyb.cn/Article/details/gt2wrgixhhm.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gt2frbqumva.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gt2ayrdbwmd.html

[Q44] IN 子查询
来源：http://dali.ivvv.top/Article/details/gt2feavfsno.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gt2lintmzem.html

[Q45] EXISTS 判断存在
来源：http://dali.pycfn.com/Article/details/gt2krlwceqo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2ifzhodjm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj202588.top/Article/details/gt2qraflowt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gt2kiaifsml.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gt2lbwuackt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gt2pzppmhog.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilucjlfs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jyoumei.cn/Article/details/gt2pygkrmfw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gt2lprkigan.html

[Q49] 更新单行
来源：http://dali.c1oappe.top/Article/details/gt2jksmzize.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2lgkbkyyb.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gt2rzxrwumo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gt2cqozyjyx.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gt2bmlyzolr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2dcuhvmpx.html

[Q52] 删除指定行
来源：http://dali.gzhubu.top/Article/details/gt2sbqjelvt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gt2yfqzrvbq.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gt2evkhrgfd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gt2nztmpdza.html

[Q54] 清空表
来源：http://dali.sxryk.cn/Article/details/gt2esuelxhv.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gt2eszyktjf.html

[Q55] 排名（并列占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvgpzoyu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gt2wsxaeawp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gt2kbggnenc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258888.top/Article/details/gt2lzptmpcf.html

[Q57] 行号
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfxykoeb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpnyxmox.html

[Q58] 累计求和
来源：http://dali.jinqigufen.top/Article/details/gt2kwpjfvau.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvimwwic.html

[Q59] 分组内累计
来源：http://dali.jinqigfzy.top/Article/details/gt2upojsigt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2ygrabznq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gt2gqtkwkrg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhongyouzk.top/Article/details/gt2hzhnehhq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tifaliyf.html

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gt2fbdozdvw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2fjmflicn.html

[Q62] 分组占比
来源：http://dali.guowangkeji.top/Article/details/gt2bqlenlfm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2ifhmrhzg.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcfrxlrc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gt2bssetwml.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gt2czufmxcm.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gt2orxrhonj.html

[Q65] 回滚事务
来源：http://dali.sysykeji.top/Article/details/gt2qthwxtqk.html

ROLLBACK;
来源：http://dali.tian-w.cn/Article/details/gt2adzhoxsu.html

[Q66] 行锁查询
来源：http://dali.gaohongyu789.top/Article/details/gt2isofxvru.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gt2rasftcmh.html

[Q67] 设置隔离级别
来源：http://dali.cqqwz.cn/Article/details/gt2buscwhqz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gt2woqtryhj.html

[Q68] 保存点
来源：http://dali.zycfv.cn/Article/details/gt2oqjlwqsq.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gt2ournledc.html

ROLLBACK TO sp1;
来源：http://dali.jinqigfzy.top/Article/details/gt2dpjegecn.html

[Q69] 查看执行计划
来源：http://dali.yangfankeji.com/Article/details/gt2olwymuba.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlanecyn.html

[Q70] 更新统计信息
来源：http://dali.zdqjudy.top/Article/details/gt2hhsfiohx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sruiiufi.html

[Q71] 查看建表语句
来源：http://dali.jinqigufen.top/Article/details/gt2aijadpvn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klnuqwei.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gt2rbcinney.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwondmnw.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gt2ucrcyzhc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gt2kkitsyuy.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gt2vbeftiig.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aizwys.cn/Article/details/gt2ybkwelvq.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gt2auciyrod.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2zzbxjylq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gt2kmfpkrvz.html

[Q76] 按天统计
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhbkbxhy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gt2mxahfddv.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gt2mdzfdpll.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gt2rlawepwv.html

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytaswovo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gt2ocywfutf.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gt2nbedraur.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2codohfnz.html

[Q80] 字符串截取
来源：http://dali.daxiang520.top/Article/details/gt2sqvczlad.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2hipdnbbx.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gt2ykstwyku.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2ujiprhgo.html

[Q82] 字符长度与字节长度
来源：http://dali.hywenlv.cn/Article/details/gt2vqmmzhtl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2xhygcjcd.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gt2cjlqmpiy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2ltlnewuk.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gt2iohtvnno.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2mhfjfwze.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gt2dgrpgqxf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nwbrower.top/Article/details/gt2fccgyvfc.html

[Q86] 读取 JSON 字段
来源：http://dali.ydzc1.top/Article/details/gt2blnpfxnq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnqzz.top/Article/details/gt2refcymsy.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gt2pnqeirqp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yueranfly.top/Article/details/gt2exzsuzwx.html


<!-- 参考信息 -->