代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gt2lzftdena.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2iliapffi.html

[O04] 定义异步函数并等待
来源：http://dali.0kj1m.cn/Article/details/gt2bdumyute.html

Py:   async def f():⏎    await g()
来源：http://dali.hfpthk.cn/Article/details/gt2rwrpulqr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gt2puotvzfj.html

JS:   async function f() { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdcxevrg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fzhhl.top/Article/details/gt2bxinkrtt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gt2tymnjdel.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.9152youxi.cn/Article/details/gt2ohsufmnk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwsjcnwx.html

C#:   async Task F() { await G(); }
来源：http://dali.daria6918.cn/Article/details/gt2ndshoyrs.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gt2badrxmll.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pgxleszl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hywenlv.cn/Article/details/gt2onvdxzpt.html

JS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gt2tkttzbyw.html

TS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gt2loradqzg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gt2zznijwqc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cdnleiting.top/Article/details/gt2mdtiwglg.html

Ruby: threads.map(&:join)
来源：http://dali.wangdashe.top/Article/details/gt2eidyylvy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gt2jtcvxcgf.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gt2ehtbyxhv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gt2axauozwn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.kuanghao11.cn/Article/details/gt2ynbtwzdx.html

JS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gt2waeyfyzu.html

TS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gt2zkuujpbl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gt2ydviprrb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pycfn.com/Article/details/gt2kombkttu.html

Ruby: // fork 块
来源：http://dali.xziqi.cn/Article/details/gt2upsfiamd.html

C#:   Parallel.For
来源：http://dali.yangfankeji.com/Article/details/gt2emqitgxr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2eutzwkzm.html

P. 常用工具函数
来源：http://dali.gaohongyu789.top/Article/details/gt2gxnkvkfk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2hmvoknkj.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gt2gogvswqh.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gt2qnltzztj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nwbrower.top/Article/details/gt2wrdsqizl.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gt2sdvbzzya.html

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gt2bwboyboq.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ykeezscw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ybcxt.top/Article/details/gt2fmjnmjbd.html

Ruby: SecureRandom.uuid
来源：http://dali.yangfankeji.com/Article/details/gt2dzcfgapx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pycfn.com/Article/details/gt2mchwtbcd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yvedp.cn/Article/details/gt2wuluutoe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yanxiufei.cn/Article/details/gt2kqpezcgk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ydzc1.top/Article/details/gt2wsgtlxxw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2zblrxpem.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenzaomai.com/Article/details/gt2gtgvcnfk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2nkubzfoh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thocmmwu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gt2ohyoweqm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guowangkeji.top/Article/details/gt2skkpnirw.html

[P03] 生成短随机字符串
来源：http://dali.daxiang520.top/Article/details/gt2jciqhfpj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yangfankeji.com/Article/details/gt2lbramrak.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gt2rdivrchd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwvgxock.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gt2oyssoioh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cheryme.top/Article/details/gt2snqfahan.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgqhpibc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gt2kosfouqj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dianchejie.cn/Article/details/gt2eurrzorg.html

[P04] 求长度
来源：http://dali.9152youxi.cn/Article/details/gt2cdkivfln.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sysykeji.top/Article/details/gt2jliqqddu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2mslazikg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gt2njznteyo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gt2vkqspvhs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gt2gkzksluq.html

Go:   len(arr);  len(m)
来源：http://dali.cashguo.top/Article/details/gt2uaixxsjq.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gt2ohiffmyc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gt2hufwdfyo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gt2ckwaajfc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gt2xndepask.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.snrcjt.cn/Article/details/gt2gadltnjf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shuidangran.top/Article/details/gt2jlnnmdtf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gt2calfucml.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gt2ujmcdvdz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2tpvhktbm.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gt2gwjkguyh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fengsongda.top/Article/details/gt2rmlxpble.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.mhx1999.top/Article/details/gt2dhlnstlm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aimkqxew.html

PHP:  if (empty($x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqyermfo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tanke756.top/Article/details/gt2faueopii.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gt2ntfaazhz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvqijvcx.html

Go:   if x == nil {}
来源：http://dali.quarkkingdee.top/Article/details/gt2czcbiael.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pycfn.com/Article/details/gt2uzxvvinb.html

C#:   if (x is null) {}
来源：http://dali.sxryk.cn/Article/details/gt2xgplnwkf.html

[P07] 防抖与节流
来源：http://dali.cashguo.top/Article/details/gt2xsgbnvvh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gt2fuvxleqr.html

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gt2rynvrhuv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2wazyrqtl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2iajdfbkm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.meibo888.top/Article/details/gt2nwbylkcw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gt2mvmkrdkg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dianchejie.cn/Article/details/gt2oijgoxpk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gt2lixsftbl.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gt2ygyzfhhk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gt2vmolcnxq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sxryk.cn/Article/details/gt2jqxdhkpw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aibaodan.cn/Article/details/gt2mksvukxp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gt2kmmoubna.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jianghu66.top/Article/details/gt2wrhyuksa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqzjgbjl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kolmhwto.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzbucico.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2joligvul.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhongyouzk.top/Article/details/gt2zmaaqtlz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2tmdhcntb.html

[Q01] 创建表
来源：http://dali.yvedp.cn/Article/details/gt2ljsniept.html

CREATE TABLE users (
来源：http://dali.xinyue.icu/Article/details/gt2xkdytjgm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gt2jtgdhjkz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gt2tdftamjx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gt2lhbqkkuq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj202588.top/Article/details/gt2fdqtvdnf.html

);
来源：http://dali.hysaishi.cn/Article/details/gt2etaiieqk.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gt2hnvmueve.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gt2irwrrwky.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gt2wxzbfcoh.html

user_id INT NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gt2hxpnqmsz.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gt2ogrdihjy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuanzhike.top/Article/details/gt2ydzsjvad.html

);
来源：http://dali.smart0.xyz/Article/details/gt2gklmzyrz.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdnpfenp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangdashe.top/Article/details/gt2yhqjxtbi.html

[Q04] 修改列类型
来源：http://dali.316326.xyz/Article/details/gt2dgwozqhe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gt2objmxthc.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gt2ahphlqnh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jyoumei.cn/Article/details/gt2certntgx.html

[Q06] 删除列
来源：http://dali.jinqigufen.top/Article/details/gt2tzlkahno.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.snrcjt.cn/Article/details/gt2zmorqijt.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gt2walnkame.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gt2vjyfokgq.html

[Q08] 创建普通索引
来源：http://dali.shuidangran.top/Article/details/gt2qjkvaijc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gt2xlnchwla.html

[Q09] 创建唯一索引
来源：http://dali.daxiang520.top/Article/details/gt2irajegwm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gt2nqzkkyie.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gt2unrmzudy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gt2dtngdhjj.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gt2ijwgwssl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gt2dgmfhltc.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnubdxgr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnxiangtu.top/Article/details/gt2htyquxms.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gt2raszbqqd.html

[Q13] 忽略重复插入
来源：http://dali.hnqzz.top/Article/details/gt2fgasdpzo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cucudq.cn/Article/details/gt2igmnnayr.html

[Q14] 存在则更新（upsert）
来源：http://dali.9152youxi.cn/Article/details/gt2ahdnjtzy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gt2jusxdhar.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gogol.net.cn/Article/details/gt2smbdnxgz.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gt2dvputidt.html

SELECT * FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2qyutkqkt.html

[Q16] 查询指定列
来源：http://dali.yj20258.top/Article/details/gt2trdpzesy.html

SELECT id, name FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2eefkdwvy.html

[Q17] 条件查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ygwgxyya.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2agjuuzgm.html

[Q18] 模糊匹配
来源：http://dali.zhixingplan.top/Article/details/gt2ifficged.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gt2quosfeak.html

[Q19] 范围查询
来源：http://dali.gaohongyu789.top/Article/details/gt2qeevkwxb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntaewzcm.html

[Q20] IN 列表
来源：http://dali.ybcxt.top/Article/details/gt2chyrykgf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2cmtphcvv.html

[Q21] 空值判断
来源：http://dali.sxryk.cn/Article/details/gt2gvgqsuyj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2abnpnqax.html

[Q22] 排序
来源：http://dali.yongpay.top/Article/details/gt2jtqeitsl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sysykeji.top/Article/details/gt2wciaehxg.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebruvvmu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gt2pvgpfzdu.html

[Q24] 去重
来源：http://dali.svipenyu.cn/Article/details/gt2ezrdrujj.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2xznjedmg.html

[Q25] 只取前 N 条
来源：http://dali.cqqwz.cn/Article/details/gt2dlchfzau.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gt2pvugogmg.html

[Q26] 计数
来源：http://dali.wangdashe.top/Article/details/gt2gzzomqhp.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2hgcshjji.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gt2naxgdkvu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2mlkibalx.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gt2uxveglzv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2aibxgenh.html

[Q29] 最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gt2gsbjsqhp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2vovitqla.html

[Q30] 分组统计
来源：http://dali.chenzaomai.com/Article/details/gt2rapmpdoj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gt2ullmhdip.html

[Q31] 分组后过滤
来源：http://dali.jianghu66.top/Article/details/gt2jeakvlog.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gt2qhqnicse.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2fdwckgdm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gt2hbysxkzh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shuidangran.top/Article/details/gt2ibkgmsvc.html

[Q33] 多列分组
来源：http://dali.hnxiangtu.top/Article/details/gt2mfftyity.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxuanxn.top/Article/details/gt2ssstgcxn.html

[Q34] 每组取第一条
来源：http://dali.bjfxy.top/Article/details/gt2pgyhiefm.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gt2awqkvatf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.iojbl.cn/Article/details/gt2vibthgql.html

) t WHERE rn = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2jikzrdnr.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lojaiohi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gt2ukbcvaqw.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gt2eymaoyem.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gt2ysgqgbao.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gt2aqrawbyj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hysaishi.cn/Article/details/gt2uifbthoi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gt2vpsveztl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrrdydly.html

[Q39] 自连接（查上下级）
来源：http://dali.ybcxt.top/Article/details/gt2dugpanzh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxuanxn.top/Article/details/gt2ixllgwdw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gt2sdovpjoi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hongshengwenyu.top/Article/details/gt2qenvbklf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gt2pgzvmijl.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gt2ecopbnhd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gt2ktngycfm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gt2ppfpjrns.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258.top/Article/details/gt2fmgvmhsm.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gypgxunj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.havefunace.top/Article/details/gt2vuyqrfqe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gt2awjuyvqq.html

[Q43] 标量子查询
来源：http://dali.yj20258.top/Article/details/gt2abpqficl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jldnxbnw.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gt2ltqluljk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkjdfzua.html

[Q45] EXISTS 判断存在
来源：http://dali.fengsongda.top/Article/details/gt2aqbqlqxx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gt2vyvmxqoa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gt2pchpuqdz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gt2llvsudfm.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gt2dsvqljpj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gt2mzdhjzpx.html

[Q48] CTE 公用表表达式
来源：http://dali.fzhhl.top/Article/details/gt2lhjgvedq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kncjhfox.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hammf.cn/Article/details/gt2vifnwmuq.html

[Q49] 更新单行
来源：http://dali.wangshuangyany.cn/Article/details/gt2zflifykc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gt2bqrjkstb.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gt2nbedwqrd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hysaishi.cn/Article/details/gt2vfftxmtl.html

[Q51] 用子查询更新
来源：http://dali.smart0.xyz/Article/details/gt2quqmthiz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzbaqfdv.html

[Q52] 删除指定行
来源：http://dali.yj20258.top/Article/details/gt2yjrdahyf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gt2uwgbwpqw.html

[Q53] 按条件删除
来源：http://dali.iojbl.cn/Article/details/gt2dzvbsioy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcswqtyl.html

[Q54] 清空表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hobmvcji.html

TRUNCATE TABLE logs;
来源：http://dali.tian-w.cn/Article/details/gt2hxwqfxbm.html

[Q55] 排名（并列占位）
来源：http://dali.sxryk.cn/Article/details/gt2wasnqffj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2ptiucpup.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gt2dhfrypkp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shuidangran.top/Article/details/gt2ecbyvflo.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gt2lrkpvcix.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2cfgzynme.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gt2myvmsbou.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2trnprbti.html

[Q59] 分组内累计
来源：http://dali.pycfn.com/Article/details/gt2acgphsgr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2xtqocxkk.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gt2bkfqtuvy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sxryk.cn/Article/details/gt2iksuxaog.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2goaqxnza.html

[Q61] 移动平均
来源：http://dali.yanxiufei.cn/Article/details/gt2ykirbkqj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2ibyankzp.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gt2eeqkypoi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2tjrfriui.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gt2szsrmcfv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zdsetyvr.html

[Q64] 提交事务
来源：http://dali.xuanzx.com/Article/details/gt2hhtkxgvu.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gt2bbzyuyws.html

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gt2qfadinwe.html

ROLLBACK;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqtjftdb.html

[Q66] 行锁查询
来源：http://dali.svipenyu.cn/Article/details/gt2bvvrildd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gt2kbphzjfw.html

[Q67] 设置隔离级别
来源：http://dali.yuanzhike.top/Article/details/gt2gtydsqkv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.redwolf501.top/Article/details/gt2ablcsxvp.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gt2eugtwgpg.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pyehpxus.html

ROLLBACK TO sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2acnyguxi.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gt2kurmghke.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gt2dczrwbjo.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gt2oqicthpd.html

ANALYZE TABLE users;
来源：http://dali.redwolf501.top/Article/details/gt2acynivao.html

[Q71] 查看建表语句
来源：http://dali.nanxuanxn.top/Article/details/gt2yhfyhrau.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gt2yvgczvnw.html

[Q72] 查看索引
来源：http://dali.quarkkingdee.top/Article/details/gt2glyqxmxv.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2mduurpan.html

[Q73] 查看表状态
来源：http://dali.mhx1999.top/Article/details/gt2hcxojczc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cashguo.top/Article/details/gt2bqecjqid.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gt2gqivkztu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gt2wwznvogo.html

[Q75] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gt2ozltkgpq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2nksgfedz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.mhx1999.top/Article/details/gt2dzzsispx.html

[Q76] 按天统计
来源：http://dali.chenzaomai.com/Article/details/gt2tgnyxshx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcfigwkb.html

[Q77] 时间加减
来源：http://dali.sysykeji.top/Article/details/gt2quurhhgv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhongyouzk.top/Article/details/gt2crahtnqj.html

[Q78] 当前时间
来源：http://dali.sufxvd.cn/Article/details/gt2ehyrhiio.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gt2flrhtdfv.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gt2iuhldyit.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjskwdvm.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gt2znvfvayv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2bhmofllz.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xihpxerr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2anihleub.html

[Q82] 字符长度与字节长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnuwmpto.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2ydtrcsxw.html

[Q83] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2ukwcoqck.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2uoxxcdlx.html

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gt2lzvnapyl.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2ycpotjjl.html

[Q85] 数值取整
来源：http://dali.yvedp.cn/Article/details/gt2algykuqs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gt2vttwwcri.html


<!-- 参考信息 -->