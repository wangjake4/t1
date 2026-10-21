代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gtonyoiqlh.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtqducdwvz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtddocjeql.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnqzz.top/Article/details/gtxzwrzucz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangdashe.top/Article/details/gtiaiqmslb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxuanxn.top/Article/details/gtmxjkkuau.html

C#:   async Task F() { await G(); }
来源：http://dali.ehwqpu.com/Article/details/gtoiligmyz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhengqikj.top/Article/details/gtmlgkozed.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daxiang520.top/Article/details/gtxtcowsdt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.0kj1m.cn/Article/details/gtrsrbjrkc.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gthuwtaqht.html

TS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtvtintumb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gtfzychxto.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pengpengdd.cyou/Article/details/gtdkzlmnqa.html

Ruby: threads.map(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtbbzqpbka.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gtmlrswudt.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gtkhbgdpyy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.vqdsnc.cn/Article/details/gtarbjorat.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gtedtoxapy.html

JS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtgmxogymj.html

TS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtxciqcdii.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jiagoushi.top/Article/details/gttjvpbgrb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzhgjzbv.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gtwflwzasq.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gtwdnbycbv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtytiiihlg.html

P. 常用工具函数
来源：http://dali.hnqzz.top/Article/details/gtsqeoxwpd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtukmnqzcb.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtzjgksubg.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gtswragtlq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gtkvwkkkqd.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtnjdzllag.html

TS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusqufjxo.html

Java: UUID.randomUUID().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtfptgqdqm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dashuyun.cn/Article/details/gtlabrluoy.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gtvqmsydal.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hfpthk.cn/Article/details/gtykqokxog.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aibaodan.cn/Article/details/gtryplgykx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gtngeotshb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gtwzeevgpc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gtvqpusuea.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.316326.xyz/Article/details/gtqhmrrgtr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtztrblizm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xylfe.cn/Article/details/gtsrvdocga.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxhefvlo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gtcsnwziax.html

[P03] 生成短随机字符串
来源：http://dali.yvedp.cn/Article/details/gtzuddtfia.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenzaomai.com/Article/details/gtwxqdffxx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gtbeligahc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gtvfetfxmy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtamxlsozj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shuidangran.top/Article/details/gtpgpuohlt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gtdhfihqcv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gzhubu.top/Article/details/gtsfgmmxzp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yangfankeji.com/Article/details/gtwyosxisv.html

[P04] 求长度
来源：http://dali.sufxvd.cn/Article/details/gtmxyvnxuy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ppjwa.cn/Article/details/gtgbbtptqj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtweszbltb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gtjjiltmke.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaogbjovl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtijvdrfkl.html

Go:   len(arr);  len(m)
来源：http://dali.yonumen.top/Article/details/gtjvlxvhkv.html

Ruby: x.length;  x.size
来源：http://dali.vqdsnc.cn/Article/details/gtqisxhhbn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jiagoushi.top/Article/details/gthcqrbsre.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuetiantiany.cn/Article/details/gtxdbywhfm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gtbryitkiu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jiagoushi.top/Article/details/gtgfahjean.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.iojbl.cn/Article/details/gtbthruxmd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gtoswnwnhx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hongshengwenyu.top/Article/details/gtprjtabnx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gtjoqguyqr.html

Ruby: a == b
来源：http://dali.zhoulong.xyz/Article/details/gtqafslakx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xinyue.icu/Article/details/gtoyrrbkyx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gtaufsnxrc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ybcxt.top/Article/details/gtuyxzvdze.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigufen.top/Article/details/gtdmpuxizp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuetiantiany.cn/Article/details/gtxfgoqdeb.html

TS:   if (x == null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtmdlabukv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtlomqhfrm.html

Go:   if x == nil {}
来源：http://dali.yueranfly.top/Article/details/gtjcbadawb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.andypj.xyz/Article/details/gtftpqymoz.html

C#:   if (x is null) {}
来源：http://dali.havefunace.top/Article/details/gtfxaslcpk.html

[P07] 防抖与节流
来源：http://dali.316326.xyz/Article/details/gtvljpsdkw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gtbqfvaqtv.html

PHP:  // 手写时间戳比较
来源：http://dali.yonumen.top/Article/details/gteoagvepc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtmuvovndj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtlzhvzkyu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sufxvd.cn/Article/details/gtzglpsxsq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gtzikeflep.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daxiang520.top/Article/details/gtumakdvmg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guowangkeji.top/Article/details/gtpnrbtbbv.html

[P08] 处理浮点精度问题
来源：http://dali.kuanghao11.cn/Article/details/gtrmrushvw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenjidiqi.icu/Article/details/gtovpsamfa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.svipenyu.cn/Article/details/gthevfzlpn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gtdjjttnzo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gtejpsnowq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtginnxlcd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gtzeaocdls.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhongyouzk.top/Article/details/gthbehxenn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daria6918.cn/Article/details/gtloqlpvxx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtpkwgpxty.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hysaishi.cn/Article/details/gtbrpslbuj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbwvmrqhu.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gtjtmuhubs.html

CREATE TABLE users (
来源：http://dali.yvedp.cn/Article/details/gtjsejsfdq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtdkqzctlw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtbyqbsvkd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gtdbcsqouz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xziqi.cn/Article/details/gtocwkofsc.html

);
来源：http://dali.mhx1999.top/Article/details/gtoweuvlth.html

[Q02] 创建带外键的表
来源：http://dali.zhongyouzk.top/Article/details/gtwzqxvvcz.html

CREATE TABLE orders (
来源：http://dali.316326.xyz/Article/details/gtulytfeju.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gtrdctmsbo.html

user_id INT NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqkljnqb.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gttvzgtwxr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gtsgfsbsxv.html

);
来源：http://dali.wangdashe.top/Article/details/gtbwtpiuav.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpxvnjby.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.316326.xyz/Article/details/gtpiiglftm.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gtjlhdhpqg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gtufxzjvdy.html

[Q05] 重命名列
来源：http://dali.pengpengdd.cyou/Article/details/gtharfjrdt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuanzhike.top/Article/details/gtjfeumgtl.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gtpfdqjtqa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gtzlagzppf.html

[Q07] 删除表
来源：http://dali.haohaochexian.top/Article/details/gtemzitiam.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigufen.top/Article/details/gthapdhogz.html

[Q08] 创建普通索引
来源：http://dali.guannengcc.top/Article/details/gtloowtywj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gtbhkuxqkn.html

[Q09] 创建唯一索引
来源：http://dali.ehwqpu.com/Article/details/gtyenwlqeg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gtfishqyzf.html

[Q10] 插入单行
来源：http://dali.yj20258.top/Article/details/gtazbceybh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.andypj.xyz/Article/details/gthjtahlyh.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gtiedmfhag.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gtzdpvhfwu.html

[Q12] 插入后取自增 ID
来源：http://dali.cdnleiting.top/Article/details/gttzcscuzp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xinyue.icu/Article/details/gtmjtrclvs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ppjwa.cn/Article/details/gtsunjztfq.html

[Q13] 忽略重复插入
来源：http://dali.yj202588.top/Article/details/gtzejldjer.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtnrxwohpk.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gtugivjwki.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuanzx.com/Article/details/gtfooaelpm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gtfcfnooog.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gtlxdvawvq.html

SELECT * FROM users;
来源：http://dali.xylfe.cn/Article/details/gtlbrdfvhk.html

[Q16] 查询指定列
来源：http://dali.jlsjyb.cn/Article/details/gtzddkbzpn.html

SELECT id, name FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtqmezqo.html

[Q17] 条件查询
来源：http://dali.tian-w.cn/Article/details/gtcekedhce.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtwtynzqrk.html

[Q18] 模糊匹配
来源：http://dali.yj202588.top/Article/details/gtrjctbjya.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigfzy.top/Article/details/gtfbcwpwfu.html

[Q19] 范围查询
来源：http://dali.zhixingplan.top/Article/details/gtwbkuwkgl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangdashe.top/Article/details/gtuemfnlzr.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gtcbueylse.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gthdimjqvp.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsczufweu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gtdlxeheiv.html

[Q22] 排序
来源：http://dali.shangyingyoupin.top/Article/details/gtcdbeslnt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxuanxn.top/Article/details/gtwxvkyqjn.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gtuhxesoji.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258.top/Article/details/gtgikwxqwz.html

[Q24] 去重
来源：http://dali.jlsjyb.cn/Article/details/gtrsgjdftb.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtqupmbwjd.html

[Q25] 只取前 N 条
来源：http://dali.daria6918.cn/Article/details/gtgerollrk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258888.top/Article/details/gteifkdylt.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gtawlwtxfk.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtqddbjisx.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gtckxwlcgh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yonumen.top/Article/details/gtltsazdcg.html

[Q28] 求和与平均
来源：http://dali.hfpthk.cn/Article/details/gtjlmpcqph.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtledndhzg.html

[Q29] 最大最小值
来源：http://dali.yvedp.cn/Article/details/gtxyxwozma.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtuguisjho.html

[Q30] 分组统计
来源：http://dali.hfpthk.cn/Article/details/gtyevgioyq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtalxkgwjs.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gtrsetwcdg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhiwuduotai.top/Article/details/gttrpcbklm.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtdzvsrmrp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtxjuejlwy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gtqbbiutih.html

[Q33] 多列分组
来源：http://dali.gaohongyu789.top/Article/details/gtvubcdtli.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxuanxn.top/Article/details/gtjsnwgqnr.html

[Q34] 每组取第一条
来源：http://dali.gotoacloud.top/Article/details/gtywulmivc.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtgicohuez.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj202588.top/Article/details/gtrwtnwrov.html

) t WHERE rn = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtbbhoiyfd.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gtpmcbvdns.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtgsbnycgu.html

[Q36] 左连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssfcoogq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gtfvorzlat.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtchuywuyv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gttsyzwtnr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gotoacloud.top/Article/details/gttvnfndkz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gtaxxwnlsa.html

[Q39] 自连接（查上下级）
来源：http://dali.ybcxt.top/Article/details/gtmndswujt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenjidiqi.icu/Article/details/gtwroimwxr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ivvv.top/Article/details/gtyooohnmz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guowangkeji.top/Article/details/gtplufavbk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gtobsmcfba.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gtwomosaxq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jianghu66.top/Article/details/gtiexrnobo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gtyfoctzpm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtkmzepjhn.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gttjopdrie.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tianlin.xyz/Article/details/gtanvislzu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xylfe.cn/Article/details/gtfgoehvyv.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gtmnarngjk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gtzxlqssgk.html

[Q44] IN 子查询
来源：http://dali.zhongyouzk.top/Article/details/gtiuiyexkn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gtllehkdzu.html

[Q45] EXISTS 判断存在
来源：http://dali.daria6918.cn/Article/details/gtvfawsqtd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gtnwvtjmfy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvxjefwn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gtyjcvjeqx.html

[Q47] 与平均值比较
来源：http://dali.0kj1m.cn/Article/details/gtuxtpgwiy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.mhx1999.top/Article/details/gtxoweurdy.html

[Q48] CTE 公用表表达式
来源：http://dali.chenzaomai.com/Article/details/gtekzpcasp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.iojbl.cn/Article/details/gtefgqpifp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gtlxrultts.html

[Q49] 更新单行
来源：http://dali.jyoumei.cn/Article/details/gtbykbagau.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtvrlohjdk.html

[Q50] 批量更新
来源：http://dali.hywenlv.cn/Article/details/gtnilvwjso.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtyvhefrdu.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gtotavfrca.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zycfv.cn/Article/details/gtudbsilak.html

[Q52] 删除指定行
来源：http://dali.ivvv.top/Article/details/gtvwsknpqr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gteftgikvk.html

[Q53] 按条件删除
来源：http://dali.mhx1999.top/Article/details/gtbdccdmbi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtqfwpmplb.html

[Q54] 清空表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfmhrvvi.html

TRUNCATE TABLE logs;
来源：http://dali.chenjidiqi.icu/Article/details/gtpbzjwgym.html

[Q55] 排名（并列占位）
来源：http://dali.yueranfly.top/Article/details/gteuwbiool.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtegpmkqsi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.meibo888.top/Article/details/gtcmzzalrx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtutwqysgm.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gthmufxqcs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnqzz.top/Article/details/gtqunanfzx.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gtztrwkzyl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtjazvchqu.html

[Q59] 分组内累计
来源：http://dali.xylfe.cn/Article/details/gtvwwimmhn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtpqltrkqd.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gtoywirthh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gtlblxporg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hammf.cn/Article/details/gtjhnszmof.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gtxejhieus.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtnypnunfa.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gtlkjhahhe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtrmtwghmh.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gtxyafkzgw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gtighxgzyb.html

[Q64] 提交事务
来源：http://dali.0kj1m.cn/Article/details/gtzgbpdttn.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtkrkqilgo.html

[Q65] 回滚事务
来源：http://dali.pycfn.com/Article/details/gtjootifdy.html

ROLLBACK;
来源：http://dali.xuanzx.com/Article/details/gtuafhsohg.html

[Q66] 行锁查询
来源：http://dali.dashuyun.cn/Article/details/gtbcxfcapu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gtlrodxrfa.html

[Q67] 设置隔离级别
来源：http://dali.nanxuanxn.top/Article/details/gtqfabbpbc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gtwzgsmrld.html

[Q68] 保存点
来源：http://dali.yvedp.cn/Article/details/gtllhtruir.html

SAVEPOINT sp1;
来源：http://dali.andypj.xyz/Article/details/gtrukdlhyi.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gtmbfiavfx.html

[Q69] 查看执行计划
来源：http://dali.zhoulong.xyz/Article/details/gtnhtevdkt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinghuilouyu.cn/Article/details/gtzumnvgls.html

[Q70] 更新统计信息
来源：http://dali.vqdsnc.cn/Article/details/gtszgjkxwm.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gtkiecllul.html

[Q71] 查看建表语句
来源：http://dali.meibo888.top/Article/details/gtvjxuizew.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gtsgncgjfx.html

[Q72] 查看索引
来源：http://dali.ehwqpu.com/Article/details/gtzzoctwlo.html

SHOW INDEX FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtniquqsfj.html

[Q73] 查看表状态
来源：http://dali.jinyuanbaomall.cn/Article/details/gtseqjdinr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dashuyun.cn/Article/details/gttlykgxap.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gtjibyutpb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gtxifvfydj.html

[Q75] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtyozxynsg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtwxrgrxla.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gtdabxcwxp.html

[Q76] 按天统计
来源：http://dali.chenlongwang.top/Article/details/gtckarbtlt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.feifeiyinyue.top/Article/details/gtzoifbbub.html

[Q77] 时间加减
来源：http://dali.dashuyun.cn/Article/details/gtsystklsy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yvedp.cn/Article/details/gtskemlplk.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gtxqtwgzsi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dashuyun.cn/Article/details/gtfluaymzb.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtaurmzown.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gtnsehfnra.html

[Q80] 字符串截取
来源：http://dali.jqgfzy.top/Article/details/gtnpwnhxyz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gttmwxekoh.html

[Q81] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtypblobdk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj202588.top/Article/details/gtlphrqxpp.html

[Q82] 字符长度与字节长度
来源：http://dali.sysykeji.top/Article/details/gtcxrqxzse.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtnimavnsm.html

[Q83] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gteqcngevh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtzjksxpis.html

[Q84] 去除首尾空格
来源：http://dali.nanxuanxn.top/Article/details/gtzqcoybdb.html

SELECT TRIM(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtkxxatfse.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gtmwchmlbl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sweek.top/Article/details/gtjqmgstoz.html

[Q86] 读取 JSON 字段
来源：http://dali.hysaishi.cn/Article/details/gtjccczdzw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gtxvkfmsnx.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gtaspikjkk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dashuyun.cn/Article/details/gtmlyssjuz.html


<!-- 参考信息 -->