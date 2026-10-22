代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258888.top/Article/details/gtgogjhimv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnqzz.top/Article/details/gtnsckoocu.html

JS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtsewwrfwf.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gttikqhqkl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.meibo888.top/Article/details/gttchxydob.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgfzy.top/Article/details/gtctwbokin.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gtrplfvlyh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sxryk.cn/Article/details/gtcygafnfs.html

[O06] 使用进程池
来源：http://dali.316326.xyz/Article/details/gtnacjmwfj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gtofqxoqhh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gtvarjvujr.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtaiimyfgk.html

TS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gtqyhaetek.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.meibo888.top/Article/details/gtglsxajua.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pycfn.com/Article/details/gtqzppcwxj.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gtkbduyzth.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtbjmixnee.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtitxqrswu.html

P. 常用工具函数
来源：http://dali.jinqigufen.top/Article/details/gtcgcojykp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtnlidjpuo.html

[P01] 生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gtjwdtszwn.html

Py:   str(uuid.uuid4())
来源：http://dali.feifeiyinyue.top/Article/details/gtnjnhnrar.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gtcoydszgu.html

JS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtkrluquci.html

TS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrimkeuay.html

Java: UUID.randomUUID().toString()
来源：http://dali.yvedp.cn/Article/details/gtedibixvd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ydzc1.top/Article/details/gtpugseslv.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gtjmpxbwdp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxinkj.top/Article/details/gtpjhvikfc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gtqwcxnzis.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gtzpuemjoh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuxming.cn/Article/details/gtcjkglkag.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gtnlltnsxu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gtlzxtumai.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtcbtyskop.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gtwmadpftp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtgerfgasa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zdqjudy.top/Article/details/gtuwtsjoqj.html

[P03] 生成短随机字符串
来源：http://dali.yvedp.cn/Article/details/gtipvttrrk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gtjsdvebog.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yonumen.top/Article/details/gtdencqzye.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtsxmtwobn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtjbftajqp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtwqplomlk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gtdaccsamc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgufenzy.top/Article/details/gtohrmlbux.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynbdyhgr.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gtuanyedpw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnxiangtu.top/Article/details/gteqesszjo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxscwmqb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtudvdnkqq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gtawcbtadh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtqrutuzsi.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gthizprhnt.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gtuipswhwo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.c1oappe.top/Article/details/gtvxipuzct.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gtdzxftxdg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gtawudokil.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhengqikj.top/Article/details/gtopqnjldr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aizwys.cn/Article/details/gtsqsibzuw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gtmcrogjjy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gtbinzltls.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xinyue.icu/Article/details/gtsvvblbxb.html

Ruby: a == b
来源：http://dali.sxryk.cn/Article/details/gtrsjgcaez.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gtestasgao.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tianlin.xyz/Article/details/gtsdyjjhvk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cheryme.top/Article/details/gtrvtnuaqx.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gtberubinu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guannengcc.top/Article/details/gtwoymrjxm.html

TS:   if (x == null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjghwazdi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtyawcanxw.html

Go:   if x == nil {}
来源：http://dali.guannengcc.top/Article/details/gtrosbcyub.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gticixjgex.html

C#:   if (x is null) {}
来源：http://dali.316326.xyz/Article/details/gtipfpwdnq.html

[P07] 防抖与节流
来源：http://dali.sufxvd.cn/Article/details/gtyuwcovst.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.snrcjt.cn/Article/details/gtfayxgztm.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gtlelfills.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtuwyxnpfh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtcsimczki.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tianlin.xyz/Article/details/gtrucdzxei.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuxming.cn/Article/details/gtpnxwhrpr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daxiang520.top/Article/details/gtnxdpxhis.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.c1oappe.top/Article/details/gtvxgkracf.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gthryiaiye.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tianlin.xyz/Article/details/gtyirnfuov.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fzhhl.top/Article/details/gtapsnvcvk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gtodivpill.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gtfpxyiwfa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gtovihvidm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gtrkwguett.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.bjfxy.top/Article/details/gtmdpasvgr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gttrocubtp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtapzqwtwy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtmyctkcjt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtyasssjdj.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gtbtbphumu.html

CREATE TABLE users (
来源：http://dali.haohaochexian.top/Article/details/gtkiwhywra.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtltoxovus.html

name VARCHAR(50) NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gthsdvhrqk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gtpxuggnoh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfcmzwdg.html

);
来源：http://dali.yangfankeji.com/Article/details/gtkspxhlww.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gtqyjefgsh.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gtmdqdikzg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gtaegjusqx.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtbnphjffb.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gthcvjgyjc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gtdimgosxq.html

);
来源：http://dali.jianghu66.top/Article/details/gtovcmfgeq.html

[Q03] 增加列
来源：http://dali.zdqjudy.top/Article/details/gtuwqjanpq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aizwys.cn/Article/details/gtqobgaayy.html

[Q04] 修改列类型
来源：http://dali.xinyue.icu/Article/details/gtjwhricjy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxomneys.html

[Q05] 重命名列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxegsrugf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuxming.cn/Article/details/gtjmlgshtj.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtdqzgdmmg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrwwjvkx.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gttpjjzqky.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dianchejie.cn/Article/details/gtjlxrtfus.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gtnbolcmlc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gtwhvvlpvt.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gtcvrmtitc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gtifdxgzwt.html

[Q10] 插入单行
来源：http://dali.redwolf501.top/Article/details/gtuvwlluiz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtrqiezwjj.html

[Q11] 一次插入多行
来源：http://dali.hysaishi.cn/Article/details/gthrmhbimu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guannengcc.top/Article/details/gtdncbgkap.html

[Q12] 插入后取自增 ID
来源：http://dali.0kj1m.cn/Article/details/gtduykgdqi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuxming.cn/Article/details/gthyktzldp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.havefunace.top/Article/details/gtgutecgbf.html

[Q13] 忽略重复插入
来源：http://dali.ivvv.top/Article/details/gtvhbiknai.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtqclglduy.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhiwuduotai.top/Article/details/gtbwurmklb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gtxxsikttq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gtznyneysq.html

[Q15] 查询全部
来源：http://dali.316326.xyz/Article/details/gttwujsiqz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtsqabrpmt.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtnyveooan.html

SELECT id, name FROM users;
来源：http://dali.smart0.xyz/Article/details/gtxqyxpgbu.html

[Q17] 条件查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntybhogx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gtukqfqxnz.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gtfjdcypnd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hammf.cn/Article/details/gtxcawowik.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gtwldxagep.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuanzhike.top/Article/details/gtmoeghfta.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gtrslqlhev.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fengsongda.top/Article/details/gtntbuqzjd.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gthrwqyrvl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nwbrower.top/Article/details/gtbpomzkkx.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gtavnghwhh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yvedp.cn/Article/details/gtfwlmteoc.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzyahtpi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuetiantiany.cn/Article/details/gtwjhwcost.html

[Q24] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtycpeials.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258888.top/Article/details/gtdpkfnzpw.html

[Q25] 只取前 N 条
来源：http://dali.yanxiufei.cn/Article/details/gtvvrqwfqz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gtresstljq.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gtplglwrri.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspsgichc.html

[Q27] 条件计数
来源：http://dali.zdqjudy.top/Article/details/gtxawqescp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuxming.cn/Article/details/gtrzniedyp.html

[Q28] 求和与平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgmfetgn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtnhomunhl.html

[Q29] 最大最小值
来源：http://dali.yuanzhike.top/Article/details/gteejnicng.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.316326.xyz/Article/details/gtphpuvnfp.html

[Q30] 分组统计
来源：http://dali.jinghuilouyu.cn/Article/details/gtkswreenu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gteixxxubo.html

[Q31] 分组后过滤
来源：http://dali.aibaodan.cn/Article/details/gtbtprsaxw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.9152youxi.cn/Article/details/gtgwwuedwr.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtvzxeqwwf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtvqbtrvdz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnqzz.top/Article/details/gtbrejvkwu.html

[Q33] 多列分组
来源：http://dali.zhengqikj.top/Article/details/gtdpiwlaxo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.birdmap.top/Article/details/gtnshdikch.html

[Q34] 每组取第一条
来源：http://dali.chenzaomai.com/Article/details/gtszcaqpcw.html

SELECT * FROM (
来源：http://dali.sweek.top/Article/details/gtgtomaroz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.bjfxy.top/Article/details/gtviaqajlc.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtsadnyqhh.html

[Q35] 内连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfggisysi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtjcmplclv.html

[Q36] 左连接
来源：http://dali.nanxuanxn.top/Article/details/gtbehvrqws.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtwlqxddrw.html

[Q37] 右连接
来源：http://dali.fengsongda.top/Article/details/gtvdpgllba.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtlaomqhag.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.316326.xyz/Article/details/gtdqvxfjyc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gtvrhyqwzh.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gtuaotmwxq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hfpthk.cn/Article/details/gtxjksnner.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gtkgxfluis.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aibaodan.cn/Article/details/gtfoprkukh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.316326.xyz/Article/details/gtlwoxeqyc.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gtxbhyyxad.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenzaomai.com/Article/details/gtylxutjet.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnqanbls.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gtibsvxkhr.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtktwogske.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxuanxn.top/Article/details/gtdhwddszm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ppjwa.cn/Article/details/gttxycgxrx.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gthikbykrk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtzsoobi.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gtknhubhce.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fzhhl.top/Article/details/gtpgeqjhya.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258888.top/Article/details/gthabitftj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtbajqjfff.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gtbhtmogky.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtcqkssubu.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gtwnouwkui.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtfjngakhn.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gteqnapwso.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yongpay.top/Article/details/gtghybqgdt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hammf.cn/Article/details/gtgxnwrptd.html

[Q49] 更新单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcdtvehx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtibppxtxq.html

[Q50] 批量更新
来源：http://dali.cashguo.top/Article/details/gtdzrsgzfc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtqfkwxvid.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gtrnhwlfhr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zdqjudy.top/Article/details/gtsstitipm.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gtmnaltxhd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtabwqzimu.html

[Q53] 按条件删除
来源：http://dali.yonumen.top/Article/details/gtheveenal.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pycfn.com/Article/details/gtsmsxtkmy.html

[Q54] 清空表
来源：http://dali.jqgufenzy.top/Article/details/gtndfyzrgy.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gtfslltqti.html

[Q55] 排名（并列占位）
来源：http://dali.cheryme.top/Article/details/gtgbyddhev.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gtykzjjlly.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ehwqpu.com/Article/details/gthdcvzqea.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gtcqeuzhul.html

[Q57] 行号
来源：http://dali.aizwys.cn/Article/details/gtzjanexqc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gtdijnyopb.html

[Q58] 累计求和
来源：http://dali.cqqwz.cn/Article/details/gtmovlwjod.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtpqvtedhc.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gtrnzppral.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtxdnltlbo.html

[Q60] 取上一行 / 下一行
来源：http://dali.quarkkingdee.top/Article/details/gtqyhzbcxi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuaelfxo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtzzqlwtxd.html

[Q61] 移动平均
来源：http://dali.cheryme.top/Article/details/gtmsnlrxjm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtxgotpafb.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkwzucnv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtwrlfnyrz.html

[Q63] 开启事务
来源：http://dali.daria6918.cn/Article/details/gtuasehijm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daria6918.cn/Article/details/gtxfdlsjhb.html

[Q64] 提交事务
来源：http://dali.aizwys.cn/Article/details/gtiyhnqdzj.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gtxjvvriao.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gtrspigemo.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gtgvgautjr.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gtfcgqeqao.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yongpay.top/Article/details/gtoomytboj.html

[Q67] 设置隔离级别
来源：http://dali.xylfe.cn/Article/details/gtntjdssih.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gtbsatyfjl.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gtxfcjbsrv.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gtgwtdphhe.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gtsvtsbibx.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gtsfivijmm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hongshengwenyu.top/Article/details/gtwqrqrnwh.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gtpysguofp.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtfzntqbmz.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gthlspgazk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gtfslgrjex.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gtwtedsofu.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtbupvkmzw.html

[Q73] 查看表状态
来源：http://dali.haohaochexian.top/Article/details/gtdwwibbwq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtmzpxpuku.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtofwvhknl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.mhx1999.top/Article/details/gtpuunwtrq.html

[Q75] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtycnwhusi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtemunfyme.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbhbnnnj.html

[Q76] 按天统计
来源：http://dali.yueranfly.top/Article/details/gtzqfgkjbr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.kuanghao11.cn/Article/details/gtaazdsqow.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gtffzbinmu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hfpthk.cn/Article/details/gtjpskzbca.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gtbbfvlcpe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gtvfabbuxj.html

[Q79] 字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtmhdfqjoj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jiagoushi.top/Article/details/gtlbgjhwww.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gtarsryqcl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtnsaaneec.html

[Q81] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtmjijdgbi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtvnbshbkp.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gtwxxkbgrd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtwrsfymbc.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtmjcbpvzw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtzlxmktze.html

[Q84] 去除首尾空格
来源：http://dali.aibaodan.cn/Article/details/gtfdsvgptm.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtxqojcaxq.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gtdddnrujs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhoulong.xyz/Article/details/gtuqkzdlmu.html

[Q86] 读取 JSON 字段
来源：http://dali.nwbrower.top/Article/details/gtebqxqudy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gtrbgaaxnv.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gtgnlbfwrh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtjblnkewx.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenjidiqi.icu/Article/details/gtrytdzngv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gtoytmfugt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtorijpgxf.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gtopblvxnn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gtwbnghqsu.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gtgnpgsvrp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258888.top/Article/details/gthyvgzvzp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtqngjwzhf.html


<!-- 参考信息 -->