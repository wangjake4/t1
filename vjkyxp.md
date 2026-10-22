代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jianghu66.top/Article/details/gthhjhxzny.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtjyylxsbj.html

[O04] 定义异步函数并等待
来源：http://dali.yanxiufei.cn/Article/details/gtxvoubjsu.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gtpucwrlhz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tianlin.xyz/Article/details/gtrceczrqz.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtjtjgeash.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtepkxtfef.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cqqwz.cn/Article/details/gtppekjipx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtzjxnoimk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gtytkdwoxy.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gtxufpnped.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gtvqranggr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hysaishi.cn/Article/details/gtakuomvwc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gtksjeuyzl.html

JS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gtyvsjqkel.html

TS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gtdtdjyytm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.quarkkingdee.top/Article/details/gtwdoqusiy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gtwgwjqilo.html

Ruby: threads.map(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtrvzahecj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gtsstncfdx.html

[O06] 使用进程池
来源：http://dali.nanxinkj.top/Article/details/gtgwgjgxbg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfxmunkn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gtrerntihn.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxploeuip.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtakbzgsql.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gtmnogxgbf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jiagoushi.top/Article/details/gtplmcdcqq.html

Ruby: // fork 块
来源：http://dali.kuanghao11.cn/Article/details/gtvjbdldir.html

C#:   Parallel.For
来源：http://dali.jyoumei.cn/Article/details/gtuuffgvcx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gttmgaffpb.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gtwnwvwxbg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtagpdggot.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtjekqpsrz.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258.top/Article/details/gthlmratvw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pycfn.com/Article/details/gtgarbebdv.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtqosoidcw.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtfynedhuu.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtccrppmlc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gtafdnkgid.html

Ruby: SecureRandom.uuid
来源：http://dali.svipenyu.cn/Article/details/gthgjrlnoc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sufxvd.cn/Article/details/gtqpdkskbf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gtmahrvlij.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gtiqirahpr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gtrdlswrsc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtljjjmcsg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxuanxn.top/Article/details/gtyekcvzmh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sxryk.cn/Article/details/gthtxjvuss.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shuidangran.top/Article/details/gtzivsphkd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gtjqhuxogf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gtvyufbjdf.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gtmhnpzdlp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtxvrhblvz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangdashe.top/Article/details/gtrnxuizrw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtarbhkjvy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtutyyfbme.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtwskggjsc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuxming.cn/Article/details/gtxjntcamv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gtiraiymdu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gtrhljwcrk.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysiadboo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yvedp.cn/Article/details/gteotnyjii.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtwamhdwwd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gtvmwtpvvo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtjavpchrm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gtijhfuota.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gtosjuowkx.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gtehvqoxpw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258888.top/Article/details/gtjfqtrlpx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gtaooxxdat.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gtzzfwutgo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aibaodan.cn/Article/details/gtfahuzipq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhoulong.xyz/Article/details/gtkjuuimaz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gtjkwetmex.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkxugwvj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gtrrcmqazx.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gtqxffmvvp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gttxabrcvy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gtzmcdrdej.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gtgncdorff.html

PHP:  if (empty($x)) {}
来源：http://dali.ehwqpu.com/Article/details/gttookulfk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gthpzalext.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gtdzedqznw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtatoezldd.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtwjiycllw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ydzc1.top/Article/details/gtxnlfqrbn.html

C#:   if (x is null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtpnahpwkc.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gtbybjdhpu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cashguo.top/Article/details/gtapurebnj.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gtmzohdzzx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtcezsqcxx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtpoxfysgx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ehwqpu.com/Article/details/gtkgjasxaq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.svipenyu.cn/Article/details/gtrxfiislf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.bjfxy.top/Article/details/gtlwdzcwxm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cucudq.cn/Article/details/gtirtjjosi.html

[P08] 处理浮点精度问题
来源：http://dali.yj202588.top/Article/details/gtoypqjgli.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ehwqpu.com/Article/details/gtiturqqyd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gtilqykrwn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hywenlv.cn/Article/details/gtdszhvxbm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtbghmnijn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jiagoushi.top/Article/details/gtuqpkpirx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gtpesvvace.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgufenzy.top/Article/details/gtxvunnrkf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gtiqyxbtjc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdfwtynwk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shangyingyoupin.top/Article/details/gtrkfmeflk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtcrbyqapx.html

[Q01] 创建表
来源：http://dali.sxryk.cn/Article/details/gtkfnrxsvh.html

CREATE TABLE users (
来源：http://dali.c1oappe.top/Article/details/gtgriqjrvd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtyoiqgvjr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sweek.top/Article/details/gtysjyljfw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gtvllndwdy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xinyue.icu/Article/details/gtcbedbxvj.html

);
来源：http://dali.yj20258.top/Article/details/gtksbuauno.html

[Q02] 创建带外键的表
来源：http://dali.pengpengdd.cyou/Article/details/gtkdfpnbox.html

CREATE TABLE orders (
来源：http://dali.aibaodan.cn/Article/details/gtnvhqrzxv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtbferwtpp.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtfoptshke.html

amount DECIMAL(10, 2),
来源：http://dali.nwbrower.top/Article/details/gtiomxphxe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gtbrahekhu.html

);
来源：http://dali.guowangkeji.top/Article/details/gteljwvexr.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gtbajxwcfe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxsjonfr.html

[Q04] 修改列类型
来源：http://dali.gogol.net.cn/Article/details/gtzqaeqkew.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzypqish.html

[Q05] 重命名列
来源：http://dali.shangyingyoupin.top/Article/details/gtmzdkkqgj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sxryk.cn/Article/details/gtqlyvstsa.html

[Q06] 删除列
来源：http://dali.nanxuanxn.top/Article/details/gtpwxawcaq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxuanxn.top/Article/details/gtoirvalkj.html

[Q07] 删除表
来源：http://dali.yueranfly.top/Article/details/gtpmsaglzu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gteyijdzpv.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gtbukpcfye.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gtodoretyu.html

[Q09] 创建唯一索引
来源：http://dali.dianchejie.cn/Article/details/gtqgsiwyro.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtbmvxgzso.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gtjhglrtnx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtcvcaxhkq.html

[Q11] 一次插入多行
来源：http://dali.hysaishi.cn/Article/details/gtspamxqpb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cashguo.top/Article/details/gtkjfaxohd.html

[Q12] 插入后取自增 ID
来源：http://dali.cqqwz.cn/Article/details/gtclnvtoqd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258888.top/Article/details/gtynvdljmd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ybcxt.top/Article/details/gthnijvcmc.html

[Q13] 忽略重复插入
来源：http://dali.fengsongda.top/Article/details/gtxmxiqxvk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.mhx1999.top/Article/details/gtqpqpmyrl.html

[Q14] 存在则更新（upsert）
来源：http://dali.tanke756.top/Article/details/gtehucbdak.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258888.top/Article/details/gtxijkoqrn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.redwolf501.top/Article/details/gtidericzz.html

[Q15] 查询全部
来源：http://dali.cucudq.cn/Article/details/gtyanyvxhr.html

SELECT * FROM users;
来源：http://dali.sysykeji.top/Article/details/gtcmmduqdj.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrezalavd.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtajywfjap.html

[Q17] 条件查询
来源：http://dali.hfpthk.cn/Article/details/gtuiyevnrz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gtrzfpqpcr.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gtdtzwcjkp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ehwqpu.com/Article/details/gtnmvptnod.html

[Q19] 范围查询
来源：http://dali.dianchejie.cn/Article/details/gtinxfrwrk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gtfebssbue.html

[Q20] IN 列表
来源：http://dali.sxryk.cn/Article/details/gtycmdiyzc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtbzylzrvn.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gtcoyipmjq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gthzbqdbcy.html

[Q22] 排序
来源：http://dali.pengpengdd.cyou/Article/details/gtqiugajar.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.c1oappe.top/Article/details/gthkgrmhtz.html

[Q23] 分页
来源：http://dali.aizwys.cn/Article/details/gtyjdqvrzz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gthkzdsapn.html

[Q24] 去重
来源：http://dali.guowangkeji.top/Article/details/gtjahojkcq.html

SELECT DISTINCT city FROM users;
来源：http://dali.xylfe.cn/Article/details/gtqvfhkqvc.html

[Q25] 只取前 N 条
来源：http://dali.cheryme.top/Article/details/gtjipmrbgz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gtwwgxleoc.html

[Q26] 计数
来源：http://dali.wangdashe.top/Article/details/gthlejjkvv.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gttsexrvog.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gtqjrylxay.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtmrpevjcq.html

[Q28] 求和与平均
来源：http://dali.9152youxi.cn/Article/details/gtsenqvudj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtsisfyset.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gtfkmutetk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtegujrlad.html

[Q30] 分组统计
来源：http://dali.nwbrower.top/Article/details/gtidncnfsa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtqhhqanir.html

[Q31] 分组后过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcehozbre.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuanzx.com/Article/details/gtremnizaa.html

[Q32] 分组拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtskkbbgnu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtcrqnaiba.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daxiang520.top/Article/details/gtajquvjof.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gtyjnkeqyk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jiagoushi.top/Article/details/gtzfgaiihl.html

[Q34] 每组取第一条
来源：http://dali.jianghu66.top/Article/details/gtktoghwbz.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtefyfyvtk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.0kj1m.cn/Article/details/gtubjwwbvs.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gtkkhgbyaw.html

[Q35] 内连接
来源：http://dali.zhixingplan.top/Article/details/gtdtwojcjy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtoomoyzhs.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gtadpsnqeo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtkyvnfnmp.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gttnxagnkw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gtrgsjauqx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guowangkeji.top/Article/details/gtgdhbpliq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnxiangtu.top/Article/details/gtaveooxod.html

[Q39] 自连接（查上下级）
来源：http://dali.ivvv.top/Article/details/gthiniffku.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrnxecyh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tianlin.xyz/Article/details/gttiflimiq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhongyouzk.top/Article/details/gtombrgzcd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gtxrrubxzi.html

[Q41] 多表连接
来源：http://dali.cqqwz.cn/Article/details/gtslfjlpwa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gtivjeasfg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxinkj.top/Article/details/gtiotyriml.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgufenzy.top/Article/details/gtuneqjswp.html

[Q42] 连接条件附加过滤
来源：http://dali.chenzaomai.com/Article/details/gtslefeftl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gtrseaudzx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sufxvd.cn/Article/details/gtiyldioft.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gtpxgqciop.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsnjtyyj.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqcgzvsp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gtbvruceyd.html

[Q45] EXISTS 判断存在
来源：http://dali.daxiang520.top/Article/details/gtppcvdiqb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtdqxdypnm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gttytlmmbt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gtdympjyyz.html

[Q47] 与平均值比较
来源：http://dali.sweek.top/Article/details/gtjkuvqtkf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cdnleiting.top/Article/details/gtofcpcifo.html

[Q48] CTE 公用表表达式
来源：http://dali.yanxiufei.cn/Article/details/gtxirfkwlj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dashuyun.cn/Article/details/gtesgtodqb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gtmxwsbwas.html

[Q49] 更新单行
来源：http://dali.jyoumei.cn/Article/details/gtsuhtolwb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gtqrkkcnhc.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gtbzqhkfhn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuekgxlgk.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gtkmgjizwy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jianghu66.top/Article/details/gtxizvamhv.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gtiifxqcgm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gteuezxvjl.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gttrbioujb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuanzhike.top/Article/details/gtlqmcztzm.html

[Q54] 清空表
来源：http://dali.vqdsnc.cn/Article/details/gtfvykyzjq.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gtdesbfmrf.html

[Q55] 排名（并列占位）
来源：http://dali.guowangkeji.top/Article/details/gtgygofbbi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258.top/Article/details/gthhfyklvw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sxryk.cn/Article/details/gtbjekvxsj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ivvv.top/Article/details/gtwbkbpnna.html

[Q57] 行号
来源：http://dali.yonumen.top/Article/details/gtfqwzjyad.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtqclttvtf.html

[Q58] 累计求和
来源：http://dali.dashuyun.cn/Article/details/gtmwiocjkd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtddcwdfle.html

[Q59] 分组内累计
来源：http://dali.hongshengwenyu.top/Article/details/gtecfpaxyd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtexjarcwh.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gtfhwwahlm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gtujflrses.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtmyltiawt.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gtzibomgyo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtrymlfiip.html

[Q62] 分组占比
来源：http://dali.tian-w.cn/Article/details/gtiekqlzap.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtxlngzbzi.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtmldeiaii.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gtwbfdtvhn.html

[Q64] 提交事务
来源：http://dali.nanxuanxn.top/Article/details/gtumjkoxpt.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gtcrkuieto.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtemhqpzyx.html

ROLLBACK;
来源：http://dali.yueranfly.top/Article/details/gtpyirkora.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gtvmpqixfv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhiwqete.html

[Q67] 设置隔离级别
来源：http://dali.shangyingyoupin.top/Article/details/gtktgfvtvf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gtfelhxwjf.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gtcvmgzjjg.html

SAVEPOINT sp1;
来源：http://dali.yangfankeji.com/Article/details/gtxaqghfcs.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gtpgpvbihg.html

[Q69] 查看执行计划
来源：http://dali.0kj1m.cn/Article/details/gtqebjdtrg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuetiantiany.cn/Article/details/gtqswvjyps.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gtrfrjejqw.html

ANALYZE TABLE users;
来源：http://dali.cheryme.top/Article/details/gtfilyydxs.html

[Q71] 查看建表语句
来源：http://dali.ydzc1.top/Article/details/gtogwoself.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hammf.cn/Article/details/gtmwyjvsgr.html

[Q72] 查看索引
来源：http://dali.ybcxt.top/Article/details/gtljdggmuv.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gtrworytit.html

[Q73] 查看表状态
来源：http://dali.chenjidiqi.icu/Article/details/gthnwjufbh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gthsaaabao.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtfvvimavo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gtgmeeksdo.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtznbtaxui.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gttrferaxk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.havefunace.top/Article/details/gtrlrnylzw.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gtjbdbsacf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gtmobnwkhb.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gtvaohieqx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gtkaigdsvd.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gtikssmsdd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jiagoushi.top/Article/details/gtwtbvxwsl.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtvutjkqkc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jiagoushi.top/Article/details/gtntkrpxqh.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gteoasciap.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtdlagmikj.html

[Q81] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtklrvkzea.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtcpljtuox.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gtzwwkcjft.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtxwobxekh.html

[Q83] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspiaqwor.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtoimkogkw.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangtech.top/Article/details/gtiznumnhx.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtsgpbfkvd.html

[Q85] 数值取整
来源：http://dali.9152youxi.cn/Article/details/gtxkhbfdne.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hfpthk.cn/Article/details/gtkbwrptet.html


<!-- 参考信息 -->