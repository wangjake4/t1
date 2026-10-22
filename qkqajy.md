代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwmfxadt.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctkxfloq.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gt2euamzuxv.html

Py:   async def f():⏎    await g()
来源：http://dali.sufxvd.cn/Article/details/gt2ipykoidy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gt2ppefwwgg.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gt2gjekwcdx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2wrozupmw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gt2ouxdzgqn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.9152youxi.cn/Article/details/gt2toeuxjmq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daria6918.cn/Article/details/gt2ygiifhkz.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gt2lesonald.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gt2unduklrp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2zpjgzkqt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gt2pqjgqttq.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gt2hkgiwdpz.html

TS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gt2ajirnpnh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gt2endznkrg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.316326.xyz/Article/details/gt2gbhwragm.html

Ruby: threads.map(&:join)
来源：http://dali.hfpthk.cn/Article/details/gt2myiqtmzf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gt2jemdnrve.html

[O06] 使用进程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2toxvefkq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hysaishi.cn/Article/details/gt2ekyyjqnu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daria6918.cn/Article/details/gt2iycbfutg.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2gtxcfrnm.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gt2dlrraqfo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sxryk.cn/Article/details/gt2irrmxnqw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.vqdsnc.cn/Article/details/gt2trvefwwm.html

Ruby: // fork 块
来源：http://dali.feifeiyinyue.top/Article/details/gt2huzzzcro.html

C#:   Parallel.For
来源：http://dali.kuanghao11.cn/Article/details/gt2elencscy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2yqxmxhek.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhtsmgp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2mtoqxuqe.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gt2ludaaxga.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gt2fmtqbwih.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wlveevlk.html

JS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gt2ycwsrqyp.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gt2nnnrpdat.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gt2rljurals.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dashuyun.cn/Article/details/gt2fodolzkq.html

Ruby: SecureRandom.uuid
来源：http://dali.fengsongda.top/Article/details/gt2pevchjev.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gt2wtkfydku.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jyoumei.cn/Article/details/gt2oakzmoia.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sxryk.cn/Article/details/gt2knopweqr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gt2mukewidn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigufen.top/Article/details/gt2tnlexzlr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.316326.xyz/Article/details/gt2awqdpgmk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrtetlsl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gt2chqkrzgy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.bjfxy.top/Article/details/gt2lgaswqoi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hfpthk.cn/Article/details/gt2kgfrkhah.html

[P03] 生成短随机字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2imrnrxjn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj202588.top/Article/details/gt2vuuwkwca.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gt2yfsnnpfo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gt2lanmdqjl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gt2laxdlpvl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xylfe.cn/Article/details/gt2achtvxmw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktujfags.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.birdmap.top/Article/details/gt2ifnlqmzb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqmodel.html

[P04] 求长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcfjucng.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gt2umxiepsy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2xrnocqym.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gt2uznhxapl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gt2yyxrdwie.html

Java: list.size();  map.size();  s.length()
来源：http://dali.iojbl.cn/Article/details/gt2pqrlojaw.html

Go:   len(arr);  len(m)
来源：http://dali.meibo888.top/Article/details/gt2fzkivffq.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2ossnegcn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shzxlz.cn/Article/details/gt2ezwnogpu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhiwuduotai.top/Article/details/gt2yooslros.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gt2awebbyvk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gt2wsslyowo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gt2uqanozap.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gt2gqenrbug.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gt2oybrgwaw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2xkdgbail.html

Ruby: a == b
来源：http://dali.jiagoushi.top/Article/details/gt2plujfyfi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxuanxn.top/Article/details/gt2sakngqdx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gt2vvmoibyr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ydzc1.top/Article/details/gt2tzkmutpt.html

PHP:  if (empty($x)) {}
来源：http://dali.xylfe.cn/Article/details/gt2dacskpys.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fzhhl.top/Article/details/gt2cixjfcoz.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gt2pgsmewbw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gt2ipdxnyes.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gt2xtobcgym.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hongshengwenyu.top/Article/details/gt2norvsiis.html

C#:   if (x is null) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2knvrhyeu.html

[P07] 防抖与节流
来源：http://dali.shuidangran.top/Article/details/gt2rmcqsqrc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.meibo888.top/Article/details/gt2zcxpbccd.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gt2nwvbrffr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ddguncqs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gt2unnayjou.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jyoumei.cn/Article/details/gt2tmbiilyt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gt2ivvpftky.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gt2luwujxln.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gt2rzgzaioz.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gt2abjdqmzi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gt2wciwkypc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2yqmvilvm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.svipenyu.cn/Article/details/gt2xslfterg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gt2nwlaiunn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.bjfxy.top/Article/details/gt2aqbychtd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hfpthk.cn/Article/details/gt2cxzeaver.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gt2azcusolb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gt2apgcvcju.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2wlwlmduz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gt2yjqairql.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2nnlhfwuy.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gt2syjimkcx.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gt2mvraeeuy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2ppzyxqoc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gt2paqcgpis.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yangfankeji.com/Article/details/gt2ajgonsnf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gt2kcnmtads.html

);
来源：http://dali.gogol.net.cn/Article/details/gt2vlyedhgi.html

[Q02] 创建带外键的表
来源：http://dali.cashguo.top/Article/details/gt2mpedsedh.html

CREATE TABLE orders (
来源：http://dali.jyoumei.cn/Article/details/gt2nbirspwa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gt2shicjshd.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gt2wfqtpnkf.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gt2dpkngqmp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gt2ruruphfa.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzmrpvpb.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gt2ydmyackz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jyoumei.cn/Article/details/gt2jmkuqegr.html

[Q04] 修改列类型
来源：http://dali.sweek.top/Article/details/gt2kfghbuty.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gt2jnybhnqi.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gt2ewhmocrm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yonumen.top/Article/details/gt2xpqqhqff.html

[Q06] 删除列
来源：http://dali.jyoumei.cn/Article/details/gt2beicyfmv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gt2umthcxrk.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gt2qvhvddir.html

DROP TABLE IF EXISTS orders;
来源：http://dali.iojbl.cn/Article/details/gt2laylqtmz.html

[Q08] 创建普通索引
来源：http://dali.xinyue.icu/Article/details/gt2hpumkfbu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gt2bpdwzgxp.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gt2izbwzwkj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gt2bljjsqlq.html

[Q10] 插入单行
来源：http://dali.316326.xyz/Article/details/gt2fgdimrsc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yvedp.cn/Article/details/gt2vkerqgvq.html

[Q11] 一次插入多行
来源：http://dali.yj20258888.top/Article/details/gt2fitxcrxf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shzxlz.cn/Article/details/gt2jwbmvqnz.html

[Q12] 插入后取自增 ID
来源：http://dali.aizwys.cn/Article/details/gt2blisahrv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258.top/Article/details/gt2kvccvnbv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gt2sxzxycxe.html

[Q13] 忽略重复插入
来源：http://dali.meibo888.top/Article/details/gt2dtpzaesc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgfzy.top/Article/details/gt2ysmksvmo.html

[Q14] 存在则更新（upsert）
来源：http://dali.feifeiyinyue.top/Article/details/gt2srpfttnp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aibaodan.cn/Article/details/gt2bswfavfm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gt2szsxurxy.html

[Q15] 查询全部
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhypxwyr.html

SELECT * FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2refsyucy.html

[Q16] 查询指定列
来源：http://dali.wangshuangyany.cn/Article/details/gt2gxwfbvtq.html

SELECT id, name FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hoclklca.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gt2jtbazxit.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2lwrzatfq.html

[Q18] 模糊匹配
来源：http://dali.ivvv.top/Article/details/gt2yxdbvkqv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yonumen.top/Article/details/gt2jxpbzqun.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2bznobqmi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjcmdagh.html

[Q20] IN 列表
来源：http://dali.cashguo.top/Article/details/gt2qdqagakd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2jrrlntiy.html

[Q21] 空值判断
来源：http://dali.vqdsnc.cn/Article/details/gt2nqoibvnh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yvedp.cn/Article/details/gt2jjhtnbwk.html

[Q22] 排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqjbidvd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenzaomai.com/Article/details/gt2emkaeydb.html

[Q23] 分页
来源：http://dali.chenlongwang.top/Article/details/gt2xhamagbq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gzhubu.top/Article/details/gt2voawewuq.html

[Q24] 去重
来源：http://dali.hywenlv.cn/Article/details/gt2kdgrkgil.html

SELECT DISTINCT city FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2diokuiik.html

[Q25] 只取前 N 条
来源：http://dali.hammf.cn/Article/details/gt2uxbrqfsi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.iojbl.cn/Article/details/gt2uwypwrrd.html

[Q26] 计数
来源：http://dali.hnxiangtu.top/Article/details/gt2adggeeui.html

SELECT COUNT(*) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2fpptltki.html

[Q27] 条件计数
来源：http://dali.jlsjyb.cn/Article/details/gt2lusidqjw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2kvycndsj.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gt2yhactqqw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2nzkcgmcm.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gt2ijamreqe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2trsevruz.html

[Q30] 分组统计
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrwtxkkt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gt2jopebupx.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gt2byexjowm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aizwys.cn/Article/details/gt2lifqcvnn.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2iucbsnrc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gt2ewawficv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yvedp.cn/Article/details/gt2vzpczkzt.html

[Q33] 多列分组
来源：http://dali.9152youxi.cn/Article/details/gt2jendpozx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gt2oftoxjcj.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gt2rgdhigxl.html

SELECT * FROM (
来源：http://dali.smart0.xyz/Article/details/gt2dtockgql.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jyoumei.cn/Article/details/gt2vczcpvdi.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2hugczzex.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gt2kuqqpsec.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2thgytzbc.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvdpsgsg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdpfjpns.html

[Q37] 右连接
来源：http://dali.ehwqpu.com/Article/details/gt2ebawcdgk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cashguo.top/Article/details/gt2lyoubxps.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.9152youxi.cn/Article/details/gt2eydpvhuf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.iojbl.cn/Article/details/gt2sktggrob.html

[Q39] 自连接（查上下级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkhntyjh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.havefunace.top/Article/details/gt2hyvaxpgv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gt2bpzvtaqb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxddxwyf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gt2euppcxyn.html

[Q41] 多表连接
来源：http://dali.jinqigfzy.top/Article/details/gt2btnwslae.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sysykeji.top/Article/details/gt2ookeizoz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abobjwdb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gt2cmwuxckl.html

[Q42] 连接条件附加过滤
来源：http://dali.guannengcc.top/Article/details/gt2qkrzjhrs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fzhhl.top/Article/details/gt2ylcbjkjf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gotoacloud.top/Article/details/gt2ieguygld.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gt2vlvgnwqf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gt2mtalxtge.html

[Q44] IN 子查询
来源：http://dali.jqgfzy.top/Article/details/gt2bkwbfted.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daxiang520.top/Article/details/gt2hbacmabd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gt2landtbnu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gt2radezmeg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cashguo.top/Article/details/gt2vohattgl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gt2bozjnkod.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgiaqfui.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hysaishi.cn/Article/details/gt2dbheoypf.html

[Q48] CTE 公用表表达式
来源：http://dali.yonumen.top/Article/details/gt2ssojmcgl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxinkj.top/Article/details/gt2zefzdaan.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmojohdd.html

[Q49] 更新单行
来源：http://dali.feifeiyinyue.top/Article/details/gt2ouabvwwq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gt2ktxrmlmg.html

[Q50] 批量更新
来源：http://dali.yj20258888.top/Article/details/gt2xzqfqqfk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gt2jvgjbyiv.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvuzaufz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2hgbsyqdt.html

[Q52] 删除指定行
来源：http://dali.ehwqpu.com/Article/details/gt2aeubmtyv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gt2hwxyofvq.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytwzrlfj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cashguo.top/Article/details/gt2vujtoead.html

[Q54] 清空表
来源：http://dali.nwbrower.top/Article/details/gt2yzozwrpf.html

TRUNCATE TABLE logs;
来源：http://dali.hfpthk.cn/Article/details/gt2jviqwpug.html

[Q55] 排名（并列占位）
来源：http://dali.jyoumei.cn/Article/details/gt2mvcalsgv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ydzc1.top/Article/details/gt2iqjjojdm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zdqjudy.top/Article/details/gt2rzciaygg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gt2souytzfh.html

[Q57] 行号
来源：http://dali.dianchejie.cn/Article/details/gt2xemenbze.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2zkjeojfb.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gt2nligqlgz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2gllpcvcj.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gt2vhzdjdfk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2amszmpkc.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gt2fhemjqjf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuxming.cn/Article/details/gt2fngecdjx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2eogrtems.html

[Q61] 移动平均
来源：http://dali.ppjwa.cn/Article/details/gt2hefuqfkm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2mhivhoqd.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gt2hhagtrzs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2kkoeelfs.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gt2uakwifch.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gt2rtsddjwy.html

[Q64] 提交事务
来源：http://dali.mhx1999.top/Article/details/gt2hpjlujjv.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gt2bzvmxrwr.html

[Q65] 回滚事务
来源：http://dali.yvedp.cn/Article/details/gt2easggygv.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gt2kytajwln.html

[Q66] 行锁查询
来源：http://dali.tanke756.top/Article/details/gt2txkxklta.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gt2xfqtxzzi.html

[Q67] 设置隔离级别
来源：http://dali.jqgfzy.top/Article/details/gt2nhckmoxl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zdqjudy.top/Article/details/gt2hxydxead.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gt2xnrebobu.html

SAVEPOINT sp1;
来源：http://dali.quarkkingdee.top/Article/details/gt2elvywfwq.html

ROLLBACK TO sp1;
来源：http://dali.dianchejie.cn/Article/details/gt2uikzxaha.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gt2fvwhtssa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gt2sddqdtfh.html

[Q70] 更新统计信息
来源：http://dali.sweek.top/Article/details/gt2egazppgb.html

ANALYZE TABLE users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxhwgmvq.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gt2nhcwetlf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gt2erhdiovl.html

[Q72] 查看索引
来源：http://dali.tian-w.cn/Article/details/gt2ghmsslpn.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2krfrnpfp.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gt2teepgeop.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.iojbl.cn/Article/details/gt2opmooltg.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gt2muhbpwjg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenlongwang.top/Article/details/gt2pfkvxbqw.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2cmumtgel.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjlywwyp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gt2anfuampk.html

[Q76] 按天统计
来源：http://dali.vqdsnc.cn/Article/details/gt2aftfcvhm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebsulkuv.html

[Q77] 时间加减
来源：http://dali.guannengcc.top/Article/details/gt2ojvhytup.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gzhubu.top/Article/details/gt2nvoedutu.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gt2nwaabajl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gt2kabvagig.html

[Q79] 字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gt2ogocvtbh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.birdmap.top/Article/details/gt2dheshppf.html

[Q80] 字符串截取
来源：http://dali.nwbrower.top/Article/details/gt2wbbwhrmv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2odpozeyh.html

[Q81] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gt2qbxleujz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2xxjvhyga.html

[Q82] 字符长度与字节长度
来源：http://dali.gogol.net.cn/Article/details/gt2fxtcqzag.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2ghezgfmu.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gt2lwualxpj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzklrpik.html

[Q84] 去除首尾空格
来源：http://dali.zhongyouzk.top/Article/details/gt2zljwnlau.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2nahjwiud.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gt2afzubvwl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gt2rbuaqhgu.html


<!-- 参考信息 -->