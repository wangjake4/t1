代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gt2rwdtkxls.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gt2vjavvyvq.html

[O04] 定义异步函数并等待
来源：http://dali.redwolf501.top/Article/details/gt2atktzuci.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gt2uqnjqijo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gt2dzkqlgde.html

JS:   async function f() { await g(); }
来源：http://dali.fengsongda.top/Article/details/gt2xwjklvsw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.smart0.xyz/Article/details/gt2ushscfbq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqwstrmz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.haohaochexian.top/Article/details/gt2filkfpku.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cqqwz.cn/Article/details/gt2yhfllknt.html

C#:   async Task F() { await G(); }
来源：http://dali.cheryme.top/Article/details/gt2vcylkxfc.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gt2puzbpvpk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigfzy.top/Article/details/gt2pmokoeid.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gt2tuijyvlg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gt2mflvldix.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gt2qtkhbycj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.kuanghao11.cn/Article/details/gt2vagyriwp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gt2zqwtgqej.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gt2quqcwsho.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gt2ogjqhvby.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvyzyxpu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jlsjyb.cn/Article/details/gt2gkyasvfb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gt2tnyoxlyq.html

JS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpqldqjc.html

TS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gt2qcvvupob.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gt2vacgjvhh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gt2fzrlrzok.html

Ruby: // fork 块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hraqlroc.html

C#:   Parallel.For
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlrsbjjh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ctbzspvq.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gt2lmejescw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2lhkbsvhz.html

[P01] 生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gt2rsaqgbhr.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gt2scjlcxmr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gt2tqkexafv.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2rczqjquv.html

TS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2tmmhwocf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gt2bgixkfmh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.haohaochexian.top/Article/details/gt2slkhetuw.html

Ruby: SecureRandom.uuid
来源：http://dali.hnqzz.top/Article/details/gt2cxnzertr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gt2kzjeskxs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gt2uvvtzvtv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hysaishi.cn/Article/details/gt2ksedhiyp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.bjfxy.top/Article/details/gt2ehqbgdnj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ivvv.top/Article/details/gt2qadqwqld.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gt2zxyankrb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2wdoqhvje.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gt2zswufaag.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cqqwz.cn/Article/details/gt2wdmnbjuo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gt2gpstflon.html

[P03] 生成短随机字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzefrrey.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gt2rdzolome.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daxiang520.top/Article/details/gt2cvgdrslt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gt2qhpiuolp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gt2zrchyvgk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gt2ptvhynma.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gt2alukmyre.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigfzy.top/Article/details/gt2wqllypec.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gt2okdhkanw.html

[P04] 求长度
来源：http://dali.pycfn.com/Article/details/gt2kdsgndmk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gt2egvoffks.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2zavwxigy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gt2orkbbmpi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gt2vqixaflv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsmgauup.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gt2clztficz.html

Ruby: x.length;  x.size
来源：http://dali.redwolf501.top/Article/details/gt2zlcddxrs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2lzbrfevz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gt2ecwllugd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gt2dfkbvzjc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfqocgfo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gt2bkstodtw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gt2wgqxhogf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzikfccm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2qytefjhr.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oabrdknr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.redwolf501.top/Article/details/gt2eyzpeyns.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gt2gmrtaspk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.haohaochexian.top/Article/details/gt2fsxtbgpk.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2pvcfbxyk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xinyue.icu/Article/details/gt2zvnyzkdg.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gt2ubmtudtz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gt2mpvmnigp.html

Go:   if x == nil {}
来源：http://dali.birdmap.top/Article/details/gt2mmxptiuo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncobmuvg.html

C#:   if (x is null) {}
来源：http://dali.yuxming.cn/Article/details/gt2eomvifpg.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gt2lhdrrzur.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gt2ugnrutsy.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oudmrhxt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2kzbykser.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gt2kamgrwjn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zdqjudy.top/Article/details/gt2axbhqrgd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.redwolf501.top/Article/details/gt2vvdymnyf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.quarkkingdee.top/Article/details/gt2dgfvzqaf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gt2ujtxyvng.html

[P08] 处理浮点精度问题
来源：http://dali.iojbl.cn/Article/details/gt2cwgrtzfr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gt2yjadllhi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2rfcfyfmg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258.top/Article/details/gt2rpeezxwz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2jzcjgpsj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pycfn.com/Article/details/gt2gkgpvyzt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.kuanghao11.cn/Article/details/gt2jxkurpjd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zdqjudy.top/Article/details/gt2xgqgxasm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wlperlag.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2zuvrnaky.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shuidangran.top/Article/details/gt2ppnaihbc.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2vnpyjvlk.html

[Q01] 创建表
来源：http://dali.sxryk.cn/Article/details/gt2vnofcpki.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xnvhqsrr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gt2yqolbphc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pycfn.com/Article/details/gt2avemefhr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ivvv.top/Article/details/gt2pyqhxrik.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.9152youxi.cn/Article/details/gt2vbxvmxni.html

);
来源：http://dali.cheryme.top/Article/details/gt2opqrrulx.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gt2poebzwng.html

CREATE TABLE orders (
来源：http://dali.sysykeji.top/Article/details/gt2tthhafyy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gt2gynoqtqn.html

user_id INT NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gt2kcydhizz.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gt2dwuhuhwa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gt2cmpkbmds.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2raoicjxg.html

[Q03] 增加列
来源：http://dali.gotoacloud.top/Article/details/gt2nrtuyiaw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258888.top/Article/details/gt2xgnothii.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gt2amcsdiau.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gt2vdpzdnvh.html

[Q05] 重命名列
来源：http://dali.xziqi.cn/Article/details/gt2lasfwguc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylcicgyw.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gt2sjayjpho.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxgqdiee.html

[Q07] 删除表
来源：http://dali.hnqzz.top/Article/details/gt2twtyrzwb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.snrcjt.cn/Article/details/gt2cfnspfkd.html

[Q08] 创建普通索引
来源：http://dali.sufxvd.cn/Article/details/gt2ptqdqgid.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gt2wqzcdooc.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gt2hgkgkqtd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gt2gxubmkhs.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gt2lgudketm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gt2hqayrfkf.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gt2gkrrvzkn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2grgloefa.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gt2qricjmzl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigufen.top/Article/details/gt2qcohenyt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gt2xoczolzl.html

[Q13] 忽略重复插入
来源：http://dali.fengsongda.top/Article/details/gt2plmwbtqs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ppjwa.cn/Article/details/gt2sfzcmnfq.html

[Q14] 存在则更新（upsert）
来源：http://dali.tanke756.top/Article/details/gt2enyfsydw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.birdmap.top/Article/details/gt2bnfjnwfi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yanxiufei.cn/Article/details/gt2yvvnocvb.html

[Q15] 查询全部
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhogfbte.html

SELECT * FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2xwscmtvp.html

[Q16] 查询指定列
来源：http://dali.9152youxi.cn/Article/details/gt2jzhynjnh.html

SELECT id, name FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2xszozhuz.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gt2nqhjgago.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gt2tremsnor.html

[Q18] 模糊匹配
来源：http://dali.yuxming.cn/Article/details/gt2ajbitqna.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cucudq.cn/Article/details/gt2bbnnprcr.html

[Q19] 范围查询
来源：http://dali.tanke756.top/Article/details/gt2vttcjzda.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gt2mnlagmha.html

[Q20] IN 列表
来源：http://dali.hysaishi.cn/Article/details/gt2ydihcxwd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gt2cmerrnbi.html

[Q21] 空值判断
来源：http://dali.cucudq.cn/Article/details/gt2fejfycuz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tianlin.xyz/Article/details/gt2ckickclv.html

[Q22] 排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pizcmtlp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.mhx1999.top/Article/details/gt2dwukperm.html

[Q23] 分页
来源：http://dali.aizwys.cn/Article/details/gt2nnldgycz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wsokjdom.html

[Q24] 去重
来源：http://dali.ehwqpu.com/Article/details/gt2sgwwtsqx.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gt2blwvowyr.html

[Q25] 只取前 N 条
来源：http://dali.ehwqpu.com/Article/details/gt2rsoetnrr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gt2yardhrqp.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gt2whabtjmd.html

SELECT COUNT(*) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2abudybym.html

[Q27] 条件计数
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzbidfwb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lphzetph.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gt2zibmlaru.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2mxohjzzm.html

[Q29] 最大最小值
来源：http://dali.0kj1m.cn/Article/details/gt2omjkpeia.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2rssxthen.html

[Q30] 分组统计
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdxmgdmp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2kxgcmvwc.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gt2gbtxrkbm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2syghnzlw.html

[Q32] 分组拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gt2poswulgb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2kqniqzms.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2glzpcerv.html

[Q33] 多列分组
来源：http://dali.sufxvd.cn/Article/details/gt2lgwuujqb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnqzz.top/Article/details/gt2rcpwjusa.html

[Q34] 每组取第一条
来源：http://dali.zycfv.cn/Article/details/gt2dyaqgxxm.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gt2gyazipnz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gt2uzflgfcq.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2icbhuawz.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gt2ujrqftfi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gt2rngfjapd.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gt2rxjyctyz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gt2hgmvmtvn.html

[Q37] 右连接
来源：http://dali.jinqigufen.top/Article/details/gt2cdmhkztp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.iojbl.cn/Article/details/gt2snxwkfzl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guannengcc.top/Article/details/gt2cozkgetb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvkhzsgj.html

[Q39] 自连接（查上下级）
来源：http://dali.tianlin.xyz/Article/details/gt2rqokgfyv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tianlin.xyz/Article/details/gt2dzkouesk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gotoacloud.top/Article/details/gt2qhbijrnq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gt2kizkecst.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fzhhl.top/Article/details/gt2qvkszykd.html

[Q41] 多表连接
来源：http://dali.havefunace.top/Article/details/gt2zgzlzzsj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fengsongda.top/Article/details/gt2yygxcfsz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gt2olxwkxmb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gt2femkyqnf.html

[Q42] 连接条件附加过滤
来源：http://dali.cqqwz.cn/Article/details/gt2lwcujezy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gt2uocwmggw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ybcxt.top/Article/details/gt2duqzqlpd.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gt2upablybj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gaohongyu789.top/Article/details/gt2fhftogxk.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gt2nagzvkqg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gt2zkybbxex.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vehkwwbk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gt2mggfwnvu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sxryk.cn/Article/details/gt2bfnhppjb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gt2sxrrtvro.html

[Q47] 与平均值比较
来源：http://dali.cucudq.cn/Article/details/gt2fhmugtbi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.9152youxi.cn/Article/details/gt2cvcyymxh.html

[Q48] CTE 公用表表达式
来源：http://dali.andypj.xyz/Article/details/gt2uiafhwid.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxinkj.top/Article/details/gt2ovukndpm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gt2vjnlictn.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gt2bhfsfrii.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gt2akmvwqif.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gt2chagfuke.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.meibo888.top/Article/details/gt2miqvxqrv.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gt2qadkrpii.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2fzrbclna.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gt2quuxihbf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gt2ssiynpvi.html

[Q53] 按条件删除
来源：http://dali.gzhubu.top/Article/details/gt2efjmwftv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shuidangran.top/Article/details/gt2kvjlhqli.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gt2ptoifebx.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gt2mnfubadm.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gt2yxtulcxl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.meibo888.top/Article/details/gt2ykujshyp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuanzx.com/Article/details/gt2ikexykcn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gt2hdsfmodi.html

[Q57] 行号
来源：http://dali.cashguo.top/Article/details/gt2fonqlhwd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2mhsmkmlk.html

[Q58] 累计求和
来源：http://dali.kuanghao11.cn/Article/details/gt2apkvecaj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2bmoboqsj.html

[Q59] 分组内累计
来源：http://dali.fengsongda.top/Article/details/gt2jgsvdnlq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qiabqzsw.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gt2qaqnuttv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gt2otxovzjv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2lxutwqyx.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gt2giyhlszo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2zstxzsxh.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gt2nmexcvrz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2fqddtxld.html

[Q63] 开启事务
来源：http://dali.cucudq.cn/Article/details/gt2oyjrbrsa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sweek.top/Article/details/gt2eeryaqsv.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gt2gwtkbsmp.html

COMMIT;
来源：http://dali.gaohongyu789.top/Article/details/gt2helszund.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gt2ygfkmyau.html

ROLLBACK;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifxzusnc.html

[Q66] 行锁查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrvulfbh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shzxlz.cn/Article/details/gt2xizxhexq.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gt2zpojlqaj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.andypj.xyz/Article/details/gt2lufosrsf.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdkjlezd.html

SAVEPOINT sp1;
来源：http://dali.9152youxi.cn/Article/details/gt2noceewiq.html

ROLLBACK TO sp1;
来源：http://dali.dianchejie.cn/Article/details/gt2wzbamfhc.html

[Q69] 查看执行计划
来源：http://dali.aibaodan.cn/Article/details/gt2qrwakzdk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gt2rphjlrur.html

[Q70] 更新统计信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnsssljd.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gt2ntlhykio.html

[Q71] 查看建表语句
来源：http://dali.zhoulong.xyz/Article/details/gt2tvajspqn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdiqqwhs.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gt2spdwyuox.html

SHOW INDEX FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2spegjqed.html

[Q73] 查看表状态
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkpjjmpx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnepihum.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gt2qokqbzrb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigufen.top/Article/details/gt2qvhosjct.html

[Q75] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gt2yivvexop.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2eoyphmfc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pfwzwovx.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gt2lvxwhdzx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gt2bbnestur.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gt2parrlilt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.c1oappe.top/Article/details/gt2fzgzvgya.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gt2qgicczkk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gogol.net.cn/Article/details/gt2lzokbhid.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gt2cxiepreg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258888.top/Article/details/gt2rhjqgvef.html

[Q80] 字符串截取
来源：http://dali.daxiang520.top/Article/details/gt2angkxysb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmvivfvw.html

[Q81] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gt2pcystkez.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcojfraf.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gt2khcptdni.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2nkqwojxp.html

[Q83] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2imzikxnx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2iprhlokn.html

[Q84] 去除首尾空格
来源：http://dali.cdnleiting.top/Article/details/gt2qdvzrtvk.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2nykhfzvl.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gt2lghgksue.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gt2bcwndumc.html


<!-- 参考信息 -->