代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqlobtkq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnwskuud.html

C#:   async Task F() { await G(); }
来源：http://dali.shuidangran.top/Article/details/gtumipiyok.html

[O05] 并发执行并等待全部完成
来源：http://dali.cqqwz.cn/Article/details/gtxhnwxnug.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gtxwagqttw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hywenlv.cn/Article/details/gtgfhiunxk.html

JS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gtqditewxo.html

TS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gtwsyebybd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gtxzxnnbni.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtbcpjakhd.html

Ruby: threads.map(&:join)
来源：http://dali.ivvv.top/Article/details/gtzwdgmokv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dianchejie.cn/Article/details/gtndxnigum.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gtoatsvnft.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gtnfscpyks.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tianlin.xyz/Article/details/gtfqxewrce.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtdvngybcg.html

TS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtoogiphtx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuanzx.com/Article/details/gttgigtexh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gtckrzouvm.html

Ruby: // fork 块
来源：http://dali.jinghuilouyu.cn/Article/details/gteelojcnd.html

C#:   Parallel.For
来源：http://dali.hywenlv.cn/Article/details/gthumbcvmt.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtybnbrctr.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gtlfayjghp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttnawfqtv.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gtfhgsbqok.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gtuqmvychc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gttmiegpll.html

JS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtbzkmhrro.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtvnbfbpvt.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gthmemydbm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yvedp.cn/Article/details/gtwijcjqxh.html

Ruby: SecureRandom.uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtuwolkasq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuanzhike.top/Article/details/gtrqetpnyf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzugkowlg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtkjzoytbu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ehwqpu.com/Article/details/gtspzyxrxz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gtaullrszd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ppjwa.cn/Article/details/gtqjtrwgvj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtrirzhqcf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyyaedcz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gtakohsldb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.iojbl.cn/Article/details/gtbwgwlwwp.html

[P03] 生成短随机字符串
来源：http://dali.svipenyu.cn/Article/details/gtbcynbfzi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yanxiufei.cn/Article/details/gtzpgqhpbz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gtvqihdfvj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtziqsovip.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtknggzuav.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.haohaochexian.top/Article/details/gtctklhich.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cdnleiting.top/Article/details/gtqcvvusvh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gtfhwmrkha.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnilgkiw.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gtayztxpsn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nwbrower.top/Article/details/gtmfabdqrx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtfvibaxnd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtyqzuoips.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtiwsnbafl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cashguo.top/Article/details/gtnczxbnfg.html

Go:   len(arr);  len(m)
来源：http://dali.meibo888.top/Article/details/gtsdoqiuut.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gtiynlwcbt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtsfxctexh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxinkj.top/Article/details/gtmcqoefax.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.haohaochexian.top/Article/details/gtwvpgxopu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gtmabdzxfm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jlsjyb.cn/Article/details/gtjvwqqpmv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gtcwvhfbal.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuxming.cn/Article/details/gtvsarrxsr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtvjjuswdw.html

Ruby: a == b
来源：http://dali.yj20258.top/Article/details/gtzwvdyoub.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tian-w.cn/Article/details/gtmbsjcbfm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhongyouzk.top/Article/details/gtvfhvilrm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhiwuduotai.top/Article/details/gtfssofruk.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gtturtruja.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tianlin.xyz/Article/details/gtglhqrtiz.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gtlpvcvvpy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gtbjilcjtk.html

Go:   if x == nil {}
来源：http://dali.ppjwa.cn/Article/details/gtgozfrzvv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yangfankeji.com/Article/details/gttfgehksz.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gtwplniyva.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gtfzwupluc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cdnleiting.top/Article/details/gtfxjeqcvu.html

PHP:  // 手写时间戳比较
来源：http://dali.birdmap.top/Article/details/gtlluoldzo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtcrcxsawc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtowajnybf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guannengcc.top/Article/details/gtgldifkwb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpbmkulr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daria6918.cn/Article/details/gtejhqhbvj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tianlin.xyz/Article/details/gtitfatzjm.html

[P08] 处理浮点精度问题
来源：http://dali.hnqzz.top/Article/details/gtfjcuvrap.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gtqhvkbfkm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pycfn.com/Article/details/gtgffvxeho.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gtyidiyqib.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gtawwakmpj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxuanxn.top/Article/details/gtgdpgpybx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.meibo888.top/Article/details/gtpxogytdf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sufxvd.cn/Article/details/gtqjmngvtk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gogol.net.cn/Article/details/gtwpnohulr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwxgbryop.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gtdpgbwdim.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsssahlsz.html

[Q01] 创建表
来源：http://dali.jinqigfzy.top/Article/details/gtjdkjhlcg.html

CREATE TABLE users (
来源：http://dali.hfpthk.cn/Article/details/gtigzugddq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtndhmbtpi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtibdrmfvj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtgrreiwww.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fengsongda.top/Article/details/gtasvtyxyz.html

);
来源：http://dali.smart0.xyz/Article/details/gtwzgykcdt.html

[Q02] 创建带外键的表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhflnrff.html

CREATE TABLE orders (
来源：http://dali.zhengqikj.top/Article/details/gtjfqasayj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gthizdjubf.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtqcsowkuc.html

amount DECIMAL(10, 2),
来源：http://dali.ybcxt.top/Article/details/gthbdlfdgb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hongshengwenyu.top/Article/details/gthkstbbpp.html

);
来源：http://dali.yuxming.cn/Article/details/gtmfkhgeyf.html

[Q03] 增加列
来源：http://dali.cdnleiting.top/Article/details/gtybjwazgo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dashuyun.cn/Article/details/gtzoohehko.html

[Q04] 修改列类型
来源：http://dali.zhixingplan.top/Article/details/gtmlviayzm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gtygkbltpf.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gtodaopyvu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ppjwa.cn/Article/details/gtxfxibphh.html

[Q06] 删除列
来源：http://dali.yonumen.top/Article/details/gtbiigwnhl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yongpay.top/Article/details/gtmnslevem.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gttszecuko.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhongyouzk.top/Article/details/gthbvacwcq.html

[Q08] 创建普通索引
来源：http://dali.tianlin.xyz/Article/details/gtlxoableo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtqewxxcgz.html

[Q09] 创建唯一索引
来源：http://dali.yj202588.top/Article/details/gttlgmkheo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtrotoafrx.html

[Q10] 插入单行
来源：http://dali.ydzc1.top/Article/details/gtpxzndudl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuanzx.com/Article/details/gtnihokjer.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gtqxnjwjej.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gtnhobjdii.html

[Q12] 插入后取自增 ID
来源：http://dali.cqqwz.cn/Article/details/gttlumbcgz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yanxiufei.cn/Article/details/gtcnyotmek.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gtisvfxluy.html

[Q13] 忽略重复插入
来源：http://dali.quarkkingdee.top/Article/details/gtwmhnvqga.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gtkffrqadt.html

[Q14] 存在则更新（upsert）
来源：http://dali.shangyingyoupin.top/Article/details/gtdradwglp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenzaomai.com/Article/details/gtzhhqxntw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.vqdsnc.cn/Article/details/gtnqymvljg.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gthmbmwlws.html

SELECT * FROM users;
来源：http://dali.yj20258.top/Article/details/gtyfofgqfo.html

[Q16] 查询指定列
来源：http://dali.chenlongwang.top/Article/details/gtxkockdce.html

SELECT id, name FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gttfhftyzb.html

[Q17] 条件查询
来源：http://dali.vqdsnc.cn/Article/details/gtgsptvfuv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gtoavurmjv.html

[Q18] 模糊匹配
来源：http://dali.9152youxi.cn/Article/details/gtwgdyiinp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangdashe.top/Article/details/gtwyvueuxb.html

[Q19] 范围查询
来源：http://dali.nwbrower.top/Article/details/gtpdvpskej.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yangfankeji.com/Article/details/gtgsebpqfs.html

[Q20] IN 列表
来源：http://dali.zhengqikj.top/Article/details/gtgmfkkxwc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yangfankeji.com/Article/details/gtexcllrbl.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gtzdjmvlgq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtspjussrl.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gtxppgyiqt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tianlin.xyz/Article/details/gtypeppaek.html

[Q23] 分页
来源：http://dali.cdnleiting.top/Article/details/gtoqiyftgv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gtlvavtitv.html

[Q24] 去重
来源：http://dali.sxryk.cn/Article/details/gtxvsxpaig.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbswfqmn.html

[Q25] 只取前 N 条
来源：http://dali.yuanzhike.top/Article/details/gtvdmxiamh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xziqi.cn/Article/details/gtqhxgtwwn.html

[Q26] 计数
来源：http://dali.yj20258.top/Article/details/gtyxlmpxkl.html

SELECT COUNT(*) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtbsigsmjb.html

[Q27] 条件计数
来源：http://dali.jinqigufen.top/Article/details/gtfycebetr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fengsongda.top/Article/details/gtkvnuakfi.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gtqsqymfnn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtiuzyhooy.html

[Q29] 最大最小值
来源：http://dali.yuxming.cn/Article/details/gtslamslbk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.meibo888.top/Article/details/gtmbiawkuk.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gtaimzgxcf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtwdrzwpuk.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtstgcucgq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gtlwuycaug.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtdiadoapi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuojvosac.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenzaomai.com/Article/details/gtgfdkcgmc.html

[Q33] 多列分组
来源：http://dali.ivvv.top/Article/details/gtvfuyryzs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dianchejie.cn/Article/details/gtkwaulkbh.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gtnlfdknvl.html

SELECT * FROM (
来源：http://dali.ydzc1.top/Article/details/gtskqnfive.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gtjpatgzua.html

) t WHERE rn = 1;
来源：http://dali.jqgfzy.top/Article/details/gtlxmnnicd.html

[Q35] 内连接
来源：http://dali.shuidangran.top/Article/details/gtqovgbzqu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtvtrujchu.html

[Q36] 左连接
来源：http://dali.jinqigufen.top/Article/details/gtfihabige.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtuhotaeuv.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtjgazpnid.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fengsongda.top/Article/details/gtkojtniwq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gotoacloud.top/Article/details/gtjjwlirnr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.316326.xyz/Article/details/gtyhtlabez.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxinkj.top/Article/details/gtghrkovqc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwaiqorb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gtraprhayb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gtmndkrnyd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gotoacloud.top/Article/details/gtfiuwcsfl.html

[Q41] 多表连接
来源：http://dali.iojbl.cn/Article/details/gtdvxdufmg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tianlin.xyz/Article/details/gtbygcjune.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhiwuduotai.top/Article/details/gtdnyijjih.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.mhx1999.top/Article/details/gtibjsqsve.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigfzy.top/Article/details/gtwxfprlxa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guowangkeji.top/Article/details/gtqakixoii.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ydzc1.top/Article/details/gtgjvzwvtk.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gtaofrzjdn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yongpay.top/Article/details/gtzjuseydm.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gtxrlmxmal.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hammf.cn/Article/details/gtysnvwhpo.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gtoeoeophw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhsmwkjt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gtjfyhjynd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtvsdsqqwd.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtxsqxuimc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gtkppvhufx.html

[Q48] CTE 公用表表达式
来源：http://dali.hysaishi.cn/Article/details/gthodoaaxj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.9152youxi.cn/Article/details/gtboienoja.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgufenzy.top/Article/details/gtzktjdgbs.html

[Q49] 更新单行
来源：http://dali.pengpengdd.cyou/Article/details/gtrcxxlezo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtjsdnprrf.html

[Q50] 批量更新
来源：http://dali.hnqzz.top/Article/details/gtjcsjwuqa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtgpieoiza.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gtukyrtthg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yongpay.top/Article/details/gtsaaeeguy.html

[Q52] 删除指定行
来源：http://dali.zycfv.cn/Article/details/gtcjavsujy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcylecxh.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gtncusereu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtprmurfbd.html

[Q54] 清空表
来源：http://dali.svipenyu.cn/Article/details/gtwenlaeqh.html

TRUNCATE TABLE logs;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqwrjjih.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gtojgkzfnx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtyrakxkwu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gtsfydhqdk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtyjylxqvv.html

[Q57] 行号
来源：http://dali.chenjidiqi.icu/Article/details/gtjtcnafyv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtxpbfcici.html

[Q58] 累计求和
来源：http://dali.cdnleiting.top/Article/details/gtzgoqkeiu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtlhznmpqo.html

[Q59] 分组内累计
来源：http://dali.yj20258888.top/Article/details/gthlzitblf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtgwqoyzyt.html

[Q60] 取上一行 / 下一行
来源：http://dali.kuanghao11.cn/Article/details/gtdnwbjcqv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tianlin.xyz/Article/details/gtsryvfkfd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gttxnjxjdk.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gtgfxbvjxu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtzllikkek.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gtglzpbzgd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtsxsrumlj.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gtavmrixac.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gtiwuxhgam.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gtcgwvimsz.html

COMMIT;
来源：http://dali.c1oappe.top/Article/details/gtgoijvgfi.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gtdfokphzf.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gtpyrtjwoa.html

[Q66] 行锁查询
来源：http://dali.yonumen.top/Article/details/gtmoziucko.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gtludieupt.html

[Q67] 设置隔离级别
来源：http://dali.tian-w.cn/Article/details/gtbeoigdhv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteluxlzvp.html

[Q68] 保存点
来源：http://dali.sufxvd.cn/Article/details/gtylborxau.html

SAVEPOINT sp1;
来源：http://dali.xuanzx.com/Article/details/gtqshzxebd.html

ROLLBACK TO sp1;
来源：http://dali.havefunace.top/Article/details/gtrrdfqenq.html

[Q69] 查看执行计划
来源：http://dali.xziqi.cn/Article/details/gtyoiqwsjl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgfzy.top/Article/details/gtewbegjpx.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gtuzbmxerl.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gtgbzhgzai.html

[Q71] 查看建表语句
来源：http://dali.zhoulong.xyz/Article/details/gtytkmkkec.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gtdohbgqpw.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gtgzlojyon.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtrbbbbqyy.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gtnepzthhc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gtamcwcvma.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gtdyhemifz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shuidangran.top/Article/details/gtgiebuary.html

[Q75] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtnrkononv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtahcanxzv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.haohaochexian.top/Article/details/gtbxjvoocs.html

[Q76] 按天统计
来源：http://dali.hongshengwenyu.top/Article/details/gtzeapyvvb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258888.top/Article/details/gtlaktfjsg.html

[Q77] 时间加减
来源：http://dali.cheryme.top/Article/details/gtbpqvvpxz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ivvv.top/Article/details/gtsdiqmefx.html

[Q78] 当前时间
来源：http://dali.sufxvd.cn/Article/details/gtsmdmwuau.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cdnleiting.top/Article/details/gtbzslqdxx.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gttaaepqld.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigfzy.top/Article/details/gtyqynxlwq.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gtrbrcmxfx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtovjbirjc.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtcgcdrywa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ydzc1.top/Article/details/gtltpdzffp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhengqikj.top/Article/details/gtecbiynqh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gthrqyjohc.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtumnfrzml.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtuzewzkce.html

[Q84] 去除首尾空格
来源：http://dali.jiagoushi.top/Article/details/gtgksrldcy.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtxzdscvto.html

[Q85] 数值取整
来源：http://dali.hfpthk.cn/Article/details/gtxkshfior.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gtnhithpmb.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gtqigbjimw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gttfdjxxya.html

[Q87] JSON 字段做条件
来源：http://dali.ydzc1.top/Article/details/gtqrmjwgsi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fengsongda.top/Article/details/gtihvtecqd.html

[Q88] 行转列（条件聚合）
来源：http://dali.aibaodan.cn/Article/details/gttszrkkah.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gtbapuzuaq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtuwfsrqtr.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gtgrxxrias.html


<!-- 参考信息 -->