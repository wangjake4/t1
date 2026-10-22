代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpqrmefe.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gtsvbwkzwf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtjniotfna.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxinkj.top/Article/details/gtnjksuarl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumbequjx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gtaxtyrkzs.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gtllcpwjet.html

[O05] 并发执行并等待全部完成
来源：http://dali.tanke756.top/Article/details/gtymuaqpdc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.mhx1999.top/Article/details/gtasjgniox.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuetiantiany.cn/Article/details/gtmhqxcgtf.html

JS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqlbscxr.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtmdnuyhyv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxinkj.top/Article/details/gtykmuzacx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gtcksfwxbo.html

Ruby: threads.map(&:join)
来源：http://dali.ivvv.top/Article/details/gtqukrtzll.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.svipenyu.cn/Article/details/gtdlumgvzn.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gtvcrbiuos.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigufen.top/Article/details/gtgqggbilm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigfzy.top/Article/details/gtcswiwejh.html

JS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gtsvkujirp.html

TS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtfiekupgc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gtgcjgcezl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhkbkppx.html

Ruby: // fork 块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvexbsoti.html

C#:   Parallel.For
来源：http://dali.snrcjt.cn/Article/details/gtteulsjdf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzejxmsxy.html

P. 常用工具函数
来源：http://dali.guannengcc.top/Article/details/gtjazwzaos.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfdvaabbf.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gtwpgrqrvo.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gtxpyzbewb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnqzz.top/Article/details/gtogpltoqc.html

JS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtqvfyflxx.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtqftufiuv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhengqikj.top/Article/details/gtetsohept.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daria6918.cn/Article/details/gtszbjdauk.html

Ruby: SecureRandom.uuid
来源：http://dali.yangfankeji.com/Article/details/gtirqnsvca.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dashuyun.cn/Article/details/gtdcfygahh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.birdmap.top/Article/details/gtqruigjxj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258.top/Article/details/gtrweeffdi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gtifguodhm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gtgvfewxmx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.quarkkingdee.top/Article/details/gtdcyqaoye.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.havefunace.top/Article/details/gtbtqqeloj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gtndtzybzp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aizwys.cn/Article/details/gtbqcylhoq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gtggtmjyhc.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gtiqzzgzie.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gtrjfeswiw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xziqi.cn/Article/details/gtubmfkqwv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gthbxjcora.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtwybnrdud.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxuanxn.top/Article/details/gtzqemtlqj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gtkqvdokxa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhixingplan.top/Article/details/gtgpnunhbl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.vqdsnc.cn/Article/details/gtxtuunfko.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gtmxxaldfd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj202588.top/Article/details/gtdnotvijr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtictvylvi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtbgrocjws.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtlujatosd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtiypyzege.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gtknlpipnc.html

Ruby: x.length;  x.size
来源：http://dali.gzhubu.top/Article/details/gtrfbluipz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sysykeji.top/Article/details/gtfqvzmeje.html

[P05] 判断两个对象内容是否相等
来源：http://dali.c1oappe.top/Article/details/gtnjsdyjha.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gttvvqxsyt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gtjrtahigy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shuidangran.top/Article/details/gtjnuezcdh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtrypprbiw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cashguo.top/Article/details/gtrbpkdstn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtdfvgqlgy.html

Ruby: a == b
来源：http://dali.andypj.xyz/Article/details/gtkdjyujqz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xinyue.icu/Article/details/gtohkzxwxx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258888.top/Article/details/gtlfziubfk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cheryme.top/Article/details/gtfbcgtguo.html

PHP:  if (empty($x)) {}
来源：http://dali.aibaodan.cn/Article/details/gtlezcdxsh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtbgfyxyjs.html

TS:   if (x == null) {}
来源：http://dali.jyoumei.cn/Article/details/gtijmoongg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gttnuxttcj.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtzqkxuhkj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gtwoxrdxpi.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gtsqdmcseu.html

[P07] 防抖与节流
来源：http://dali.haohaochexian.top/Article/details/gthmihavtq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yangfankeji.com/Article/details/gtymtxcwqz.html

PHP:  // 手写时间戳比较
来源：http://dali.zdqjudy.top/Article/details/gtitqtmngg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtnlcmgypw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtflzdwgkj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gtosspconk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gtrgaruzxf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabzfeeyr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gtwrmwmnis.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gtvrymmsye.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnqzz.top/Article/details/gtzulodsae.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gtfcwncmjc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cqqwz.cn/Article/details/gtfbuxuzpz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtpjdoijhn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvtemzik.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbmihdlc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.birdmap.top/Article/details/gtahujznwr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gtgmhxodgc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwtwpbrnp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gtlqbokaaq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtplrsjrxr.html

[Q01] 创建表
来源：http://dali.ybcxt.top/Article/details/gtmlonofim.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtpatlziha.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtubwboass.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtnzvrrhbc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sufxvd.cn/Article/details/gtmxkngiua.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlxxolfa.html

);
来源：http://dali.hnxiangtu.top/Article/details/gtgweipjqe.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gtgzthsnhb.html

CREATE TABLE orders (
来源：http://dali.smart0.xyz/Article/details/gtksrkbzau.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtinrytiui.html

user_id INT NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtubwildqt.html

amount DECIMAL(10, 2),
来源：http://dali.mhx1999.top/Article/details/gtprdzyphe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvfrvvea.html

);
来源：http://dali.birdmap.top/Article/details/gtrqgyeqpt.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gtzuuuymfk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtuqgpikqa.html

[Q04] 修改列类型
来源：http://dali.wangshuangyany.cn/Article/details/gtnqhzuzvx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gtiillpvsy.html

[Q05] 重命名列
来源：http://dali.shzxlz.cn/Article/details/gthivcorym.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yanxiufei.cn/Article/details/gtiibfnwct.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gtmrqsalou.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cashguo.top/Article/details/gtxukuvugj.html

[Q07] 删除表
来源：http://dali.jinqigufen.top/Article/details/gtueidtqfq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yvedp.cn/Article/details/gtfduvejbx.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gtgvnifkzk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtrygdmnfx.html

[Q09] 创建唯一索引
来源：http://dali.dianchejie.cn/Article/details/gtnmfthsuf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtuiucfkqs.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbnpcgsz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gtwyppysvk.html

[Q11] 一次插入多行
来源：http://dali.zhixingplan.top/Article/details/gtcusfdtad.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtowxkzqov.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjnbjvqx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yangfankeji.com/Article/details/gtkokgsopj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tian-w.cn/Article/details/gtifxpmfqv.html

[Q13] 忽略重复插入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbenvoomd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gtrmcbdxmr.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gtlekrcunw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gthmgufazp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.9152youxi.cn/Article/details/gttfbececn.html

[Q15] 查询全部
来源：http://dali.yuanzhike.top/Article/details/gtsypfutay.html

SELECT * FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtoyoxqvxm.html

[Q16] 查询指定列
来源：http://dali.daria6918.cn/Article/details/gtknjqnhzu.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtcifimgtd.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gtnczsuujc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gtpoiiorvh.html

[Q18] 模糊匹配
来源：http://dali.quarkkingdee.top/Article/details/gtlzbfgrwx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtlupcenio.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gtcgddnlyh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gtoolilucj.html

[Q20] IN 列表
来源：http://dali.hnxiangtu.top/Article/details/gtoqmuhvuk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgfzy.top/Article/details/gtrwpsnyvn.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gtzcgbqlot.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gtcfgbmcin.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gtzkyanaxp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gtpcejidvy.html

[Q23] 分页
来源：http://dali.birdmap.top/Article/details/gtpbbfreil.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gtstfhotqx.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gtfomcfkzs.html

SELECT DISTINCT city FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtgfkgronj.html

[Q25] 只取前 N 条
来源：http://dali.zhixingplan.top/Article/details/gtqrfsnflb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigfzy.top/Article/details/gtfajkxdfj.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gtuigrzmni.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gttxkzvmtz.html

[Q27] 条件计数
来源：http://dali.gotoacloud.top/Article/details/gtbqtwebbz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtmhlcyukg.html

[Q28] 求和与平均
来源：http://dali.cdnleiting.top/Article/details/gtjmimzlrs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtjfmnvdra.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gtecyddcso.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtmyovplmg.html

[Q30] 分组统计
来源：http://dali.wangshuangyany.cn/Article/details/gtnedlsbxq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtryusalat.html

[Q31] 分组后过滤
来源：http://dali.yonumen.top/Article/details/gtvgziwyuq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gtdyezxwmf.html

[Q32] 分组拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtuzfltxiy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gthnmgvmhy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gtslxtrevo.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gtrkxeixwq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.iojbl.cn/Article/details/gtxftzslwp.html

[Q34] 每组取第一条
来源：http://dali.chenjidiqi.icu/Article/details/gtcmhipptv.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gtrszisqah.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.316326.xyz/Article/details/gtwmcxtztb.html

) t WHERE rn = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlvuvmoa.html

[Q35] 内连接
来源：http://dali.shuidangran.top/Article/details/gtpzyzupng.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gttvevxpmb.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gtwybnvxfj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtovdsyhjs.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gtatppvatn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtezzdcuzp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sweek.top/Article/details/gtosbnhqmj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tian-w.cn/Article/details/gtygxjysei.html

[Q39] 自连接（查上下级）
来源：http://dali.bjfxy.top/Article/details/gtlpwgbkdr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sxryk.cn/Article/details/gtlrwozimn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gtqyyigsld.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gtlwvcrgmt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gttpslttfc.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gtcmkvqnzc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gtojwvoror.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gogol.net.cn/Article/details/gtkzmkenst.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gtufppxhif.html

[Q42] 连接条件附加过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnfbfcjm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daria6918.cn/Article/details/gthbxozyjp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.iojbl.cn/Article/details/gtiqjcicth.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuoucfelm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.havefunace.top/Article/details/gtuycqplhl.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gtefbeqfly.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gtvkfulexp.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gtwqrzjnzt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtjnywmuxy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gthexhavgw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtetnvxluj.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtsgofkdaq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidkrnfdp.html

[Q48] CTE 公用表表达式
来源：http://dali.gaohongyu789.top/Article/details/gtrhufgatb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigufen.top/Article/details/gtevgcbvhc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gtmdskettg.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gtmlbyvcfu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtjahsdyjk.html

[Q50] 批量更新
来源：http://dali.xinyue.icu/Article/details/gtnxyyniqe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdovcuidq.html

[Q51] 用子查询更新
来源：http://dali.wangdashe.top/Article/details/gtbbmgxmxq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnxiangtu.top/Article/details/gthrxyjtsq.html

[Q52] 删除指定行
来源：http://dali.gaohongyu789.top/Article/details/gtbgfsyrwu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtqqxpblcz.html

[Q53] 按条件删除
来源：http://dali.meibo888.top/Article/details/gtixwoxvbg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtfksnwiit.html

[Q54] 清空表
来源：http://dali.shangyingyoupin.top/Article/details/gtccslhsgi.html

TRUNCATE TABLE logs;
来源：http://dali.wangshuangyany.cn/Article/details/gthjcbwcvx.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gtfhlbuzhw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtiuelczbi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtbxcklivt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gttgeuqwia.html

[Q57] 行号
来源：http://dali.aibaodan.cn/Article/details/gtyehdpbfz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.iojbl.cn/Article/details/gtadyadckv.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gtypdnqzlo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtyfykekbz.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gtvgszlfeb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtfbpdwmst.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gtittnyiga.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gtvhchfvwk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gttmuukvhk.html

[Q61] 移动平均
来源：http://dali.andypj.xyz/Article/details/gtrolgfqul.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtudgdeilu.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gtqgkqgeph.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttetztype.html

[Q63] 开启事务
来源：http://dali.ehwqpu.com/Article/details/gtiummlqfy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcaojylhy.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gtxdczuykt.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gtafiyntgq.html

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gtecmacccm.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gtbfzsdwrh.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gtongtvqvb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.kuanghao11.cn/Article/details/gthntjxdpf.html

[Q67] 设置隔离级别
来源：http://dali.aizwys.cn/Article/details/gtownpuoac.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gtefdyikca.html

[Q68] 保存点
来源：http://dali.zhongyouzk.top/Article/details/gthqurbbyt.html

SAVEPOINT sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtxhuwvkfc.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gtvsgtpaup.html

[Q69] 查看执行计划
来源：http://dali.sufxvd.cn/Article/details/gtjqumspom.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gttxoljhym.html

[Q70] 更新统计信息
来源：http://dali.smart0.xyz/Article/details/gtdjuqxvti.html

ANALYZE TABLE users;
来源：http://dali.xylfe.cn/Article/details/gtrprqooyo.html

[Q71] 查看建表语句
来源：http://dali.c1oappe.top/Article/details/gtcddjjkbu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gtxanbuzxs.html

[Q72] 查看索引
来源：http://dali.dianchejie.cn/Article/details/gtldcqkvpb.html

SHOW INDEX FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtqqibadme.html

[Q73] 查看表状态
来源：http://dali.xylfe.cn/Article/details/gtyjyzcdix.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.iojbl.cn/Article/details/gtjzykoqmj.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gtdabmkvwd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gttdpoeodz.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtaskrktym.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtpqpmizzl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangshuangyany.cn/Article/details/gtausigbsg.html

[Q76] 按天统计
来源：http://dali.shzxlz.cn/Article/details/gtaoxkxxwr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbaifnrmd.html

[Q77] 时间加减
来源：http://dali.smart0.xyz/Article/details/gthawzywnc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ehwqpu.com/Article/details/gtkbqznuzm.html

[Q78] 当前时间
来源：http://dali.fzhhl.top/Article/details/gttewwlpwz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamgiwsdk.html

[Q79] 字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gtnqhxhioe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqaxuqxuq.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajbcwfgc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtscuelrow.html

[Q81] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gthyqzymts.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtoldjmere.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gtgtabkdjc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtbhxcpqvr.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtveovnjdh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtivmrkusi.html

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gtcglobiuu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcumqahxo.html

[Q85] 数值取整
来源：http://dali.yvedp.cn/Article/details/gtzgwtqnjk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ehwqpu.com/Article/details/gtgdgqayxo.html

[Q86] 读取 JSON 字段
来源：http://dali.gaohongyu789.top/Article/details/gtjhfzwwax.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xylfe.cn/Article/details/gtjhcrrrdj.html

[Q87] JSON 字段做条件
来源：http://dali.guowangkeji.top/Article/details/gtmnjeyrsx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtjswyxtef.html


<!-- 参考信息 -->