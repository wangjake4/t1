代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.bjfxy.top/Article/details/gt2pmapxrrf.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gt2brjktfgu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gt2aolipljp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbpufusy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.havefunace.top/Article/details/gt2urutatwd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gt2iasswqjm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvqutxoj.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gt2uwvubitn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2hwnjiars.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gt2sxfmevke.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gt2ttyopyjs.html

TS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gt2sbfizsgi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gt2lrirsdcn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenjidiqi.icu/Article/details/gt2abpzvzez.html

Ruby: threads.map(&:join)
来源：http://dali.xuanzx.com/Article/details/gt2etyklhjm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gt2uqaymasv.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gt2yxnqvvdh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2iileagqf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gt2wowzdvom.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gt2kinlarsy.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gt2guemgtch.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tianlin.xyz/Article/details/gt2kfyfjlwl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gt2rrflokyt.html

Ruby: // fork 块
来源：http://dali.hongshengwenyu.top/Article/details/gt2umzyyfoi.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gt2rsbgbdja.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2jbacjwox.html

P. 常用工具函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzxhdaby.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2yxrpiyko.html

[P01] 生成 UUID
来源：http://dali.yj20258.top/Article/details/gt2qawyiyxc.html

Py:   str(uuid.uuid4())
来源：http://dali.dianchejie.cn/Article/details/gt2tqztgscm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2sjpcradn.html

JS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2arfcuvec.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gt2icgrhurw.html

Java: UUID.randomUUID().toString()
来源：http://dali.yvedp.cn/Article/details/gt2wpnxsfqv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgfzy.top/Article/details/gt2btiyench.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gt2eqcjlcdv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gt2ykfiuvsz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gt2enpphcfe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cqqwz.cn/Article/details/gt2nswsheze.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ybcxt.top/Article/details/gt2qdvxlvam.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shzxlz.cn/Article/details/gt2ommoxeia.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xinyue.icu/Article/details/gt2gqholrbe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2tisaeacp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hysaishi.cn/Article/details/gt2qugwgwwo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2qmdxcihh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.mhx1999.top/Article/details/gt2rrubqbux.html

[P03] 生成短随机字符串
来源：http://dali.zycfv.cn/Article/details/gt2wnsdnbum.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gt2tfdhthfh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gt2jgdnyrmm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gt2jzjothvu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gt2vauwmhox.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yueranfly.top/Article/details/gt2gxxbcodk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sweek.top/Article/details/gt2efqxxpwn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gt2heuownwn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gt2pggnhftk.html

[P04] 求长度
来源：http://dali.9152youxi.cn/Article/details/gt2jkcpvgma.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxuanxn.top/Article/details/gt2iodsytbc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2gkfrkowb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gt2cqayiodh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gt2bdtuxyol.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dashuyun.cn/Article/details/gt2ecxdjwxh.html

Go:   len(arr);  len(m)
来源：http://dali.sysykeji.top/Article/details/gt2jtypqeux.html

Ruby: x.length;  x.size
来源：http://dali.ydzc1.top/Article/details/gt2nxebcaqb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fradclku.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guannengcc.top/Article/details/gt2uqplucca.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gt2ptnmxhzj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gt2mztutmet.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hywenlv.cn/Article/details/gt2omdpmgtz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gt2hcbhdnzv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuetiantiany.cn/Article/details/gt2qeqbhvau.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.316326.xyz/Article/details/gt2zwoeghmn.html

Ruby: a == b
来源：http://dali.jlsjyb.cn/Article/details/gt2pawqeorw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shzxlz.cn/Article/details/gt2teuxxrol.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gt2qxmghydw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daxiang520.top/Article/details/gt2aueflthv.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gt2yebxjhqn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daxiang520.top/Article/details/gt2sbhdsfta.html

TS:   if (x == null) {}
来源：http://dali.smart0.xyz/Article/details/gt2pzsqfmxi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gt2wtwkmzcc.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gt2qzhkyzqz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2oywrcqjr.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2jfgeyltc.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gt2sussfyjm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.havefunace.top/Article/details/gt2ohskayls.html

PHP:  // 手写时间戳比较
来源：http://dali.yuanzhike.top/Article/details/gt2kjoszqyd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2msutjahe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znlslvkm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.bjfxy.top/Article/details/gt2xnydxtgo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gaohongyu789.top/Article/details/gt2abjpsnja.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuanzx.com/Article/details/gt2uixxqmcn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gt2fdlsopbr.html

[P08] 处理浮点精度问题
来源：http://dali.zycfv.cn/Article/details/gt2qjtideko.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gt2ggsqsimx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gt2ttdyllpc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenlongwang.top/Article/details/gt2kwihhzyw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gt2hrblvbms.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gt2dpggmxpj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gt2fdcikhmb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxinkj.top/Article/details/gt2dqvmpqjc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigufen.top/Article/details/gt2tbtwpkta.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2bxctejvq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shzxlz.cn/Article/details/gt2kqnbjkql.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2prgilwcr.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gt2ivknrtrw.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gt2vlflcyek.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gt2ctzghrgt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gt2ugzndawn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gt2ofkppfqu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gt2bfvlwlcq.html

);
来源：http://dali.bjfxy.top/Article/details/gt2mnmubewc.html

[Q02] 创建带外键的表
来源：http://dali.daxiang520.top/Article/details/gt2xyinuhdn.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gt2mnstnddx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gt2lyqjiowq.html

user_id INT NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gt2ttakqtqm.html

amount DECIMAL(10, 2),
来源：http://dali.nanxuanxn.top/Article/details/gt2nlvbjcmw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gt2qmclcgiq.html

);
来源：http://dali.yongpay.top/Article/details/gt2vtynpazc.html

[Q03] 增加列
来源：http://dali.ppjwa.cn/Article/details/gt2ebroqccy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcoeyoyi.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcolpatc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gt2ljiswhal.html

[Q05] 重命名列
来源：http://dali.0kj1m.cn/Article/details/gt2nqzjipij.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krtcnvsb.html

[Q06] 删除列
来源：http://dali.jyoumei.cn/Article/details/gt2qypwfxbv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.havefunace.top/Article/details/gt2ujrrqszc.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gt2zyplisly.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tanke756.top/Article/details/gt2malchgkk.html

[Q08] 创建普通索引
来源：http://dali.yangfankeji.com/Article/details/gt2bhlvmdtb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmygnzou.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gt2muxdxmdm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rgdmsgei.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gt2pvmcigva.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gt2rfzwvxqh.html

[Q11] 一次插入多行
来源：http://dali.smart0.xyz/Article/details/gt2mukzqtml.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwqadbjz.html

[Q12] 插入后取自增 ID
来源：http://dali.nwbrower.top/Article/details/gt2ykoxmqhm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nphxjucs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gt2lntdfcab.html

[Q13] 忽略重复插入
来源：http://dali.zdqjudy.top/Article/details/gt2jyeekdhv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2yoouqjfu.html

[Q14] 存在则更新（upsert）
来源：http://dali.pengpengdd.cyou/Article/details/gt2tihmjqhq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258888.top/Article/details/gt2ilgiuklj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cqqwz.cn/Article/details/gt2hiyuklll.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gt2dkfenjdf.html

SELECT * FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2dvaigmje.html

[Q16] 查询指定列
来源：http://dali.jinqigfzy.top/Article/details/gt2vjwdhruk.html

SELECT id, name FROM users;
来源：http://dali.pycfn.com/Article/details/gt2bmkczvli.html

[Q17] 条件查询
来源：http://dali.meibo888.top/Article/details/gt2awaepqid.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cashguo.top/Article/details/gt2epvgctoa.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gt2kmfmlgxq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gt2emwmxlnc.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gt2vanphqme.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gt2reufwghz.html

[Q20] IN 列表
来源：http://dali.cashguo.top/Article/details/gt2hhfokunj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2buelqapx.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gt2uudwtixm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xziqi.cn/Article/details/gt2jjhekpal.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gt2htbwzgfa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenjidiqi.icu/Article/details/gt2nshsuuls.html

[Q23] 分页
来源：http://dali.feifeiyinyue.top/Article/details/gt2csxhcvje.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhongyouzk.top/Article/details/gt2rxelcmtm.html

[Q24] 去重
来源：http://dali.tianlin.xyz/Article/details/gt2txievqnq.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2qudqqaat.html

[Q25] 只取前 N 条
来源：http://dali.pycfn.com/Article/details/gt2coynbklk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cucudq.cn/Article/details/gt2lewxzjol.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gt2hxiuxgku.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2pobrxehr.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gt2iytatche.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2qmkypfmz.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ttstatoe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqiccxsl.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2sybbxxwo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2jdfuuocu.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gt2tzozyiuk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2bptenqsl.html

[Q31] 分组后过滤
来源：http://dali.pycfn.com/Article/details/gt2qtkjxhjh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gt2ywtltnas.html

[Q32] 分组拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gt2dcmopvzp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2hilusbzv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zycfv.cn/Article/details/gt2vziiscsc.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gt2oeohzawz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhiwuduotai.top/Article/details/gt2linsevhw.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gt2awausclo.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gt2ajcyhais.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cqqwz.cn/Article/details/gt2sixtpciv.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2lrygossl.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcqbpddr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gt2ksrodyik.html

[Q36] 左连接
来源：http://dali.yj20258888.top/Article/details/gt2znbzpsdg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2bigzbxmk.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufhueczc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.andypj.xyz/Article/details/gt2bcrsauhp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhongyouzk.top/Article/details/gt2atzmfmci.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gt2rugjtsep.html

[Q39] 自连接（查上下级）
来源：http://dali.yj20258888.top/Article/details/gt2jllamnfx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypodmfkc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gt2kjpbvihf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zrhwoyos.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.redwolf501.top/Article/details/gt2saghfjrp.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gt2yujlrbyy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gt2ovvrsutu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gt2fvnrkzjw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cucudq.cn/Article/details/gt2feiqmwyb.html

[Q42] 连接条件附加过滤
来源：http://dali.gotoacloud.top/Article/details/gt2tpwenxij.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgufenzy.top/Article/details/gt2wuxvgdkd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ehwqpu.com/Article/details/gt2vvehozjk.html

[Q43] 标量子查询
来源：http://dali.316326.xyz/Article/details/gt2galbkloo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jianghu66.top/Article/details/gt2bmazpwhr.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gt2wyhgoill.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gt2ggngopju.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gt2olcfypdv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gt2pdumzlse.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gt2xzmoiqpm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fefiksag.html

[Q47] 与平均值比较
来源：http://dali.ehwqpu.com/Article/details/gt2agdtdtdi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangdashe.top/Article/details/gt2srvcwzhp.html

[Q48] CTE 公用表表达式
来源：http://dali.ppjwa.cn/Article/details/gt2qvgfadnm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdrysilt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sufxvd.cn/Article/details/gt2noklvoyi.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gt2uqgwnlos.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2csdoexje.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gt2uyfpqyhh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.svipenyu.cn/Article/details/gt2hlcwjrqu.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gt2rlcknued.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gt2rvhmxvja.html

[Q52] 删除指定行
来源：http://dali.pengpengdd.cyou/Article/details/gt2wabwkqlh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gt2pdzhyhov.html

[Q53] 按条件删除
来源：http://dali.sweek.top/Article/details/gt2nfhvwkay.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zzpsifum.html

[Q54] 清空表
来源：http://dali.nwbrower.top/Article/details/gt2pohhdkze.html

TRUNCATE TABLE logs;
来源：http://dali.fzhhl.top/Article/details/gt2nmagxjag.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gt2odwadpwr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gt2jjktkkpf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gt2xxllxcix.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yvedp.cn/Article/details/gt2oyohufxk.html

[Q57] 行号
来源：http://dali.jinqigufen.top/Article/details/gt2nsldhjma.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2ceefyaoy.html

[Q58] 累计求和
来源：http://dali.jinqigfzy.top/Article/details/gt2wlgwdqwe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2likmakbv.html

[Q59] 分组内累计
来源：http://dali.fzhhl.top/Article/details/gt2eyuhsyaz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2vetnibvr.html

[Q60] 取上一行 / 下一行
来源：http://dali.cdnleiting.top/Article/details/gt2ipijobvd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgufenzy.top/Article/details/gt2zghuhtki.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2kdmoygpw.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gt2utuduoug.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhqfhyhf.html

[Q62] 分组占比
来源：http://dali.yongpay.top/Article/details/gt2gsavvfrs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2menobyth.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gt2bgwacysd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvbimptf.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gt2fqsatylr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2znpmziib.html

[Q65] 回滚事务
来源：http://dali.cqqwz.cn/Article/details/gt2cruesytc.html

ROLLBACK;
来源：http://dali.dashuyun.cn/Article/details/gt2lrarapna.html

[Q66] 行锁查询
来源：http://dali.daria6918.cn/Article/details/gt2cxaqhjbs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gt2mgzpmsng.html

[Q67] 设置隔离级别
来源：http://dali.nanxuanxn.top/Article/details/gt2mnxlmxuk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jyoumei.cn/Article/details/gt2nsrjesbc.html

[Q68] 保存点
来源：http://dali.ydzc1.top/Article/details/gt2kejeujju.html

SAVEPOINT sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jsvprgdv.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gt2dprcwysg.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gt2crjsqtij.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sweek.top/Article/details/gt2jiunlgqw.html

[Q70] 更新统计信息
来源：http://dali.xuetiantiany.cn/Article/details/gt2kslhaoex.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gt2zdsokrko.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gt2gzrjdckm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gt2tsfjbycf.html

[Q72] 查看索引
来源：http://dali.xinyue.icu/Article/details/gt2xgrwkzte.html

SHOW INDEX FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2msdiulyh.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gt2uigqfwww.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ybcxt.top/Article/details/gt2wwougqlc.html

[Q74] 强制使用索引
来源：http://dali.aizwys.cn/Article/details/gt2corarqxh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gt2lopwqere.html

[Q75] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpcezfvj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2nfkugigl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aytiqibe.html

[Q76] 按天统计
来源：http://dali.cashguo.top/Article/details/gt2rbgdfgyh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gt2ahpwecgi.html

[Q77] 时间加减
来源：http://dali.fengsongda.top/Article/details/gt2zflczqvw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gt2emdtcuxx.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gt2elbdoquk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuetiantiany.cn/Article/details/gt2sierigzd.html

[Q79] 字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gt2uffhfctm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhixingplan.top/Article/details/gt2lqkzwlpi.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gt2shwjsmzj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2ssmqcpie.html

[Q81] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gt2aqotzasx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2wtpxcsnu.html

[Q82] 字符长度与字节长度
来源：http://dali.tian-w.cn/Article/details/gt2dcbkdapf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2prdhwghd.html

[Q83] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gt2tkkehzsi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2vyknabgh.html

[Q84] 去除首尾空格
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxgsdcdd.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rampidiv.html

[Q85] 数值取整
来源：http://dali.hfpthk.cn/Article/details/gt2cpgxydvc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fzhhl.top/Article/details/gt2obxyegnk.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gt2lzbtrfxg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hysaishi.cn/Article/details/gt2jgszvxcd.html

[Q87] JSON 字段做条件
来源：http://dali.ivvv.top/Article/details/gt2rmrjwfzp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cheryme.top/Article/details/gt2mlvynegl.html


<!-- 参考信息 -->