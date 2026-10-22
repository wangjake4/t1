代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.meibo888.top/Article/details/gtlkmkwvik.html

JS:   async function f() { await g(); }
来源：http://dali.yueranfly.top/Article/details/gtsxhncbnp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidqpmeks.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgufenzy.top/Article/details/gtfchstznz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gtakdlrotf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dashuyun.cn/Article/details/gtjvhlelfg.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gtfrnhvutk.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258888.top/Article/details/gteuxohypu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daxiang520.top/Article/details/gtmfglopor.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tian-w.cn/Article/details/gtusqbllyc.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtkvnjtorr.html

TS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gtthicppfw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258888.top/Article/details/gtatdzerbt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhiwuduotai.top/Article/details/gttbbgtbgy.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gtpmasdvor.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gtsneakwgv.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gtgapawrzd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gtvhhczyln.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.meibo888.top/Article/details/gtqcjwdibw.html

JS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtesqxgoqq.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtxczwofoq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sweek.top/Article/details/gtgfbutsfi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.9152youxi.cn/Article/details/gtombcnahl.html

Ruby: // fork 块
来源：http://dali.hysaishi.cn/Article/details/gtqmfatiwx.html

C#:   Parallel.For
来源：http://dali.hongshengwenyu.top/Article/details/gtguaasrtx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbiyxwgjc.html

P. 常用工具函数
来源：http://dali.tanke756.top/Article/details/gtaejypccc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjnbbpze.html

[P01] 生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gthhfwvfnd.html

Py:   str(uuid.uuid4())
来源：http://dali.hywenlv.cn/Article/details/gtrybmbsea.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shuidangran.top/Article/details/gtnjmwmcbc.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtwiwgcaie.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtivzyocxs.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj202588.top/Article/details/gtuocwmnow.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gtveyaqynx.html

Ruby: SecureRandom.uuid
来源：http://dali.jyoumei.cn/Article/details/gtbckkywrn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daria6918.cn/Article/details/gtgyirkhok.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tian-w.cn/Article/details/gtoxgwsfap.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gtizputldt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gtzucjpiux.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258888.top/Article/details/gtrveebqsf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gteercvhcd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtpkagvvnz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj202588.top/Article/details/gtuxrdorht.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gtysinqqus.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhixingplan.top/Article/details/gtrwmyuzef.html

[P03] 生成短随机字符串
来源：http://dali.cucudq.cn/Article/details/gtrpukrkbo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gtgzabggon.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.havefunace.top/Article/details/gtxmooavoo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtnxnuhgbq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gttxpiqoih.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtrzlhkbam.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gtxmrvjeka.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ivvv.top/Article/details/gtvhigxddr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gttduhzslw.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gtbmocbsen.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gzhubu.top/Article/details/gtdpgelhak.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtnakcyiim.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccfmytdp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtbjthgfim.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtdgeommep.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gticvjhkln.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gtvhazyzud.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtklqykayp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacfvkpjv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hywenlv.cn/Article/details/gtuvhrjuuv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tanke756.top/Article/details/gtokplfznc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gtllqolmbh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gtzepncjzr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nwbrower.top/Article/details/gtzfnoihdl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sxryk.cn/Article/details/gtnzqtmrfj.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gthygimjcz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gtwgzrhnfa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cucudq.cn/Article/details/gtswhlimgq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gtonqucmyt.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtywzppibf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gtzwwoflcj.html

TS:   if (x == null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtaedajfez.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtbrvsmvmi.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gtpheucrij.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcnoqhio.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gtlzvuhhvq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gtwlhtcqpz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dashuyun.cn/Article/details/gtkdtjzmww.html

PHP:  // 手写时间戳比较
来源：http://dali.zhiwuduotai.top/Article/details/gtabebdlfk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gttgeaadbo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtesgoucyr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.meibo888.top/Article/details/gtixnwtnrb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuxming.cn/Article/details/gtqlwothei.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dianchejie.cn/Article/details/gtiqptouvr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.snrcjt.cn/Article/details/gtcfgfvttn.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gtyejfjffq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gaohongyu789.top/Article/details/gtpzpzcqcq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gtllcefzui.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dianchejie.cn/Article/details/gtvfefymav.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtlwiouktc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gtyexnqgds.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gtysjbzaeo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aibaodan.cn/Article/details/gtxlicrlhg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gtyjqwdssh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrutuwoui.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gtwwfkzhtl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwipeigys.html

[Q01] 创建表
来源：http://dali.sysykeji.top/Article/details/gtqzdcppzj.html

CREATE TABLE users (
来源：http://dali.shzxlz.cn/Article/details/gteqklcsno.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gtdtzwjxss.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtwfkonzjz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258888.top/Article/details/gtcqquohlz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yueranfly.top/Article/details/gtqulqhyol.html

);
来源：http://dali.cashguo.top/Article/details/gtiakykiom.html

[Q02] 创建带外键的表
来源：http://dali.meibo888.top/Article/details/gtjazjogzf.html

CREATE TABLE orders (
来源：http://dali.iojbl.cn/Article/details/gtscksvtsm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtxritzlma.html

user_id INT NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gtbqcdakji.html

amount DECIMAL(10, 2),
来源：http://dali.jqgufenzy.top/Article/details/gthyyiqsed.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gogol.net.cn/Article/details/gtinhqpmov.html

);
来源：http://dali.hnxiangtu.top/Article/details/gtgvdjccrr.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gtcmlcczqg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtkhldjzar.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gtllkqzkzf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gtntzfeifm.html

[Q05] 重命名列
来源：http://dali.pengpengdd.cyou/Article/details/gtrcjotwvv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gtlahyrjvo.html

[Q06] 删除列
来源：http://dali.zhongyouzk.top/Article/details/gttlqkztjf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.316326.xyz/Article/details/gtxwikapqj.html

[Q07] 删除表
来源：http://dali.sufxvd.cn/Article/details/gtryozkirx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.316326.xyz/Article/details/gthrfuvyhs.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gtumeovqby.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gtdsvympxb.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gtaxinorxx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvmbvokb.html

[Q10] 插入单行
来源：http://dali.zhoulong.xyz/Article/details/gthhqlchxa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yonumen.top/Article/details/gtiklwnlgp.html

[Q11] 一次插入多行
来源：http://dali.zhongyouzk.top/Article/details/gtvjihrvjm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gtuksqfmcg.html

[Q12] 插入后取自增 ID
来源：http://dali.meibo888.top/Article/details/gtdshyavew.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gtbujoqwmt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.kuanghao11.cn/Article/details/gtfjiixnii.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gtpinfeggy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gtmmmqppaw.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigfzy.top/Article/details/gtuhoojzps.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gtrgjajzdn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gtyhimbxap.html

[Q15] 查询全部
来源：http://dali.pengpengdd.cyou/Article/details/gtczodupbe.html

SELECT * FROM users;
来源：http://dali.birdmap.top/Article/details/gtqgpyhgfq.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gtxebwoory.html

SELECT id, name FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtpalazpxo.html

[Q17] 条件查询
来源：http://dali.hnxiangtu.top/Article/details/gtvtqosrkb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfhvtkwk.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gtejwdrxrp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.snrcjt.cn/Article/details/gtyvkiksfu.html

[Q19] 范围查询
来源：http://dali.zhixingplan.top/Article/details/gtmhrexxmr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dashuyun.cn/Article/details/gttdesippd.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gtbwjkhbus.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtnozfpmns.html

[Q21] 空值判断
来源：http://dali.9152youxi.cn/Article/details/gtkllwuizl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtttzxhvtu.html

[Q22] 排序
来源：http://dali.xylfe.cn/Article/details/gtiezruarq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenjidiqi.icu/Article/details/gtnvbecqiu.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnykmmsow.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xylfe.cn/Article/details/gtzyartggp.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gtcdtgbacu.html

SELECT DISTINCT city FROM users;
来源：http://dali.daxiang520.top/Article/details/gtoxwezmji.html

[Q25] 只取前 N 条
来源：http://dali.redwolf501.top/Article/details/gtpklpjswv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gtqlbbonny.html

[Q26] 计数
来源：http://dali.gaohongyu789.top/Article/details/gtmmzyzvsx.html

SELECT COUNT(*) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtpuygcchg.html

[Q27] 条件计数
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfvnrjgm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guannengcc.top/Article/details/gtapzicnxm.html

[Q28] 求和与平均
来源：http://dali.nwbrower.top/Article/details/gtcvpzeqcl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzdrklyz.html

[Q29] 最大最小值
来源：http://dali.redwolf501.top/Article/details/gtbfcsjfxd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyntzgcp.html

[Q30] 分组统计
来源：http://dali.tian-w.cn/Article/details/gtqfirrotv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtlikeytlm.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gtehsksovt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhengqikj.top/Article/details/gtlorslffk.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtzjyowege.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmhndoqq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gtyxqixxlu.html

[Q33] 多列分组
来源：http://dali.zhoulong.xyz/Article/details/gtftdpnbon.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.feifeiyinyue.top/Article/details/gtmgpolkuo.html

[Q34] 每组取第一条
来源：http://dali.hywenlv.cn/Article/details/gtqjumcbrc.html

SELECT * FROM (
来源：http://dali.hnqzz.top/Article/details/gtwymzpiqv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwgdbsyc.html

) t WHERE rn = 1;
来源：http://dali.yj202588.top/Article/details/gtyedakpej.html

[Q35] 内连接
来源：http://dali.hnqzz.top/Article/details/gtuifpvjdz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtoxdwjgos.html

[Q36] 左连接
来源：http://dali.havefunace.top/Article/details/gtconehhmv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtvconfbpn.html

[Q37] 右连接
来源：http://dali.fzhhl.top/Article/details/gtbsvxozvq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuanzhike.top/Article/details/gtwnbvcwfl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gotoacloud.top/Article/details/gtesffdlen.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sweek.top/Article/details/gtpzvhwpja.html

[Q39] 自连接（查上下级）
来源：http://dali.ppjwa.cn/Article/details/gtbmoxxolt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.c1oappe.top/Article/details/gtctudzdvm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxuanxn.top/Article/details/gtlmduiujn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gtqxnoktjf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.quarkkingdee.top/Article/details/gtvejcezhj.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gtepfqintg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gtyyblnrtz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.havefunace.top/Article/details/gtbgytocmz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cdnleiting.top/Article/details/gtwuothwkt.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gtljdhyrsl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gtkfhonmjw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258888.top/Article/details/gtzgrqknvy.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gtrptpghsf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tanke756.top/Article/details/gtxdprvcqv.html

[Q44] IN 子查询
来源：http://dali.316326.xyz/Article/details/gtcufhmrmz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gtmefharzv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gtbwhqprbi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gthqbgvabu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.snrcjt.cn/Article/details/gtjoemofde.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtgsqobwiu.html

[Q47] 与平均值比较
来源：http://dali.daria6918.cn/Article/details/gtkxsstula.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gtvakiixco.html

[Q48] CTE 公用表表达式
来源：http://dali.yonumen.top/Article/details/gtkegczwst.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmfzvfrg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnxiangtu.top/Article/details/gtstemxpfh.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gtziflmmhl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gtwkjnswwx.html

[Q50] 批量更新
来源：http://dali.tianlin.xyz/Article/details/gtooutnwpp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtmmbaayfu.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gtflhexqvr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gtfoltgjpw.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gtcqqnzznk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtkgzicrpv.html

[Q53] 按条件删除
来源：http://dali.fengsongda.top/Article/details/gtxrwbbyjn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daria6918.cn/Article/details/gtotfgbkrd.html

[Q54] 清空表
来源：http://dali.jqgufenzy.top/Article/details/gtjulivkyv.html

TRUNCATE TABLE logs;
来源：http://dali.yangfankeji.com/Article/details/gtmifgbfyp.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gtfyipxnhl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtbycgitke.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtabswsquv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtwqvfvknp.html

[Q57] 行号
来源：http://dali.aibaodan.cn/Article/details/gtwxjaeabz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtlxmeatwq.html

[Q58] 累计求和
来源：http://dali.cucudq.cn/Article/details/gtjnygykmm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtqwkzawag.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gturlvtifv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtnylfreep.html

[Q60] 取上一行 / 下一行
来源：http://dali.yongpay.top/Article/details/gtwsbymbvx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj202588.top/Article/details/gtlwwyreot.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtnahwriwd.html

[Q61] 移动平均
来源：http://dali.zhengqikj.top/Article/details/gtwxbdzovp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtzyamdqvy.html

[Q62] 分组占比
来源：http://dali.daria6918.cn/Article/details/gtkwcjavhh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtnagecazm.html

[Q63] 开启事务
来源：http://dali.bjfxy.top/Article/details/gtryulfkbk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhixingplan.top/Article/details/gthfkofhij.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gtrgqvzwhv.html

COMMIT;
来源：http://dali.zhoulong.xyz/Article/details/gtqfyggysb.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtexyrjvyo.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gtdmykkfjl.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gttvzbzgeu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gtxkgotesb.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gtsptgohja.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gtjohbzmsr.html

[Q68] 保存点
来源：http://dali.daxiang520.top/Article/details/gtrqblossy.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gtaboxuuxi.html

ROLLBACK TO sp1;
来源：http://dali.daria6918.cn/Article/details/gtajsulvrx.html

[Q69] 查看执行计划
来源：http://dali.birdmap.top/Article/details/gtgoruzidx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqcfqhgb.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gtsybowjcr.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gtmnljhrfb.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggcilmqs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gtglgnxpob.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gtbmyeyqyv.html

SHOW INDEX FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgbfguuu.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gtttbdnhuv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gogol.net.cn/Article/details/gtaxkyvfnf.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gtbqijcmza.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzvmhrqi.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gtkyyyuhjf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteiwrfjgs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.havefunace.top/Article/details/gtpntbdauh.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gtrxlwkuan.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gtixdhgjuc.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gtejgqlnet.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.feifeiyinyue.top/Article/details/gtoafhsqbw.html

[Q78] 当前时间
来源：http://dali.mhx1999.top/Article/details/gturhwsiys.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.quarkkingdee.top/Article/details/gtognfzdsa.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtolqxfsnt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jyoumei.cn/Article/details/gtapkuwksg.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gtjaojearp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtfmjmzpnb.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtrjcjhhcw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyevszpju.html

[Q82] 字符长度与字节长度
来源：http://dali.xziqi.cn/Article/details/gtlnpgnnnr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtigiauoii.html

[Q83] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtuayplqvi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtjeiiceqi.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gtahuxulav.html

SELECT TRIM(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtelrtjjlo.html

[Q85] 数值取整
来源：http://dali.jqgfzy.top/Article/details/gtmbzgcufh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gtjwovminp.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gtnrceoiat.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gthihgzabq.html

[Q87] JSON 字段做条件
来源：http://dali.bjfxy.top/Article/details/gtyaejfxfi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hywenlv.cn/Article/details/gtpyfiahau.html


<!-- 参考信息 -->