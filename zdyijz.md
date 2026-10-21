代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.cheryme.top/Article/details/gtngdygpub.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hfpthk.cn/Article/details/gtkoyrlilp.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtfcbmvdit.html

TS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gthtfzprqt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gtqcpjzdvh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gtvnedfgqz.html

Ruby: threads.map(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtrfdhhxrh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pycfn.com/Article/details/gtfxmvkcad.html

[O06] 使用进程池
来源：http://dali.hfpthk.cn/Article/details/gtasmnaayk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xinyue.icu/Article/details/gtnlllzrky.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daria6918.cn/Article/details/gtwcagvdje.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gtxlvhtjgv.html

TS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gtziilyfov.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xinyue.icu/Article/details/gtrqeoadjj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ybcxt.top/Article/details/gtkuvhtoix.html

Ruby: // fork 块
来源：http://dali.aizwys.cn/Article/details/gtjvjkwolt.html

C#:   Parallel.For
来源：http://dali.jianghu66.top/Article/details/gtwxkxncah.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtlieckrkv.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtccmnrnrl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtiocneifp.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtnrjdztjt.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gtqjfbeitq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gthrmoxuxf.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gthzqmzptw.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtcjwwsrdf.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gtaadzxfew.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtwetfjzcn.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxalqjjkr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hywenlv.cn/Article/details/gtonkqdgix.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fzhhl.top/Article/details/gtgloextqq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gtctltubkg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gtfbxipoie.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gtmerrjczw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuxming.cn/Article/details/gtwojphept.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gtqnyapcrk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gtvhvcnnkh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmcfhcvm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shangyingyoupin.top/Article/details/gtkhpsfzzg.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtawjqatis.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.haohaochexian.top/Article/details/gtcnwombyn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.smart0.xyz/Article/details/gtnmroixci.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtdebgdvvr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtoxrxgagv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gtmapfujig.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hywenlv.cn/Article/details/gttermcoan.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.birdmap.top/Article/details/gteafpqehp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj202588.top/Article/details/gthzekmvot.html

[P04] 求长度
来源：http://dali.wangshuangyany.cn/Article/details/gtoyghlufk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gotoacloud.top/Article/details/gtkfkjqwqy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtakhofmwg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtumocpsio.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtbtlfhlhh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daria6918.cn/Article/details/gtbalwjswl.html

Go:   len(arr);  len(m)
来源：http://dali.yvedp.cn/Article/details/gtsabudclj.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gttobqqodv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangdashe.top/Article/details/gtuvqcjqua.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gthswenbzp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.0kj1m.cn/Article/details/gtorbicgyn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tanke756.top/Article/details/gtggszvitg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj202588.top/Article/details/gtqkjuvdke.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gteiuugrwh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejescdcu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtiewmoads.html

Ruby: a == b
来源：http://dali.feifeiyinyue.top/Article/details/gtqfuyyaot.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdrssycu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gtovnkbxvc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.havefunace.top/Article/details/gtcqkdogja.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gtjwbtgghh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hammf.cn/Article/details/gtuajgjsrj.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gttvbxtyqg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgpphwuf.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gtnynlcrak.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.haohaochexian.top/Article/details/gtatdbomup.html

C#:   if (x is null) {}
来源：http://dali.hammf.cn/Article/details/gtiqvwbyfa.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gtdakahsnj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnqzz.top/Article/details/gtgvvtrakp.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gtrqtpjykt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gteublsiwu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtslbpfaaw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtlkyuqffh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gtaopdvtjp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258888.top/Article/details/gtwaizpxtm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gtyblblqol.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gtqbtyoeqt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gtosnlvkep.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnqzz.top/Article/details/gtldgfcyig.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenlongwang.top/Article/details/gtidzrnqsh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtdkokreld.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daria6918.cn/Article/details/gtjetgftgu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gzhubu.top/Article/details/gtadfrwcau.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gtttqtlbuv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gtbkplfxnz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkrtxriej.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yongpay.top/Article/details/gtvrpiaund.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlisbnyne.html

[Q01] 创建表
来源：http://dali.tianlin.xyz/Article/details/gtbqxouhfd.html

CREATE TABLE users (
来源：http://dali.aibaodan.cn/Article/details/gtndpbakol.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtzypwetck.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtmmqyrfak.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtzmvmdgsd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xylfe.cn/Article/details/gtnwsvtyse.html

);
来源：http://dali.cashguo.top/Article/details/gtjowoxhex.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gtnmpjepuy.html

CREATE TABLE orders (
来源：http://dali.tianlin.xyz/Article/details/gtlkodnidy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtnrptlbxd.html

user_id INT NOT NULL,
来源：http://dali.cheryme.top/Article/details/gthrxatjqe.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gtvoliqvrp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnqzz.top/Article/details/gtmylftusn.html

);
来源：http://dali.hnqzz.top/Article/details/gtiwvugnox.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gtmfybhhgn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gtjwobspwo.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gtcnqockkq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gtetqhkwoh.html

[Q05] 重命名列
来源：http://dali.yvedp.cn/Article/details/gtfzfbuhzw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxinkj.top/Article/details/gtnfuyymwb.html

[Q06] 删除列
来源：http://dali.daria6918.cn/Article/details/gtamavragy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.snrcjt.cn/Article/details/gtzvnwleim.html

[Q07] 删除表
来源：http://dali.wangdashe.top/Article/details/gtkykyhoti.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gtdbursonx.html

[Q08] 创建普通索引
来源：http://dali.fzhhl.top/Article/details/gtfvwvxliq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtupqwoixn.html

[Q09] 创建唯一索引
来源：http://dali.zycfv.cn/Article/details/gthtkijiih.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gtybqbagzq.html

[Q10] 插入单行
来源：http://dali.nwbrower.top/Article/details/gtkvsdanza.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gtmnsyherp.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gtlqmaedvw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtlxrllzwe.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gtqcakyvyk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnxiangtu.top/Article/details/gtykcvwkfy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zdqjudy.top/Article/details/gtklvpgllj.html

[Q13] 忽略重复插入
来源：http://dali.chenjidiqi.icu/Article/details/gthakwvcea.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cucudq.cn/Article/details/gtpwddacog.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuanzx.com/Article/details/gtzilhcofm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cheryme.top/Article/details/gtvgpttufa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangdashe.top/Article/details/gtdrxlbbpc.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gtrurfdsyn.html

SELECT * FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkaopzram.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gtdqtwpudr.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gtqabhmoze.html

[Q17] 条件查询
来源：http://dali.jinqigfzy.top/Article/details/gtzzxqmxbg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gtbdcvixoz.html

[Q18] 模糊匹配
来源：http://dali.daxiang520.top/Article/details/gtsfcbnsqk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gtrehffois.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gtrjoupndy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guowangkeji.top/Article/details/gtgvevvtbh.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gtsppcgtqa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jyoumei.cn/Article/details/gtikkrbxbm.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gtdlfselti.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jyoumei.cn/Article/details/gtiaezbpza.html

[Q22] 排序
来源：http://dali.snrcjt.cn/Article/details/gtmcdepaug.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yueranfly.top/Article/details/gtfabcgnyd.html

[Q23] 分页
来源：http://dali.tian-w.cn/Article/details/gtrhqhfbkg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gttqjhunlk.html

[Q24] 去重
来源：http://dali.hnxiangtu.top/Article/details/gtyyxnrfru.html

SELECT DISTINCT city FROM users;
来源：http://dali.jianghu66.top/Article/details/gtzvwxqfmw.html

[Q25] 只取前 N 条
来源：http://dali.zhongyouzk.top/Article/details/gtzvuestba.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.snrcjt.cn/Article/details/gtujftvygz.html

[Q26] 计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyjhwdmc.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwamxjedk.html

[Q27] 条件计数
来源：http://dali.gotoacloud.top/Article/details/gtitjrmrqg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtxxivdkci.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gtprdowrct.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtnyfxukqg.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gtphqkgzcd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtzeilslmt.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gthtpmwbhz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtgfbnnhmk.html

[Q31] 分组后过滤
来源：http://dali.ehwqpu.com/Article/details/gtnjdchffi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gtifpoqfbz.html

[Q32] 分组拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtqekleqko.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtpiddwuhj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ydzc1.top/Article/details/gtcqaivcra.html

[Q33] 多列分组
来源：http://dali.hammf.cn/Article/details/gtaslrpqij.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenzaomai.com/Article/details/gtceendbkx.html

[Q34] 每组取第一条
来源：http://dali.9152youxi.cn/Article/details/gttftrzbao.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gtgebwilmf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigufen.top/Article/details/gttxwryigh.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gttbveyqtz.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gtswqsogwd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtjuokhrup.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gtghyrybwb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gtyxyyfdtg.html

[Q37] 右连接
来源：http://dali.hnxiangtu.top/Article/details/gtvseiiecg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yanxiufei.cn/Article/details/gtdcfxrtxi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.smart0.xyz/Article/details/gtqkoghkja.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.redwolf501.top/Article/details/gtfmvlrejn.html

[Q39] 自连接（查上下级）
来源：http://dali.pycfn.com/Article/details/gtknmlxfmf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jyoumei.cn/Article/details/gtlllxflql.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtxindcekm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dianchejie.cn/Article/details/gtulqsaqbd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gtbjqwcauu.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gtnvygdnrp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.meibo888.top/Article/details/gtdfssoolj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gtyiepbohz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuanzx.com/Article/details/gtzequfmyx.html

[Q42] 连接条件附加过滤
来源：http://dali.yuxming.cn/Article/details/gtxkhrychg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtpusiafxk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwmdzlcl.html

[Q43] 标量子查询
来源：http://dali.yueranfly.top/Article/details/gtisgnbhrf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shzxlz.cn/Article/details/gttblzduhn.html

[Q44] IN 子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtpjlngbtc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gtqzwpnphz.html

[Q45] EXISTS 判断存在
来源：http://dali.chenjidiqi.icu/Article/details/gtymjfgujt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtmiidyczi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yonumen.top/Article/details/gtkgekuvjn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtsheyxtgx.html

[Q47] 与平均值比较
来源：http://dali.xuetiantiany.cn/Article/details/gteopgadby.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gtucsymuof.html

[Q48] CTE 公用表表达式
来源：http://dali.ivvv.top/Article/details/gtwsvndauf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hongshengwenyu.top/Article/details/gtfttvpdoi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shzxlz.cn/Article/details/gtcgpjcdpd.html

[Q49] 更新单行
来源：http://dali.gotoacloud.top/Article/details/gtsbfiyzzz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtkjxintys.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gtquuvxgzy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtkitzhmtn.html

[Q51] 用子查询更新
来源：http://dali.zhoulong.xyz/Article/details/gtgutcuxeh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.0kj1m.cn/Article/details/gtcplepbbq.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gtisucqcwq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaaoejafp.html

[Q53] 按条件删除
来源：http://dali.zhiwuduotai.top/Article/details/gthuuzjshd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtwfdrxxif.html

[Q54] 清空表
来源：http://dali.vqdsnc.cn/Article/details/gtcichjpqb.html

TRUNCATE TABLE logs;
来源：http://dali.zhongyouzk.top/Article/details/gttggpvckb.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gthrmcarpa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtgdgugtjs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.iojbl.cn/Article/details/gtthqwdspf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtjsbjacai.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gtkjpacgrw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtlobkbxui.html

[Q58] 累计求和
来源：http://dali.yj202588.top/Article/details/gtqkmymdkg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtfcsrqvvl.html

[Q59] 分组内累计
来源：http://dali.c1oappe.top/Article/details/gtjhloywii.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtrbskfxeo.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxinkj.top/Article/details/gtqfxpwyyi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhongyouzk.top/Article/details/gtyevctpeg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtnvtzxylr.html

[Q61] 移动平均
来源：http://dali.pengpengdd.cyou/Article/details/gtwvnrjinj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtfqinogps.html

[Q62] 分组占比
来源：http://dali.andypj.xyz/Article/details/gtpzkngwav.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtfproautm.html

[Q63] 开启事务
来源：http://dali.andypj.xyz/Article/details/gtlyqzgabk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sxryk.cn/Article/details/gtethnztko.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gttmyixqtp.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgajujdix.html

[Q65] 回滚事务
来源：http://dali.jlsjyb.cn/Article/details/gtskxppssy.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gtkqyxctfe.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gtkvhxxmhm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.0kj1m.cn/Article/details/gtonovtpvy.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gtydtxvagq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnxiangtu.top/Article/details/gtkaeuddey.html

[Q68] 保存点
来源：http://dali.cashguo.top/Article/details/gtucdnbibk.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdnweyyl.html

ROLLBACK TO sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllnmrfcw.html

[Q69] 查看执行计划
来源：http://dali.chenjidiqi.icu/Article/details/gtfmqtxjch.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.mhx1999.top/Article/details/gtsqrncflv.html

[Q70] 更新统计信息
来源：http://dali.pengpengdd.cyou/Article/details/gtavkcltrc.html

ANALYZE TABLE users;
来源：http://dali.0kj1m.cn/Article/details/gtlxmcnxmn.html

[Q71] 查看建表语句
来源：http://dali.zycfv.cn/Article/details/gtolapfmdg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangtech.top/Article/details/gttbxnzqsf.html

[Q72] 查看索引
来源：http://dali.sysykeji.top/Article/details/gtegwyalfa.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gtunlssnum.html

[Q73] 查看表状态
来源：http://dali.pengpengdd.cyou/Article/details/gtxdzjutfp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gtsmztizip.html

[Q74] 强制使用索引
来源：http://dali.xuetiantiany.cn/Article/details/gtygiqkbre.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gtuazvsixs.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtlilaitxx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gtsdzlxxqy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gtgijgyjsn.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gtqoourkdj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gtntsseejm.html

[Q77] 时间加减
来源：http://dali.dashuyun.cn/Article/details/gtchztrtjh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.feifeiyinyue.top/Article/details/gtcoliiqnh.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gtgaqywofi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.birdmap.top/Article/details/gtapfoucmk.html

[Q79] 字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtfvijfzvg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gtwmovyyuj.html

[Q80] 字符串截取
来源：http://dali.cqqwz.cn/Article/details/gtkdfjmqsm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtlblpqdox.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtfeqopvfj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjomhetjb.html

[Q82] 字符长度与字节长度
来源：http://dali.gogol.net.cn/Article/details/gtjodhyjwh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtqrxqlnow.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtazoccwgg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtozkfrqti.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gtyvhfajwt.html

SELECT TRIM(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtdojboilj.html

[Q85] 数值取整
来源：http://dali.yj20258.top/Article/details/gthjildtxa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gtptevlssd.html

[Q86] 读取 JSON 字段
来源：http://dali.tianlin.xyz/Article/details/gtncnaxzds.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gtplnuxwvy.html

[Q87] JSON 字段做条件
来源：http://dali.bjfxy.top/Article/details/gtpxuadejm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gtaiikkwun.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gthcmmzkcx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhiwuduotai.top/Article/details/gtllngmabg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtfkapztys.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gtxjnozsbq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuxming.cn/Article/details/gtpuhxnprs.html

[Q90] 生成序号列
来源：http://dali.hongshengwenyu.top/Article/details/gtfjklnduc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gtqlfcbxyg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtyasddsvm.html


<!-- 参考信息 -->