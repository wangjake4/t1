代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenlongwang.top/Article/details/gt2ssjywnkr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.0kj1m.cn/Article/details/gt2qzqpjmev.html

C#:   async Task F() { await G(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2bbgktdif.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gt2allrwbly.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuanzx.com/Article/details/gt2wrgcutje.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuxming.cn/Article/details/gt2nfbnsspg.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gt2zbfydjdt.html

TS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gt2gzlwvvxd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gt2ixyynuoa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gt2xtzorjox.html

Ruby: threads.map(&:join)
来源：http://dali.tianlin.xyz/Article/details/gt2wdfiufpq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guannengcc.top/Article/details/gt2mpiovtuj.html

[O06] 使用进程池
来源：http://dali.meibo888.top/Article/details/gt2uphcjmxa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gt2antkjjxq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gt2enzgnjpo.html

JS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gt2ibqpllwv.html

TS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gt2tyqrlfrt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gt2erwszdof.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjdntamp.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gt2marbsxmi.html

C#:   Parallel.For
来源：http://dali.xylfe.cn/Article/details/gt2udedhmwg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2gfntxgzm.html

P. 常用工具函数
来源：http://dali.nwbrower.top/Article/details/gt2ceqpzgka.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2hxisxigi.html

[P01] 生成 UUID
来源：http://dali.yj202588.top/Article/details/gt2vvcdbaxd.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgufenzy.top/Article/details/gt2vrboqsag.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.andypj.xyz/Article/details/gt2cijxupvr.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2djafyplo.html

TS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gt2royespsg.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ceeyorfw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gt2zmwsbkcs.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gt2nmwuchqe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gt2wlzntjut.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gt2sgswkqzj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ivvv.top/Article/details/gt2nlpoqndc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gt2nlpvykcj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2rlqzzfpv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aghymzos.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2jsteuvng.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fusbixiv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzihivfg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gt2bokkrehb.html

[P03] 生成短随机字符串
来源：http://dali.aibaodan.cn/Article/details/gt2qeelbffk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkhtssqi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gt2atqbkiiu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2nbeugizn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gt2nmojvfjb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gzhubu.top/Article/details/gt2bwhgecqm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daria6918.cn/Article/details/gt2remmqtcu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ehwqpu.com/Article/details/gt2fvsywrdg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gt2nuurtsmo.html

[P04] 求长度
来源：http://dali.chenlongwang.top/Article/details/gt2ngldxcyv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fylacggl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2vpzbhehx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gt2nmnspknr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gt2plhitpls.html

Java: list.size();  map.size();  s.length()
来源：http://dali.iojbl.cn/Article/details/gt2jlryjfhx.html

Go:   len(arr);  len(m)
来源：http://dali.shuidangran.top/Article/details/gt2aaxjpmzb.html

Ruby: x.length;  x.size
来源：http://dali.tian-w.cn/Article/details/gt2jqvizrcp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijurbeci.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gt2jiopqciv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylolgmmg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sufxvd.cn/Article/details/gt2ossepsqe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guowangkeji.top/Article/details/gt2zwwiiyjr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gt2zmkzotfy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cqqwz.cn/Article/details/gt2nqqgiivn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sufxvd.cn/Article/details/gt2msdytcye.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gt2tmsqlpup.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sxryk.cn/Article/details/gt2yivjeapd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuxming.cn/Article/details/gt2blpivmsq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gt2zgwyqbcr.html

PHP:  if (empty($x)) {}
来源：http://dali.pycfn.com/Article/details/gt2naayakrd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gt2yjaosuoz.html

TS:   if (x == null) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2dujkrhnj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gt2cjojflkq.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gt2wzozvzmr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dianchejie.cn/Article/details/gt2yqiqpupc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epkkzgnk.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gt2bpwpyykv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnqzz.top/Article/details/gt2cboqhxkz.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gt2etruimdb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gsiguftf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2mllbjhyf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2nqocqcsq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgcdppte.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigufen.top/Article/details/gt2dvagecte.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gt2usuyclud.html

[P08] 处理浮点精度问题
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnsxjmll.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gt2hxipsxwj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jaimbgit.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yonumen.top/Article/details/gt2ydumcfcu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gt2hgttaqjx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gt2jlclsaex.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gt2cdezujqu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangdashe.top/Article/details/gt2jbnmjieq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2irapqmvl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2tugkttyt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gt2vjxidnov.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2botldvcm.html

[Q01] 创建表
来源：http://dali.yongpay.top/Article/details/gt2jiesrxmo.html

CREATE TABLE users (
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhkgvdpg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gt2prxpkwtj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gt2mffpgoiz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hysaishi.cn/Article/details/gt2rcdycfzp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gt2lfqihlzi.html

);
来源：http://dali.nwbrower.top/Article/details/gt2kygliwql.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gt2qwjjwsfa.html

CREATE TABLE orders (
来源：http://dali.tianlin.xyz/Article/details/gt2lgveljap.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gt2vldxgyke.html

user_id INT NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gt2rvpetnyt.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gt2faoxpsrq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fengsongda.top/Article/details/gt2ddultfkv.html

);
来源：http://dali.guowangkeji.top/Article/details/gt2oshagkoy.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gt2qydqsihr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gt2imgcxpqi.html

[Q04] 修改列类型
来源：http://dali.haohaochexian.top/Article/details/gt2kgjizpmd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2anuwmoly.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gt2xlylntot.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yvedp.cn/Article/details/gt2lhsfxswp.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gt2htgtyvur.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxinkj.top/Article/details/gt2llcpgnfb.html

[Q07] 删除表
来源：http://dali.xinyue.icu/Article/details/gt2vywylzar.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xylfe.cn/Article/details/gt2iagxqwjz.html

[Q08] 创建普通索引
来源：http://dali.zhengqikj.top/Article/details/gt2uwomsdjp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gt2idmidzlk.html

[Q09] 创建唯一索引
来源：http://dali.cheryme.top/Article/details/gt2oosiaent.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gt2qctpddxd.html

[Q10] 插入单行
来源：http://dali.jqgufenzy.top/Article/details/gt2qiorsyzl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gt2qivbiwrr.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gt2zmjfrdra.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shuidangran.top/Article/details/gt2kwrexenr.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gt2oxnaiptc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.0kj1m.cn/Article/details/gt2ozmyaxna.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenzaomai.com/Article/details/gt2qzemxuqt.html

[Q13] 忽略重复插入
来源：http://dali.fengsongda.top/Article/details/gt2dvkezyah.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gt2kqotktwb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zdqjudy.top/Article/details/gt2plmwnapj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gt2lfjorctn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tian-w.cn/Article/details/gt2arhuvmhz.html

[Q15] 查询全部
来源：http://dali.zycfv.cn/Article/details/gt2zwljyhld.html

SELECT * FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2avwlrllh.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gt2ouopsnnr.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2tohopajq.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gt2ytjiwtuc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuanzx.com/Article/details/gt2tmchypef.html

[Q18] 模糊匹配
来源：http://dali.svipenyu.cn/Article/details/gt2hbvagwdt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gt2ufqziluo.html

[Q19] 范围查询
来源：http://dali.andypj.xyz/Article/details/gt2unfuamwr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gt2zrztovpo.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gt2zfvmqxfv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guannengcc.top/Article/details/gt2lrnmuskc.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gt2vzbwlwqj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gt2wkbvdooj.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gt2lgfpvqbb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gt2rdgjwhnj.html

[Q23] 分页
来源：http://dali.yonumen.top/Article/details/gt2fbufyekn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgufenzy.top/Article/details/gt2byddgnii.html

[Q24] 去重
来源：http://dali.smart0.xyz/Article/details/gt2thbizkow.html

SELECT DISTINCT city FROM users;
来源：http://dali.yongpay.top/Article/details/gt2gdmapylx.html

[Q25] 只取前 N 条
来源：http://dali.havefunace.top/Article/details/gt2rcvxtcog.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gt2aykonrim.html

[Q26] 计数
来源：http://dali.yj20258.top/Article/details/gt2enqhvskg.html

SELECT COUNT(*) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2qmshjanh.html

[Q27] 条件计数
来源：http://dali.zycfv.cn/Article/details/gt2zcvdynft.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2uphnspet.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gt2euhdqrnu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2ndhlkkum.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gt2czcwurhs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2odhvxjev.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gt2iyntqeqj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gt2fqvaewno.html

[Q31] 分组后过滤
来源：http://dali.ehwqpu.com/Article/details/gt2yolfkfhm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258888.top/Article/details/gt2uaabtpvv.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gt2ysefaykq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2sjxtjimf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dianchejie.cn/Article/details/gt2xpjcphjp.html

[Q33] 多列分组
来源：http://dali.zhongyouzk.top/Article/details/gt2zujmepxp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbpjomzr.html

[Q34] 每组取第一条
来源：http://dali.daxiang520.top/Article/details/gt2vllmfhqd.html

SELECT * FROM (
来源：http://dali.jinqigufen.top/Article/details/gt2ivqlifvh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gt2eqhskupe.html

) t WHERE rn = 1;
来源：http://dali.shuidangran.top/Article/details/gt2cdnepxvu.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gt2qcmcrkxm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gt2pebdznxz.html

[Q36] 左连接
来源：http://dali.cheryme.top/Article/details/gt2ldpsmguk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gt2ciwjlgtx.html

[Q37] 右连接
来源：http://dali.sxryk.cn/Article/details/gt2ufdepfnw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gt2jiiapadr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gt2qvlxttlm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gt2vbnenpvr.html

[Q39] 自连接（查上下级）
来源：http://dali.iojbl.cn/Article/details/gt2rslxuqly.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aizwys.cn/Article/details/gt2kilgovjd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gt2fzxncsvr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gt2ttlmexko.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gt2wyzrsjfc.html

[Q41] 多表连接
来源：http://dali.dianchejie.cn/Article/details/gt2yflbipvx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gt2rzrxoogn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gt2mzxoxyya.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnfqrbvn.html

[Q42] 连接条件附加过滤
来源：http://dali.yonumen.top/Article/details/gt2grtmvpgg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gt2xkdtvnsn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guannengcc.top/Article/details/gt2xtlunpcv.html

[Q43] 标量子查询
来源：http://dali.cdnleiting.top/Article/details/gt2dsoxztpe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pfyxwtxq.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gt2mikcffsp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tian-w.cn/Article/details/gt2diqjdcay.html

[Q45] EXISTS 判断存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mttlaqbk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gt2ojgxpxdt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gotoacloud.top/Article/details/gt2jegeolss.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gt2lccypzhr.html

[Q47] 与平均值比较
来源：http://dali.xinyue.icu/Article/details/gt2uoodrjov.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhixingplan.top/Article/details/gt2myksetgt.html

[Q48] CTE 公用表表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmwqdmaj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.bjfxy.top/Article/details/gt2zdkekatk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hywenlv.cn/Article/details/gt2hkjfcaip.html

[Q49] 更新单行
来源：http://dali.wangshuangyany.cn/Article/details/gt2cktktffs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oksdhsuu.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gt2ixvuoflp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gt2yprsuigv.html

[Q51] 用子查询更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2avrbfehy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2zsliyyff.html

[Q52] 删除指定行
来源：http://dali.cqqwz.cn/Article/details/gt2jbuwreuv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gt2tulmthho.html

[Q53] 按条件删除
来源：http://dali.wangdashe.top/Article/details/gt2ttuqpsbh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gt2jwwcrmny.html

[Q54] 清空表
来源：http://dali.jqgufenzy.top/Article/details/gt2qanyucjf.html

TRUNCATE TABLE logs;
来源：http://dali.iojbl.cn/Article/details/gt2ibktdlyc.html

[Q55] 排名（并列占位）
来源：http://dali.yj202588.top/Article/details/gt2sabfmrhj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gt2vkaalthj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ppjwa.cn/Article/details/gt2oeqbnscz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksaansui.html

[Q57] 行号
来源：http://dali.dianchejie.cn/Article/details/gt2ubdvniav.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2bsfzgwgw.html

[Q58] 累计求和
来源：http://dali.zycfv.cn/Article/details/gt2miwwypzn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2lezlnxyy.html

[Q59] 分组内累计
来源：http://dali.fzhhl.top/Article/details/gt2gnepcxse.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2soosspxt.html

[Q60] 取上一行 / 下一行
来源：http://dali.fzhhl.top/Article/details/gt2ltfskoqh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gt2pbfhgxov.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2hokjctcv.html

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gt2mcjkimpa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2wewhdnru.html

[Q62] 分组占比
来源：http://dali.xinyue.icu/Article/details/gt2cecupwch.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gt2shbcdljg.html

[Q63] 开启事务
来源：http://dali.gaohongyu789.top/Article/details/gt2vygiwnoh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlubgclu.html

[Q64] 提交事务
来源：http://dali.jinqigufen.top/Article/details/gt2ktrbhrup.html

COMMIT;
来源：http://dali.cheryme.top/Article/details/gt2yczftkmi.html

[Q65] 回滚事务
来源：http://dali.pycfn.com/Article/details/gt2ciyxbkaj.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gt2fakfmbcv.html

[Q66] 行锁查询
来源：http://dali.zdqjudy.top/Article/details/gt2esolcsfy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.feifeiyinyue.top/Article/details/gt2twcrdyof.html

[Q67] 设置隔离级别
来源：http://dali.gaohongyu789.top/Article/details/gt2nxvcpczz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gt2bjinhxjd.html

[Q68] 保存点
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnkddaiy.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gt2ayxzklxh.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gt2jmbihkhl.html

[Q69] 查看执行计划
来源：http://dali.shuidangran.top/Article/details/gt2rktbapld.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gt2cuzrzasz.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gt2ouivnfhq.html

ANALYZE TABLE users;
来源：http://dali.nanxuanxn.top/Article/details/gt2evwilwaw.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sovmvbpy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.birdmap.top/Article/details/gt2auqejwst.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gt2rduhskrz.html

SHOW INDEX FROM users;
来源：http://dali.cashguo.top/Article/details/gt2jlfggqnh.html

[Q73] 查看表状态
来源：http://dali.ppjwa.cn/Article/details/gt2pnzsudbq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvztmazj.html

[Q74] 强制使用索引
来源：http://dali.jyoumei.cn/Article/details/gt2dzpyfhfm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tanke756.top/Article/details/gt2agamtrad.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgctidzo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2ivpghxbc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gt2rpbpaimu.html

[Q76] 按天统计
来源：http://dali.sxryk.cn/Article/details/gt2baraztnq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gt2moieghsu.html

[Q77] 时间加减
来源：http://dali.chenlongwang.top/Article/details/gt2mibufecc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gt2dlhhuttg.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihrrnwkr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ydzc1.top/Article/details/gt2vnakrfit.html

[Q79] 字符串拼接
来源：http://dali.yonumen.top/Article/details/gt2ypjhhebr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gt2maphzjev.html

[Q80] 字符串截取
来源：http://dali.xziqi.cn/Article/details/gt2iibuxqdr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2ombeetev.html

[Q81] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gt2gwfpjmwe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gt2mrzmcgfn.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvcribwp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2ydrqokft.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gt2krhtadyg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2qjovtsof.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjacoaos.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukbiwavk.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhvspvkj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gt2nfrokxhp.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gt2kxujubrl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gt2twhjhpks.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gt2oxulpdlk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhixingplan.top/Article/details/gt2ayseudqs.html

[Q88] 行转列（条件聚合）
来源：http://dali.mhx1999.top/Article/details/gt2sbltnyuf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gt2anbczwsg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2evxbwqim.html

[Q89] 判断表是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emzvxgua.html


<!-- 参考信息 -->