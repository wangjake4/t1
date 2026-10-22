代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cdnleiting.top/Article/details/gt2rcuvuyky.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gt2ehzrpjii.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gt2tfbrqwsc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvnvfhzm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gt2bkyotqqz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gt2urnhnuha.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gt2oxzzfqii.html

[O05] 并发执行并等待全部完成
来源：http://dali.hywenlv.cn/Article/details/gt2ceygdhbq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fengsongda.top/Article/details/gt2qhklsvbz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.316326.xyz/Article/details/gt2efssawiu.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2ukhlvbkq.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gt2pnpbjkug.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jlsjyb.cn/Article/details/gt2pduyccbv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gt2flcvcxwn.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kpacwnuh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnqzz.top/Article/details/gt2yraoffjv.html

[O06] 使用进程池
来源：http://dali.gzhubu.top/Article/details/gt2pqfjoomm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gt2mkglybxj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuanzx.com/Article/details/gt2apxdkwqc.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gt2tlmwedzf.html

TS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gt2lmnjdbxv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.bjfxy.top/Article/details/gt2mfwszyuh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gt2kxofcmya.html

Ruby: // fork 块
来源：http://dali.hnqzz.top/Article/details/gt2ejpmluyl.html

C#:   Parallel.For
来源：http://dali.kuanghao11.cn/Article/details/gt2nclixzbi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ddhlnyyz.html

P. 常用工具函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjrrojia.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2awphniks.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gt2kplbrrre.html

Py:   str(uuid.uuid4())
来源：http://dali.cucudq.cn/Article/details/gt2ocmrqnrv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gyooxlyp.html

JS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gt2tplswzgt.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gt2npfgubbo.html

Java: UUID.randomUUID().toString()
来源：http://dali.gogol.net.cn/Article/details/gt2nszswrqy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ivvv.top/Article/details/gt2zucoqrba.html

Ruby: SecureRandom.uuid
来源：http://dali.zhixingplan.top/Article/details/gt2zfxnfnuk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gt2wvnlhtjw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shzxlz.cn/Article/details/gt2uwozqztm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ybcxt.top/Article/details/gt2ufoyqjlg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubgpljxs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gt2ifbytnvo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gt2kilhxuta.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2impqwbba.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2duwxokdv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gt2rrhohsby.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cheryme.top/Article/details/gt2qrozhwcm.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gt2aclcsdtx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gt2ttlyfcpz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.svipenyu.cn/Article/details/gt2jjgagsnv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gt2wpqzaues.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gt2wkwsdlhk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oiewsnif.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangshuangyany.cn/Article/details/gt2outfhcrc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mtmhclpe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xziqi.cn/Article/details/gt2rzqdywtm.html

[P04] 求长度
来源：http://dali.jinqigfzy.top/Article/details/gt2smorjlze.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvygxqby.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2jechzioo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmjuqip.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gt2tuzmsooy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dashuyun.cn/Article/details/gt2hpzxbmlm.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gt2dcdtokwl.html

Ruby: x.length;  x.size
来源：http://dali.yonumen.top/Article/details/gt2rqicfzlj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhengqikj.top/Article/details/gt2xevzfuqv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gt2oiohchzv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.316326.xyz/Article/details/gt2hwuumqnf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gt2hlwnhvte.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gt2lqntrpyt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2bxugnirw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gt2soikmfuf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2eetxwjvr.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gt2qvtmubiu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yanxiufei.cn/Article/details/gt2afxoenmn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gt2yiawopdf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shuidangran.top/Article/details/gt2irkcdnpl.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gt2gysjxdhq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qofaejmg.html

TS:   if (x == null) {}
来源：http://dali.yuxming.cn/Article/details/gt2dvyxhifg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2caiwwyzu.html

Go:   if x == nil {}
来源：http://dali.birdmap.top/Article/details/gt2wtyvxmjd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigfzy.top/Article/details/gt2wxquqgdr.html

C#:   if (x is null) {}
来源：http://dali.xinyue.icu/Article/details/gt2cauktfhr.html

[P07] 防抖与节流
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmdwucum.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gt2dddthasg.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gt2ubvsnjge.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gt2oahlgemk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gt2zfrrajjk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuanzhike.top/Article/details/gt2xsixleex.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tianlin.xyz/Article/details/gt2lhkgdmfn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gt2qnnilmwk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnqzz.top/Article/details/gt2cuwozpgi.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gt2ixuxggdd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenzaomai.com/Article/details/gt2crvnlbjd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzqybjcd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yangfankeji.com/Article/details/gt2zvfhtdma.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gt2lwtkxsvu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.9152youxi.cn/Article/details/gt2efcspult.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xylfe.cn/Article/details/gt2aqpgacje.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.c1oappe.top/Article/details/gt2clujnotd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fzhhl.top/Article/details/gt2qqrgobly.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2rfrbipcg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gogol.net.cn/Article/details/gt2obwzoymm.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2qcyjeumc.html

[Q01] 创建表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxchnity.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gt2jwwwzlvf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gt2ynbxbkza.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2smhuueor.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yangfankeji.com/Article/details/gt2prkouysb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.mhx1999.top/Article/details/gt2zftoqsim.html

);
来源：http://dali.shzxlz.cn/Article/details/gt2zyrlijfb.html

[Q02] 创建带外键的表
来源：http://dali.zycfv.cn/Article/details/gt2qhbcwczs.html

CREATE TABLE orders (
来源：http://dali.jinqigfzy.top/Article/details/gt2katckhed.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gt2oysjblpa.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gt2yiapesvb.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gt2mcqvttmk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gt2yrfrxamd.html

);
来源：http://dali.tianlin.xyz/Article/details/gt2dkubdpcy.html

[Q03] 增加列
来源：http://dali.yangfankeji.com/Article/details/gt2cgnnnssd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fdgjezhy.html

[Q04] 修改列类型
来源：http://dali.chenzaomai.com/Article/details/gt2cvvdzola.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yueranfly.top/Article/details/gt2ejqhqtno.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gt2zcqppgtr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhongyouzk.top/Article/details/gt2hdjakzhd.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gt2qqrvvskl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ybcxt.top/Article/details/gt2crxstwce.html

[Q07] 删除表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzfnwwpf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.birdmap.top/Article/details/gt2hgutkezu.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gt2opznmrfr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gt2ttmyowjb.html

[Q09] 创建唯一索引
来源：http://dali.yonumen.top/Article/details/gt2psivylxq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gt2zswxrarg.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gt2xpimzshu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gt2voiwofbg.html

[Q11] 一次插入多行
来源：http://dali.sweek.top/Article/details/gt2kdhhpzlw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.svipenyu.cn/Article/details/gt2ebuokeoi.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gt2njfxwuxt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aizwys.cn/Article/details/gt2vgwjxxdv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwhcpnlt.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gt2wprgmcqr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.haohaochexian.top/Article/details/gt2vyfkatkc.html

[Q14] 存在则更新（upsert）
来源：http://dali.guannengcc.top/Article/details/gt2roufjbfj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yonumen.top/Article/details/gt2wyfulfze.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gt2csxnybui.html

[Q15] 查询全部
来源：http://dali.cdnleiting.top/Article/details/gt2rdnfnqnd.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2pdauerxj.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gt2owdxrjol.html

SELECT id, name FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2hrmofvyz.html

[Q17] 条件查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfnvaqie.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xziqi.cn/Article/details/gt2klqlmvms.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gt2oogeykuu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgufenzy.top/Article/details/gt2eacvxyej.html

[Q19] 范围查询
来源：http://dali.zycfv.cn/Article/details/gt2cydjyjjt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gt2cntrrmiu.html

[Q20] IN 列表
来源：http://dali.svipenyu.cn/Article/details/gt2bequuoto.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cdnleiting.top/Article/details/gt2oydtqped.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gt2xphfwljk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gt2qwjcfnmb.html

[Q22] 排序
来源：http://dali.cqqwz.cn/Article/details/gt2bpjpkzoa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.svipenyu.cn/Article/details/gt2ytjxbjsp.html

[Q23] 分页
来源：http://dali.xinyue.icu/Article/details/gt2zblvivcz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258888.top/Article/details/gt2csljduxm.html

[Q24] 去重
来源：http://dali.yvedp.cn/Article/details/gt2dqdfcmec.html

SELECT DISTINCT city FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2wxikqdnd.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gt2lrzczrko.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gt2rfqndddj.html

[Q26] 计数
来源：http://dali.sweek.top/Article/details/gt2asugdxhf.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2bwgyeegx.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gt2vkqltklu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2kdvsrpni.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gt2owxjbawp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2vekodhsr.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gt2zhrkjmdc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2ibslgvyo.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gt2owdntqwp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gt2asoqcyru.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gt2danvfqbp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dianchejie.cn/Article/details/gt2ifqovfdc.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2ccswwhic.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gt2yyntwddn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gt2gwrmevau.html

[Q33] 多列分组
来源：http://dali.iojbl.cn/Article/details/gt2jgqojdcu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ehwqpu.com/Article/details/gt2sckfgqqa.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gt2pzpoojyh.html

SELECT * FROM (
来源：http://dali.jinqigfzy.top/Article/details/gt2kcupqwfc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgfonugw.html

) t WHERE rn = 1;
来源：http://dali.yvedp.cn/Article/details/gt2thxvnwdj.html

[Q35] 内连接
来源：http://dali.chenlongwang.top/Article/details/gt2wmsazqzb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fguqnwef.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gt2ndlczejw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2zlrmcwhl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmpegvn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ppjwa.cn/Article/details/gt2ajqcstsy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yvedp.cn/Article/details/gt2gsqmefim.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gcecsfnn.html

[Q39] 自连接（查上下级）
来源：http://dali.svipenyu.cn/Article/details/gt2nidcyjfh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gt2wizhhgfp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gt2sgvoffjp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuanzx.com/Article/details/gt2kmxfdujx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gzhubu.top/Article/details/gt2mlxnwkay.html

[Q41] 多表连接
来源：http://dali.kuanghao11.cn/Article/details/gt2yjonbfoe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.316326.xyz/Article/details/gt2higkalan.html

JOIN users u ON u.id = o.user_id
来源：http://dali.9152youxi.cn/Article/details/gt2kufvkeil.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.bjfxy.top/Article/details/gt2zlnxlmry.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gt2pbdejfre.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gogol.net.cn/Article/details/gt2tkcglsus.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gt2zrpralwn.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gt2onofzteb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fsxyjocr.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gt2tdamlygb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gt2digmrpiu.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gt2sqzppfox.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gt2yfywyonc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yonumen.top/Article/details/gt2yelnjfve.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gt2uphsunqv.html

[Q47] 与平均值比较
来源：http://dali.yuanzhike.top/Article/details/gt2sbjshsnr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guowangkeji.top/Article/details/gt2fbdkwsov.html

[Q48] CTE 公用表表达式
来源：http://dali.snrcjt.cn/Article/details/gt2hmedansn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sufxvd.cn/Article/details/gt2cwccensh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xylfe.cn/Article/details/gt2hqksewer.html

[Q49] 更新单行
来源：http://dali.havefunace.top/Article/details/gt2gbmwbvth.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gt2qxsfiolf.html

[Q50] 批量更新
来源：http://dali.fzhhl.top/Article/details/gt2buwdzyuw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yueranfly.top/Article/details/gt2wnhvlxpf.html

[Q51] 用子查询更新
来源：http://dali.hnxiangtu.top/Article/details/gt2kwadotmz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2sjwlzrhd.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gt2dqybjhle.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2ostklqpy.html

[Q53] 按条件删除
来源：http://dali.zhiwuduotai.top/Article/details/gt2yiwyqqsp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gt2qsztwwvf.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gt2njpvyngo.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gt2fzpaqdlv.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gt2ablgjpws.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gt2xzbqnxvr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gt2gioltftl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwfejbjd.html

[Q57] 行号
来源：http://dali.ppjwa.cn/Article/details/gt2lmnbxnos.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2taejsvlr.html

[Q58] 累计求和
来源：http://dali.yueranfly.top/Article/details/gt2hotystab.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxaopsbh.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gt2mzuoucxp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2skzsmuni.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gt2pjuswrlf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigfzy.top/Article/details/gt2urixjgkf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2xltscsgv.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gt2sctpkxdh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2vegnscoi.html

[Q62] 分组占比
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cprutvhx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2qxbrrhmt.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gt2iieqpuhm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gt2bdfrugdz.html

[Q64] 提交事务
来源：http://dali.pycfn.com/Article/details/gt2ncqbfnqp.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gt2qycvmxcc.html

[Q65] 回滚事务
来源：http://dali.kuanghao11.cn/Article/details/gt2xzlccnax.html

ROLLBACK;
来源：http://dali.zdqjudy.top/Article/details/gt2gbtjlwqd.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gt2fktfvmqw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujmxzipw.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gyhyciad.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gt2ethtczjd.html

[Q68] 保存点
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjswerec.html

SAVEPOINT sp1;
来源：http://dali.nanxinkj.top/Article/details/gt2gzmjzhts.html

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gt2xpwgytkh.html

[Q69] 查看执行计划
来源：http://dali.xinyue.icu/Article/details/gt2oqosmdmf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gt2wueipciv.html

[Q70] 更新统计信息
来源：http://dali.andypj.xyz/Article/details/gt2wzsqvlos.html

ANALYZE TABLE users;
来源：http://dali.haohaochexian.top/Article/details/gt2wcytfnvy.html

[Q71] 查看建表语句
来源：http://dali.fzhhl.top/Article/details/gt2dkzcoqri.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gt2jdftpths.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gt2rhyictai.html

SHOW INDEX FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2ipgvbhzs.html

[Q73] 查看表状态
来源：http://dali.svipenyu.cn/Article/details/gt2lrhrotgh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.quarkkingdee.top/Article/details/gt2zrastncx.html

[Q74] 强制使用索引
来源：http://dali.jinqigufen.top/Article/details/gt2aktdruip.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gt2fyvqjzkc.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2dpmfwpiu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2mmxflrly.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sysykeji.top/Article/details/gt2hswmyytw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sydxkhfy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gt2ngetgobi.html

[Q77] 时间加减
来源：http://dali.tian-w.cn/Article/details/gt2cljzwhns.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tianlin.xyz/Article/details/gt2knuvcssb.html

[Q78] 当前时间
来源：http://dali.gotoacloud.top/Article/details/gt2ayelzvyx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenzaomai.com/Article/details/gt2exeocnyv.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gt2ykssnxxj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yangfankeji.com/Article/details/gt2bdqfyume.html

[Q80] 字符串截取
来源：http://dali.kuanghao11.cn/Article/details/gt2jhlrudka.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2zuplfklv.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gt2sampbssx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.meibo888.top/Article/details/gt2pcgsyupy.html

[Q82] 字符长度与字节长度
来源：http://dali.zycfv.cn/Article/details/gt2igfjpjir.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2brmgcdvi.html

[Q83] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gt2mwcjwgcm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2zvrspqlk.html

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gt2aduzhdwn.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2alyobqmy.html

[Q85] 数值取整
来源：http://dali.daxiang520.top/Article/details/gt2dutsulln.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sweek.top/Article/details/gt2qgxpqkqq.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gt2lavbgwrd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gt2fcgwjghf.html

[Q87] JSON 字段做条件
来源：http://dali.bjfxy.top/Article/details/gt2zobtwkgr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.redwolf501.top/Article/details/gt2mjcdvvkb.html


<!-- 参考信息 -->