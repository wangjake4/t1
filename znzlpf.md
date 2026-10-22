代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gt2srxuofzu.html

C#:   lock (gate) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gt2eqdwgvev.html

[O04] 定义异步函数并等待
来源：http://dali.smart0.xyz/Article/details/gt2dtixooav.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gt2xnkktehv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hfpthk.cn/Article/details/gt2dibxwdlu.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2visnfzrh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gt2cuorstcg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gt2ujmvdonq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigfzy.top/Article/details/gt2qofkdecr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xinyue.icu/Article/details/gt2jkamubih.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gt2rhligmts.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gt2eeoyuvuk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gt2gltdlkab.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigfzy.top/Article/details/gt2eehaeuks.html

JS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gt2jllcgbvb.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gt2etrmfwfm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gt2cpzcyehr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gt2erfwdqlw.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gt2qyjinndi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gt2mdckvczt.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gt2xyiwkktb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hysaishi.cn/Article/details/gt2lzrukotx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gt2hijbfieh.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gt2vnlkecwm.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2amuytope.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gt2iqcvzdpa.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gt2evgscykl.html

Ruby: // fork 块
来源：http://dali.xinyue.icu/Article/details/gt2xecdhwwu.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gt2iwgpcaaw.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2gzidmfrd.html

P. 常用工具函数
来源：http://dali.chenzaomai.com/Article/details/gt2cdnukqba.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2lhdgtptj.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gt2nxkxidfx.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gt2mmqhgqxb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gt2yetvcngy.html

JS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gt2tjnjjtcy.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2oqvzhfvc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gt2kuqfhmnv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.bjfxy.top/Article/details/gt2fmcsqbqo.html

Ruby: SecureRandom.uuid
来源：http://dali.aizwys.cn/Article/details/gt2bxfzbahr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjdodsot.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daxiang520.top/Article/details/gt2tyymurpz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgufenzy.top/Article/details/gt2dwinzozg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gt2sewnnefm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhrzdsjl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ehwqpu.com/Article/details/gt2msnogsav.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gt2xhwrqull.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhoulong.xyz/Article/details/gt2wugjtsbf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gt2xftmffuc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gt2nklrcquz.html

[P03] 生成短随机字符串
来源：http://dali.sxryk.cn/Article/details/gt2jougjxap.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gt2jxoynppx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.vqdsnc.cn/Article/details/gt2vgnmzotw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gt2jcdizzjz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gt2vyzthrps.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2jjlixksa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tian-w.cn/Article/details/gt2htnpykjs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhixingplan.top/Article/details/gt2qqegutlu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhnwxsvx.html

[P04] 求长度
来源：http://dali.fzhhl.top/Article/details/gt2cvcpmnsz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pycfn.com/Article/details/gt2lhesbjie.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2jowkinou.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gt2evyluzra.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gt2sosifcct.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwqortcd.html

Go:   len(arr);  len(m)
来源：http://dali.nwbrower.top/Article/details/gt2egsiopnl.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gt2ajkrnexs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258.top/Article/details/gt2kkuimgmj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gt2bowpyjov.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gt2kihjffkh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgdoyhtu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjvxqxls.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gt2cjmchfrh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gt2nsovpgky.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gt2qzgmspdc.html

Ruby: a == b
来源：http://dali.yangfankeji.com/Article/details/gt2zxunggfz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.feifeiyinyue.top/Article/details/gt2yzfwhjsh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258888.top/Article/details/gt2sthtkrtm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cheryme.top/Article/details/gt2kexuukyu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhixingplan.top/Article/details/gt2wsyqyxpj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gt2iqxhxyeg.html

TS:   if (x == null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ayjptirw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gt2wgjmbptf.html

Go:   if x == nil {}
来源：http://dali.snrcjt.cn/Article/details/gt2yhwbstlj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gt2fnjftssf.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gt2cqdnutdq.html

[P07] 防抖与节流
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghpgchtt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxinkj.top/Article/details/gt2nkfrbaqk.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gt2utadcyeu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gt2qcgemvte.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gt2zrcaromc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj202588.top/Article/details/gt2vuhadcyf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.meibo888.top/Article/details/gt2olcswzin.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tianlin.xyz/Article/details/gt2zsbulgzq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gt2fewlgzzl.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gt2pbkotzub.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gt2hdpzutvj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tian-w.cn/Article/details/gt2amuxldox.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gt2cobatndi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gt2cmruhnmm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jiagoushi.top/Article/details/gt2rcxixhoy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gt2ljutihob.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guowangkeji.top/Article/details/gt2tgwuxsgt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpreluu.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2noasfawm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gt2ywqmcvex.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2vnlyslhu.html

[Q01] 创建表
来源：http://dali.dashuyun.cn/Article/details/gt2ftnvgedm.html

CREATE TABLE users (
来源：http://dali.nwbrower.top/Article/details/gt2alspyadv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gt2yqygdonz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gt2ytjypvwk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gt2qpnlkohu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.9152youxi.cn/Article/details/gt2qwszijzi.html

);
来源：http://dali.cashguo.top/Article/details/gt2slkdhllu.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gt2xjsnenqk.html

CREATE TABLE orders (
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwuaqfjk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gt2fzwlvphi.html

user_id INT NOT NULL,
来源：http://dali.yj202588.top/Article/details/gt2gukouxih.html

amount DECIMAL(10, 2),
来源：http://dali.xuetiantiany.cn/Article/details/gt2ezctiyzf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gt2jvawczsb.html

);
来源：http://dali.zhoulong.xyz/Article/details/gt2knnkzbkm.html

[Q03] 增加列
来源：http://dali.meibo888.top/Article/details/gt2fgzxrbhk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shzxlz.cn/Article/details/gt2mnwbravc.html

[Q04] 修改列类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqgelsdp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pycfn.com/Article/details/gt2stgehuui.html

[Q05] 重命名列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzamaalg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daxiang520.top/Article/details/gt2doeblwbx.html

[Q06] 删除列
来源：http://dali.fzhhl.top/Article/details/gt2iqcahlie.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.quarkkingdee.top/Article/details/gt2pgjdttof.html

[Q07] 删除表
来源：http://dali.mhx1999.top/Article/details/gt2vncsgmwr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gt2pmglvqqp.html

[Q08] 创建普通索引
来源：http://dali.xylfe.cn/Article/details/gt2lqdwehoa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gt2imivokiz.html

[Q09] 创建唯一索引
来源：http://dali.redwolf501.top/Article/details/gt2lxzjsiwm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gt2npcwjcbp.html

[Q10] 插入单行
来源：http://dali.jqgufenzy.top/Article/details/gt2ihqcftam.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gt2hyjfzaxg.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gt2yergdeax.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2plptsgua.html

[Q12] 插入后取自增 ID
来源：http://dali.wangdashe.top/Article/details/gt2qequoqis.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dianchejie.cn/Article/details/gt2nxxrrufv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhongyouzk.top/Article/details/gt2ouysckqg.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gt2dvsjuizu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gt2cxhbdkxp.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gt2bvwgtoyk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gt2bttqdfud.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gt2sdutygme.html

[Q15] 查询全部
来源：http://dali.ppjwa.cn/Article/details/gt2fcxivwjx.html

SELECT * FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2kfcctltx.html

[Q16] 查询指定列
来源：http://dali.ivvv.top/Article/details/gt2mpnxzdqc.html

SELECT id, name FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2jfzihgrd.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gt2jttiwyey.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lzebusck.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2tigosspy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gt2dzmwuuoy.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gt2ymgmkgtm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gt2fkvdyxku.html

[Q20] IN 列表
来源：http://dali.zycfv.cn/Article/details/gt2gniwodla.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ehwqpu.com/Article/details/gt2yittgomk.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvbetnbm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yksflsxa.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gt2muxtkwhh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gt2rhqfjeov.html

[Q23] 分页
来源：http://dali.hysaishi.cn/Article/details/gt2eqfiveuh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gt2kqbjoqer.html

[Q24] 去重
来源：http://dali.yonumen.top/Article/details/gt2zqoesbhp.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xnnmnsql.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mskpjrhg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gt2svltjqdp.html

[Q26] 计数
来源：http://dali.jiagoushi.top/Article/details/gt2fbbtyswt.html

SELECT COUNT(*) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2vysznmyn.html

[Q27] 条件计数
来源：http://dali.snrcjt.cn/Article/details/gt2ixnhwwgi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2lzvcyjir.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gt2krmfywpo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2jebrkijx.html

[Q29] 最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gt2ygsdvocr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gcwitnfj.html

[Q30] 分组统计
来源：http://dali.sweek.top/Article/details/gt2wcljwhsx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gt2sphhqaiz.html

[Q31] 分组后过滤
来源：http://dali.jqgfzy.top/Article/details/gt2abqhrkuy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhengqikj.top/Article/details/gt2vxlfzlvj.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2cmmrbrqw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2mfjvwgvg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sufxvd.cn/Article/details/gt2fnzrczkk.html

[Q33] 多列分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzyshjwt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gt2xlsoweph.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gt2igzypvsk.html

SELECT * FROM (
来源：http://dali.quarkkingdee.top/Article/details/gt2qalxcccq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jianghu66.top/Article/details/gt2hniyprev.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gt2asarsbqp.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gt2lymxwhwh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krqdstxw.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gt2rsfjezem.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2voegmmto.html

[Q37] 右连接
来源：http://dali.hysaishi.cn/Article/details/gt2ybirrcyn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxuanxn.top/Article/details/gt2dsoxjalx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yvedp.cn/Article/details/gt2cytisdmb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gt2gblzemoy.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gt2mitdqgpt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jyoumei.cn/Article/details/gt2glrlwnzz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guowangkeji.top/Article/details/gt2saoieqnh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gt2kgnwdoei.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gt2rsaqjesl.html

[Q41] 多表连接
来源：http://dali.dashuyun.cn/Article/details/gt2knnhzfhe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gt2llgrnbdj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gt2heltknoh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yangfankeji.com/Article/details/gt2akwcujtd.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gt2imkuzxvo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gt2ewfxjssi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.quarkkingdee.top/Article/details/gt2vhmmandr.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gt2xekiyufh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj202588.top/Article/details/gt2gpsyxoyu.html

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gt2gnmnwxjn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.0kj1m.cn/Article/details/gt2bqveyeef.html

[Q45] EXISTS 判断存在
来源：http://dali.ydzc1.top/Article/details/gt2gszauicu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlthkty.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aibaodan.cn/Article/details/gt2lbagnycw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gt2ygozloom.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gt2zajpjvww.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gt2erqwgtzp.html

[Q48] CTE 公用表表达式
来源：http://dali.hywenlv.cn/Article/details/gt2bhivspdp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gt2vajjxrsy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gt2qbyeuvwn.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gt2kbogltbk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2bcdczrbn.html

[Q50] 批量更新
来源：http://dali.cashguo.top/Article/details/gt2kkxsigtt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfpnpqpj.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gt2xfvvtsir.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sweek.top/Article/details/gt2jrydvdex.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gt2imhkrbzm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gt2twsqlvzq.html

[Q53] 按条件删除
来源：http://dali.gzhubu.top/Article/details/gt2qiaqipyt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cashguo.top/Article/details/gt2rironyft.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gt2beianuey.html

TRUNCATE TABLE logs;
来源：http://dali.tian-w.cn/Article/details/gt2egrlvdzc.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gt2pgvvivmj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gt2qoiffcgu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hammf.cn/Article/details/gt2htbqgavz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnqzz.top/Article/details/gt2rqelewoe.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gt2jpfamusb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2uzrwtuhw.html

[Q58] 累计求和
来源：http://dali.jinqigfzy.top/Article/details/gt2oogscdih.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2tsfyoiww.html

[Q59] 分组内累计
来源：http://dali.zhoulong.xyz/Article/details/gt2sdfhftql.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2ytacprnw.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2deulkeao.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2promorqa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2rrespdnj.html

[Q61] 移动平均
来源：http://dali.0kj1m.cn/Article/details/gt2qrllltik.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2yllmfegl.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gt2tacokkyz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gt2vqhswbnc.html

[Q63] 开启事务
来源：http://dali.redwolf501.top/Article/details/gt2ubnlknbz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ydzc1.top/Article/details/gt2mtltzgje.html

[Q64] 提交事务
来源：http://dali.gotoacloud.top/Article/details/gt2styztyxi.html

COMMIT;
来源：http://dali.yonumen.top/Article/details/gt2eahynduo.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gt2ercqshyc.html

ROLLBACK;
来源：http://dali.kuanghao11.cn/Article/details/gt2nrzuxcja.html

[Q66] 行锁查询
来源：http://dali.jinqigfzy.top/Article/details/gt2zavboqmn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gt2sbeicczq.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gt2xifbwxvi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gt2aqvwihfb.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gt2gbpsrjpj.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gt2toapzqqx.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gt2vbgsujzw.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gt2ttxiynsn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aizwys.cn/Article/details/gt2szwpxxgi.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gt2wcyhiukd.html

ANALYZE TABLE users;
来源：http://dali.quarkkingdee.top/Article/details/gt2yzsmctwf.html

[Q71] 查看建表语句
来源：http://dali.jyoumei.cn/Article/details/gt2jrqdexcr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj202588.top/Article/details/gt2jbblsqlc.html

[Q72] 查看索引
来源：http://dali.sysykeji.top/Article/details/gt2rtxqdhfr.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2lmnmneso.html

[Q73] 查看表状态
来源：http://dali.yj20258888.top/Article/details/gt2jxwirmmk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.birdmap.top/Article/details/gt2rzmonlcv.html

[Q74] 强制使用索引
来源：http://dali.tanke756.top/Article/details/gt2puffldzt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cashguo.top/Article/details/gt2yzrcnjdt.html

[Q75] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gt2fwdlpabq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2akydfzxl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wdndjghx.html

[Q76] 按天统计
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpeetojp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gt2kdzcghgz.html

[Q77] 时间加减
来源：http://dali.pengpengdd.cyou/Article/details/gt2sphqofhf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zycfv.cn/Article/details/gt2ymzhffra.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2wkqbguat.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.316326.xyz/Article/details/gt2jlumqhyr.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksuofyfh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.birdmap.top/Article/details/gt2pxynreqg.html

[Q80] 字符串截取
来源：http://dali.svipenyu.cn/Article/details/gt2atjctgkf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2ugmzxjfp.html

[Q81] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gt2weayhgsq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2zgvhgxzz.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gt2hyqohcok.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2mmfvzllt.html

[Q83] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gt2ahksoibx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2selkhmpe.html

[Q84] 去除首尾空格
来源：http://dali.zycfv.cn/Article/details/gt2ivnqwhob.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2uatbmryk.html

[Q85] 数值取整
来源：http://dali.9152youxi.cn/Article/details/gt2yimmweeq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gt2oprejuce.html


<!-- 参考信息 -->