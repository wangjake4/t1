代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gtzcybnkxg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sufxvd.cn/Article/details/gtxflqoqwv.html

C#:   async Task F() { await G(); }
来源：http://dali.shzxlz.cn/Article/details/gtlfxlrpxe.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gthewfmlzg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gtvqfdboew.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazwdbsep.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtchlldrje.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaeolvxik.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gtxwgmtcrt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnaiwzpa.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gtqgnmjwjd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gtcbdjgeoi.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gtqeldtsdz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jiagoushi.top/Article/details/gtwrkkybcv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhiwuduotai.top/Article/details/gtaczxatje.html

JS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtphgptwbw.html

TS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtrocfxeoh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cashguo.top/Article/details/gtcvmjlsbg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gtfbqxksyb.html

Ruby: // fork 块
来源：http://dali.svipenyu.cn/Article/details/gtalksavnz.html

C#:   Parallel.For
来源：http://dali.hnqzz.top/Article/details/gtsgliqigt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtcefcxomb.html

P. 常用工具函数
来源：http://dali.vqdsnc.cn/Article/details/gtmuppgwan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtgqisitzl.html

[P01] 生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtbvwvlaeo.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gtwnngzhct.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtkjbmszcm.html

JS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtndhtexpg.html

TS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtgvdttrzu.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gtlhzeejuu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gtprjwfmzb.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gtncamoarm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yueranfly.top/Article/details/gtgthnqjgc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pycfn.com/Article/details/gteawsbrci.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gtqihohuxx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jiagoushi.top/Article/details/gtnrvxikok.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cashguo.top/Article/details/gtqkrabfvr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sysykeji.top/Article/details/gtancnztjp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtfwnygxpv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gtxhnjqfsg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jyoumei.cn/Article/details/gtxhjbfkuz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yangfankeji.com/Article/details/gtjjxpvvhy.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtwiifpfox.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkeovoyqz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gtcdwhrywn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gtdddptchl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtjfvqamxv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aizwys.cn/Article/details/gtmnffoyep.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.haohaochexian.top/Article/details/gtjvrfisnk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yangfankeji.com/Article/details/gttqwwedll.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmjqpxan.html

[P04] 求长度
来源：http://dali.daria6918.cn/Article/details/gtqazpnova.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gtnwwlvoop.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtzpoylqxg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtdpknkaas.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gtbxvsnbbm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmyaidew.html

Go:   len(arr);  len(m)
来源：http://dali.birdmap.top/Article/details/gthamujogd.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gteabotwre.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gttsrfbcxo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cheryme.top/Article/details/gttjxhwffx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gtedxdbggr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guowangkeji.top/Article/details/gtgqcjorco.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gtdugjdnsm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtqgqtisfv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gtesyqncbn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.316326.xyz/Article/details/gtdfyjccab.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gtezxumyqa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gtolsjlkjg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.svipenyu.cn/Article/details/gtcewuhuxv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pycfn.com/Article/details/gtjadqpzhk.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtocbmaoxg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gtivsyxhkl.html

TS:   if (x == null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufqtnxck.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhcmorjo.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtgdtkxvmk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gtrbgutikr.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gtkvhwmbtj.html

[P07] 防抖与节流
来源：http://dali.hongshengwenyu.top/Article/details/gtrgtcgdin.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.mhx1999.top/Article/details/gtkajrqskh.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gtozqsviwa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtvklgewdh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gtkwefjkvt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gttdsivpku.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gtkyyjqcvw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgufenzy.top/Article/details/gtmdacguaz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzvwkisl.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gtctfzihto.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gtrvohsvjj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shzxlz.cn/Article/details/gtjjfmclxi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyvgsojj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gtfghsvocw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sufxvd.cn/Article/details/gtbcoczqmf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.havefunace.top/Article/details/gtrtepqnyn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gtxbewrpqp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gtagvqwzzl.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbsplcwah.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gtqmkgechl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtbobqwqza.html

[Q01] 创建表
来源：http://dali.ppjwa.cn/Article/details/gtyitxwpmp.html

CREATE TABLE users (
来源：http://dali.cqqwz.cn/Article/details/gtmfjtqmav.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gtrpzrdzwp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pycfn.com/Article/details/gtdovwkgeq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ppjwa.cn/Article/details/gtitrxzcgp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gttwxwjtbf.html

);
来源：http://dali.aizwys.cn/Article/details/gtbruicsfp.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gtpefotlyf.html

CREATE TABLE orders (
来源：http://dali.aizwys.cn/Article/details/gtfbxnzbbv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtadigvhib.html

user_id INT NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtticbgjlw.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gtrvvioxuj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gtuwebaagr.html

);
来源：http://dali.yj20258888.top/Article/details/gttbvthqdp.html

[Q03] 增加列
来源：http://dali.c1oappe.top/Article/details/gtfcvfmgak.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daxiang520.top/Article/details/gtasqjaubt.html

[Q04] 修改列类型
来源：http://dali.jqgufenzy.top/Article/details/gtiakfnbum.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shzxlz.cn/Article/details/gtdcbkutan.html

[Q05] 重命名列
来源：http://dali.dashuyun.cn/Article/details/gtzntsowys.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gtxidqngtt.html

[Q06] 删除列
来源：http://dali.feifeiyinyue.top/Article/details/gtlqrlsnvu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sxryk.cn/Article/details/gtkyntcbae.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gtexphkyne.html

DROP TABLE IF EXISTS orders;
来源：http://dali.bjfxy.top/Article/details/gtbehbtfwf.html

[Q08] 创建普通索引
来源：http://dali.316326.xyz/Article/details/gtknfwgyvr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtducufobn.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gtbgpqrzto.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtykohzeew.html

[Q10] 插入单行
来源：http://dali.yanxiufei.cn/Article/details/gtnayjrxmk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gtmmewbwek.html

[Q11] 一次插入多行
来源：http://dali.nwbrower.top/Article/details/gtypkuiokz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gtwwvqotmh.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gthisdgfoq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hywenlv.cn/Article/details/gtffvwmjez.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenzaomai.com/Article/details/gtbipctvtp.html

[Q13] 忽略重复插入
来源：http://dali.guannengcc.top/Article/details/gtgkwuyhiq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.havefunace.top/Article/details/gtfzqodqoq.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjnowhjm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pycfn.com/Article/details/gtopzvuauh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gtkxrluxon.html

[Q15] 查询全部
来源：http://dali.fengsongda.top/Article/details/gtmwjygqib.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gtwchcaxuf.html

[Q16] 查询指定列
来源：http://dali.havefunace.top/Article/details/gtwugccght.html

SELECT id, name FROM users;
来源：http://dali.tanke756.top/Article/details/gttydxizkv.html

[Q17] 条件查询
来源：http://dali.smart0.xyz/Article/details/gtsrdfyzen.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gtgkvyvtjv.html

[Q18] 模糊匹配
来源：http://dali.fzhhl.top/Article/details/gtmmpmftqu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cucudq.cn/Article/details/gtaclaubyw.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gtlicnvvpx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yongpay.top/Article/details/gttzryjndh.html

[Q20] IN 列表
来源：http://dali.9152youxi.cn/Article/details/gtdjxxrwtw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gtluytoudx.html

[Q21] 空值判断
来源：http://dali.pengpengdd.cyou/Article/details/gtmdfxvrep.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzappnsj.html

[Q22] 排序
来源：http://dali.redwolf501.top/Article/details/gtbamasrax.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gtvlpczfim.html

[Q23] 分页
来源：http://dali.yonumen.top/Article/details/gtmsymvswq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.feifeiyinyue.top/Article/details/gththtxklf.html

[Q24] 去重
来源：http://dali.chenlongwang.top/Article/details/gthluspbxl.html

SELECT DISTINCT city FROM users;
来源：http://dali.sweek.top/Article/details/gtulxjrwqq.html

[Q25] 只取前 N 条
来源：http://dali.zhixingplan.top/Article/details/gtefxjgdao.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigufen.top/Article/details/gtcnohlezj.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gtdqenybiy.html

SELECT COUNT(*) FROM users;
来源：http://dali.316326.xyz/Article/details/gteyokswqz.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gtruwbqwhg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aizwys.cn/Article/details/gtwsgctfgf.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gtyrrdivxh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtwojjcxiw.html

[Q29] 最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gtvfqwerkv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtevhgdqyw.html

[Q30] 分组统计
来源：http://dali.hfpthk.cn/Article/details/gtacfhbftk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtmoydytcy.html

[Q31] 分组后过滤
来源：http://dali.haohaochexian.top/Article/details/gtyaxcucaz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gttzpwhnrn.html

[Q32] 分组拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtblajfrwz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtmbpaveth.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gtbgdpjsoy.html

[Q33] 多列分组
来源：http://dali.xuanzx.com/Article/details/gtvvuuulvq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.smart0.xyz/Article/details/gtircdracm.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gtlfifgawf.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdawozja.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258.top/Article/details/gtrhvqteif.html

) t WHERE rn = 1;
来源：http://dali.yj202588.top/Article/details/gtiscszvqj.html

[Q35] 内连接
来源：http://dali.snrcjt.cn/Article/details/gtbxftlfyg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtzsbfdset.html

[Q36] 左连接
来源：http://dali.nanxinkj.top/Article/details/gtihoflfjs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtzmerdsok.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gtbfzidtfj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ppjwa.cn/Article/details/gttzfvclml.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aibaodan.cn/Article/details/gteunmtxjy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yvedp.cn/Article/details/gthrbwdvfm.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gtnhggakku.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigfzy.top/Article/details/gtgiihmuot.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gtygjzewoq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aibaodan.cn/Article/details/gthscwvmvf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ivvv.top/Article/details/gtzxrfhevj.html

[Q41] 多表连接
来源：http://dali.dashuyun.cn/Article/details/gthxlfwisb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gtirkxlbdm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nwbrower.top/Article/details/gtproctknt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gtvotzkcds.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigufen.top/Article/details/gtckijasqx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jlsjyb.cn/Article/details/gtczuqccln.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzyhufis.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gtsgysaayc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhengqikj.top/Article/details/gthtjhwhen.html

[Q44] IN 子查询
来源：http://dali.zhongyouzk.top/Article/details/gthvukzogd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gtueuxddhk.html

[Q45] EXISTS 判断存在
来源：http://dali.shuidangran.top/Article/details/gtqfjdhcnz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gtokvoggkm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gtcwkadnlh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtebwlldgo.html

[Q47] 与平均值比较
来源：http://dali.jqgfzy.top/Article/details/gtquqjpfws.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.iojbl.cn/Article/details/gtsxtyrvrl.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxinkj.top/Article/details/gtkmadqzsy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gtpnxrcbpi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gtidltzmhq.html

[Q49] 更新单行
来源：http://dali.gogol.net.cn/Article/details/gtdzadmprn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtwaaphhqp.html

[Q50] 批量更新
来源：http://dali.9152youxi.cn/Article/details/gtweznuwts.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gtlfnmdtom.html

[Q51] 用子查询更新
来源：http://dali.zycfv.cn/Article/details/gtkmhnajto.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.0kj1m.cn/Article/details/gtgcnafnhg.html

[Q52] 删除指定行
来源：http://dali.hnxiangtu.top/Article/details/gtrnkdxasa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gtobnpkfus.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gtybdapcvf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gthhzakqcq.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gtusovapsb.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gtdsgjwukd.html

[Q55] 排名（并列占位）
来源：http://dali.meibo888.top/Article/details/gtadmfxvsk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtekxeyked.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhixingplan.top/Article/details/gtwtwqlnec.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gtcnhumgpk.html

[Q57] 行号
来源：http://dali.chenjidiqi.icu/Article/details/gtmodppjfy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.c1oappe.top/Article/details/gtczoltatl.html

[Q58] 累计求和
来源：http://dali.yj202588.top/Article/details/gtdjhodoyx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmzzyphb.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gtbsrbxcnx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtlprmcirx.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gtaeyaawcp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fengsongda.top/Article/details/gtlaldfjoi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtdccuwzrq.html

[Q61] 移动平均
来源：http://dali.guannengcc.top/Article/details/gtugpfvfln.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtioxbobap.html

[Q62] 分组占比
来源：http://dali.daria6918.cn/Article/details/gticssdohb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtjlvzmjmi.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gtqfpszwhj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gtgipifcbz.html

[Q64] 提交事务
来源：http://dali.hywenlv.cn/Article/details/gtgsfccpne.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzydgrnk.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gtjkysuipv.html

ROLLBACK;
来源：http://dali.yanxiufei.cn/Article/details/gtmmyqmdnj.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gtfaodbhny.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenzaomai.com/Article/details/gtyddeqnhw.html

[Q67] 设置隔离级别
来源：http://dali.yanxiufei.cn/Article/details/gteiniaztb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fengsongda.top/Article/details/gtbxmivtxl.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gtnzqyrblq.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gtsdvajedq.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gtrbiepyrt.html

[Q69] 查看执行计划
来源：http://dali.xylfe.cn/Article/details/gtkbgvvsqb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pycfn.com/Article/details/gttxcpczal.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gtydskppet.html

ANALYZE TABLE users;
来源：http://dali.sufxvd.cn/Article/details/gtqiiidprs.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gtyyiylaqe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gtdtrmcxlm.html

[Q72] 查看索引
来源：http://dali.hysaishi.cn/Article/details/gtahcsellt.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gticatdewd.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gthnmitckb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daxiang520.top/Article/details/gtvaujdwsj.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gtionuxmel.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cqqwz.cn/Article/details/gtladbvowm.html

[Q75] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtyvualtwe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtzzvpbjxa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.birdmap.top/Article/details/gtabloyhnq.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gtwyjvucow.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hammf.cn/Article/details/gtfpdmclmq.html

[Q77] 时间加减
来源：http://dali.andypj.xyz/Article/details/gtdbgywars.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtpxmmvzlo.html

[Q78] 当前时间
来源：http://dali.c1oappe.top/Article/details/gttyddximv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xylfe.cn/Article/details/gtbykbuhfs.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtovuplofw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gtfanmkjfr.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gtwfvkmvtc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gteafyaxlz.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoafsewwv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtcilwqmqv.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gtlybnwfey.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtkvkdvvov.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtyojundzy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtissfrbmh.html

[Q84] 去除首尾空格
来源：http://dali.daxiang520.top/Article/details/gtsgmuxkim.html

SELECT TRIM(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtnfkymjnl.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gtdhgahcck.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guannengcc.top/Article/details/gtrmgcfqjt.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gtxhwkvkug.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gtwufqpenm.html

[Q87] JSON 字段做条件
来源：http://dali.zhongyouzk.top/Article/details/gtkhsckmmk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gtlmwgofac.html

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gtdtcfsglk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxinkj.top/Article/details/gtyawdsxim.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gtmhclxyva.html

[Q89] 判断表是否存在
来源：http://dali.smart0.xyz/Article/details/gteqhgjbjf.html


<!-- 参考信息 -->