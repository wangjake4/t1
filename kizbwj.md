代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gaohongyu789.top/Article/details/gt2wlddrtuz.html

C#:   lock (gate) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gt2stugknol.html

[O04] 定义异步函数并等待
来源：http://dali.guannengcc.top/Article/details/gt2tftyfksy.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gt2fjmdpxjd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjcmjopo.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gt2cznhwntg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gt2mrjmifnr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gt2cnawnwtw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gt2shdagxkj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gt2gdrdpwev.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gt2pxniiglb.html

[O05] 并发执行并等待全部完成
来源：http://dali.quarkkingdee.top/Article/details/gt2jrrokdoo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gt2vimxysux.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gt2dmlatpet.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gt2zaqlryme.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2popeaewn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gt2cysjvnoj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.vqdsnc.cn/Article/details/gt2kxntokfi.html

Ruby: threads.map(&:join)
来源：http://dali.bjfxy.top/Article/details/gt2kxdeducs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuxming.cn/Article/details/gt2zrnyhdbg.html

[O06] 使用进程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awfuoflh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gt2ksblmuuc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sweek.top/Article/details/gt2tyqucyic.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2ngdxtaoq.html

TS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gt2bndzppur.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sysykeji.top/Article/details/gt2jxckgkne.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gt2llznnzum.html

Ruby: // fork 块
来源：http://dali.kuanghao11.cn/Article/details/gt2nmvvosgh.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gt2tnsehwwt.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2opcxjugx.html

P. 常用工具函数
来源：http://dali.jqgfzy.top/Article/details/gt2mlxqtuhu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2hrjzpelb.html

[P01] 生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gt2dbegyjpq.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gt2zysrlkrg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuanzhike.top/Article/details/gt2wpsmafnm.html

JS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gt2xxorprar.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gt2exayixke.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvhvrgxs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gt2lbswcnmy.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gt2oukolwbw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gt2nuiavtxb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gt2wqusapvt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gt2wczzvncj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gt2xkplgghf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gt2bemxrzdx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jiagoushi.top/Article/details/gt2hbthfhdv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2hwqepqzn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xinyue.icu/Article/details/gt2cwodbdsv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tian-w.cn/Article/details/gt2txsiisax.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cashguo.top/Article/details/gt2gahjkjjx.html

[P03] 生成短随机字符串
来源：http://dali.redwolf501.top/Article/details/gt2koyihgyy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gt2hwpgcoyb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhengqikj.top/Article/details/gt2yfhnpafg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gt2itwimfrr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gt2dhtvhoel.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.316326.xyz/Article/details/gt2fedakqbn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxuanxn.top/Article/details/gt2bfhlzykp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yvedp.cn/Article/details/gt2eilfsqjs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nwbrower.top/Article/details/gt2bastezxm.html

[P04] 求长度
来源：http://dali.sufxvd.cn/Article/details/gt2tijxlbjq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dashuyun.cn/Article/details/gt2yfjrajtf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wezfdmpf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gt2efbsirac.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gt2beuckrup.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yangfankeji.com/Article/details/gt2qymhwxje.html

Go:   len(arr);  len(m)
来源：http://dali.wangdashe.top/Article/details/gt2fshmjkzo.html

Ruby: x.length;  x.size
来源：http://dali.iojbl.cn/Article/details/gt2skcmilpt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gt2ewodnckj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gt2mxivwuwe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuanzhike.top/Article/details/gt2sssawmso.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yueranfly.top/Article/details/gt2qqhnnhab.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxuanxn.top/Article/details/gt2goiwmrpz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gt2nenobjqv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gt2xywepsnv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obdcqpsg.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gt2dkpowvlz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shuidangran.top/Article/details/gt2cibyleqv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrogilqj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuanzx.com/Article/details/gt2ffbknhnj.html

PHP:  if (empty($x)) {}
来源：http://dali.zhixingplan.top/Article/details/gt2wlzwnvrj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gzhubu.top/Article/details/gt2rrektmvx.html

TS:   if (x == null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2nenmdopt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gt2wmhoznjq.html

Go:   if x == nil {}
来源：http://dali.jqgfzy.top/Article/details/gt2xqtnpppv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuanzx.com/Article/details/gt2biznsxww.html

C#:   if (x is null) {}
来源：http://dali.daxiang520.top/Article/details/gt2mhcxuueb.html

[P07] 防抖与节流
来源：http://dali.haohaochexian.top/Article/details/gt2dhxhmtkz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgufenzy.top/Article/details/gt2fjocqjnn.html

PHP:  // 手写时间戳比较
来源：http://dali.andypj.xyz/Article/details/gt2mecplhzx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2vnpqlcyn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gt2jcfztarn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.bjfxy.top/Article/details/gt2ijkvqtqy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cdnleiting.top/Article/details/gt2biurkggp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jianghu66.top/Article/details/gt2jgjdvvff.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.meibo888.top/Article/details/gt2oxshubgm.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gt2qofsqhok.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gotoacloud.top/Article/details/gt2dyvmwnks.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gt2jspillut.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dpvzmjme.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gt2srvsngdr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gt2ntszgneg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yangfankeji.com/Article/details/gt2hsrzczzy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gt2lvvxhlvd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cashguo.top/Article/details/gt2hajybdfu.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2npytjcsi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gt2eooivykz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ueqmidba.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gt2gmutjipg.html

CREATE TABLE users (
来源：http://dali.zdqjudy.top/Article/details/gt2uakkgpiw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gt2timvcfwj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gt2hdozrxwx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfzvwcht.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.vqdsnc.cn/Article/details/gt2clxpdioi.html

);
来源：http://dali.zhongyouzk.top/Article/details/gt2hdmsokzq.html

[Q02] 创建带外键的表
来源：http://dali.shuidangran.top/Article/details/gt2wuztlqsa.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gt2gfrzqaeh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gt2qtkkxdhv.html

user_id INT NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gt2odxfvhat.html

amount DECIMAL(10, 2),
来源：http://dali.pengpengdd.cyou/Article/details/gt2uutmsyva.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjnpjvxt.html

);
来源：http://dali.havefunace.top/Article/details/gt2gnhhkdcq.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dpsyqjhc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gt2orkcmhvl.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbealwef.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gt2ricosasv.html

[Q05] 重命名列
来源：http://dali.wangshuangyany.cn/Article/details/gt2qoidhsky.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gt2bxhxjlss.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gt2gjawmzsu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnqzz.top/Article/details/gt2wvekkxhy.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gt2lhazocaw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gt2ypiqittl.html

[Q08] 创建普通索引
来源：http://dali.cheryme.top/Article/details/gt2nvswrekf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfjnpzov.html

[Q09] 创建唯一索引
来源：http://dali.vqdsnc.cn/Article/details/gt2moyuexlw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gt2ldsnutmw.html

[Q10] 插入单行
来源：http://dali.zhengqikj.top/Article/details/gt2lsapctbq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daria6918.cn/Article/details/gt2ujxawhde.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gt2vithcspo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gt2ndzctpjh.html

[Q12] 插入后取自增 ID
来源：http://dali.sysykeji.top/Article/details/gt2mhanmkmo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hywenlv.cn/Article/details/gt2nruuwexg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangdashe.top/Article/details/gt2yfdeomjn.html

[Q13] 忽略重复插入
来源：http://dali.hnxiangtu.top/Article/details/gt2vdyraola.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sysykeji.top/Article/details/gt2zabtkfbm.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gt2bncpdvfl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jiagoushi.top/Article/details/gt2cmmzpltd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ybcxt.top/Article/details/gt2okmkiwhu.html

[Q15] 查询全部
来源：http://dali.fengsongda.top/Article/details/gt2ucelymgu.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2lcauwpgh.html

[Q16] 查询指定列
来源：http://dali.yj202588.top/Article/details/gt2mweuglwy.html

SELECT id, name FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tmwjgozl.html

[Q17] 条件查询
来源：http://dali.ehwqpu.com/Article/details/gt2pkhxdcpk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.mhx1999.top/Article/details/gt2qzhnlogj.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gt2feufcoqf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.vqdsnc.cn/Article/details/gt2tykdcwwt.html

[Q19] 范围查询
来源：http://dali.aibaodan.cn/Article/details/gt2ofbwozjz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.birdmap.top/Article/details/gt2bzjvasfe.html

[Q20] IN 列表
来源：http://dali.guowangkeji.top/Article/details/gt2rtwrevsn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pulcgwci.html

[Q21] 空值判断
来源：http://dali.jianghu66.top/Article/details/gt2tsfxmrwp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.redwolf501.top/Article/details/gt2qnekukiz.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gt2dpcdegok.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gt2ekzgzwwy.html

[Q23] 分页
来源：http://dali.gogol.net.cn/Article/details/gt2yhcirfao.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.smart0.xyz/Article/details/gt2ogxgxyih.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gt2wvwfajrp.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jovwgryu.html

[Q25] 只取前 N 条
来源：http://dali.vqdsnc.cn/Article/details/gt2arfkahqv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jiagoushi.top/Article/details/gt2dqelpeyp.html

[Q26] 计数
来源：http://dali.hfpthk.cn/Article/details/gt2nqqmjatl.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2vkmydnud.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gt2vbwbnmdi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2romnzbzf.html

[Q28] 求和与平均
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqmkfhuh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2fanprimh.html

[Q29] 最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gt2kopkbhsk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2zrakxhxi.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gt2hjtbxndu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2xjqafghl.html

[Q31] 分组后过滤
来源：http://dali.0kj1m.cn/Article/details/gt2rvvglajb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gt2jiagcxld.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2pdqjrdtd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gt2hsoymlii.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.c1oappe.top/Article/details/gt2gmopsyev.html

[Q33] 多列分组
来源：http://dali.svipenyu.cn/Article/details/gt2mtgwxazl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gt2ahjmdnsb.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gt2dhiigjwj.html

SELECT * FROM (
来源：http://dali.andypj.xyz/Article/details/gt2ddlwotfk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daria6918.cn/Article/details/gt2mmbvykft.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2vlofdbzq.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2xiogmqlb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gt2rxofojfe.html

[Q36] 左连接
来源：http://dali.yanxiufei.cn/Article/details/gt2ulnuazyw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2dfffgqlo.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gt2zeitlgxh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhongyouzk.top/Article/details/gt2qvjfzind.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guannengcc.top/Article/details/gt2fpmyeenu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gt2vjcvxpuk.html

[Q39] 自连接（查上下级）
来源：http://dali.aizwys.cn/Article/details/gt2ewtfoyuj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hysaishi.cn/Article/details/gt2alkhmivr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2wnkztqny.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gt2yjdavzlw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gt2lpcgigeh.html

[Q41] 多表连接
来源：http://dali.zhongyouzk.top/Article/details/gt2hwhjsiqa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gt2ypnqrnzz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gt2jcfvejsj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.bjfxy.top/Article/details/gt2ndepwqty.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gt2lmjisuqn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqgcybdi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ydzc1.top/Article/details/gt2yhtzaakk.html

[Q43] 标量子查询
来源：http://dali.nanxuanxn.top/Article/details/gt2cbngiqmh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gt2clwdvxyv.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gt2lruxkqvl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.kuanghao11.cn/Article/details/gt2wufoafaz.html

[Q45] EXISTS 判断存在
来源：http://dali.ppjwa.cn/Article/details/gt2ucwnliud.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lxeeznxa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gt2uepljssz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gt2uidujycq.html

[Q47] 与平均值比较
来源：http://dali.cdnleiting.top/Article/details/gt2mnyrupht.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfdpwnlf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2vgnvbiyk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yvgbaogj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenzaomai.com/Article/details/gt2atntgwld.html

[Q49] 更新单行
来源：http://dali.hnxiangtu.top/Article/details/gt2umqcevuj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2svegsjss.html

[Q50] 批量更新
来源：http://dali.shuidangran.top/Article/details/gt2sisdzmyr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gt2rhevuldl.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gt2qxfnuexk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.andypj.xyz/Article/details/gt2bjaxdyef.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gt2xdhnynpt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gt2mamtetbm.html

[Q53] 按条件删除
来源：http://dali.xuanzx.com/Article/details/gt2bzhooawi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gt2wfvpynei.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gt2cvnsuiwo.html

TRUNCATE TABLE logs;
来源：http://dali.yangfankeji.com/Article/details/gt2abrohuks.html

[Q55] 排名（并列占位）
来源：http://dali.hysaishi.cn/Article/details/gt2xvkuutxv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gt2dpjbpjmw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gt2ttyhgqxl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gt2mdsjauph.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gt2qkckubmk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2xinfqjko.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gt2xunquoes.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2ykjbxugx.html

[Q59] 分组内累计
来源：http://dali.hammf.cn/Article/details/gt2yoteuick.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2wswijjtg.html

[Q60] 取上一行 / 下一行
来源：http://dali.haohaochexian.top/Article/details/gt2vyjlbafu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258888.top/Article/details/gt2dwujiwcp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2povkiyvw.html

[Q61] 移动平均
来源：http://dali.gzhubu.top/Article/details/gt2ztklkbeg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2vazrvpjf.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gt2dowsybax.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2eljhijdr.html

[Q63] 开启事务
来源：http://dali.zycfv.cn/Article/details/gt2ywbnerde.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nwbrower.top/Article/details/gt2zyrturhp.html

[Q64] 提交事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgwpcsdw.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gt2ovaqtidx.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gt2pvsignxv.html

ROLLBACK;
来源：http://dali.hnqzz.top/Article/details/gt2eceqmsqn.html

[Q66] 行锁查询
来源：http://dali.pycfn.com/Article/details/gt2zojwlcot.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cashguo.top/Article/details/gt2jiboyedh.html

[Q67] 设置隔离级别
来源：http://dali.dashuyun.cn/Article/details/gt2yqkdvaat.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gt2vcferbns.html

[Q68] 保存点
来源：http://dali.daria6918.cn/Article/details/gt2uvtakgwy.html

SAVEPOINT sp1;
来源：http://dali.xylfe.cn/Article/details/gt2guplkhbl.html

ROLLBACK TO sp1;
来源：http://dali.dashuyun.cn/Article/details/gt2pyezcquu.html

[Q69] 查看执行计划
来源：http://dali.hammf.cn/Article/details/gt2wahnrqym.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.meibo888.top/Article/details/gt2rvmgifrt.html

[Q70] 更新统计信息
来源：http://dali.mhx1999.top/Article/details/gt2rpbjjzxd.html

ANALYZE TABLE users;
来源：http://dali.yueranfly.top/Article/details/gt2pottkqts.html

[Q71] 查看建表语句
来源：http://dali.aibaodan.cn/Article/details/gt2zzrmbclo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gt2axzjeocq.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gt2whfugvha.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrjtjdck.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gt2ukbpybvi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dgliupii.html

[Q74] 强制使用索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trrfkynu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gt2rrzzxuwq.html

[Q75] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2zyzkbtub.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2pbohjppy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ppjwa.cn/Article/details/gt2ymwwxpif.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bglywwsl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tanke756.top/Article/details/gt2ccakehdx.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gt2xaesxkkp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sufxvd.cn/Article/details/gt2gjqvrqfh.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pbktqwjz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gt2qaeqkeoc.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gt2obxdxotb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tian-w.cn/Article/details/gt2qzwpghvz.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gt2xelhqtzm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2meugmixr.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gt2awffftrz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2gxanqtnb.html

[Q82] 字符长度与字节长度
来源：http://dali.hnqzz.top/Article/details/gt2idcnnaqp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2dsofugik.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2zixcqzss.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2dtrblzad.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gt2bhwdmsob.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2hbdfosvg.html

[Q85] 数值取整
来源：http://dali.xziqi.cn/Article/details/gt2mtnewztq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenzaomai.com/Article/details/gt2itxoqgzx.html


<!-- 参考信息 -->