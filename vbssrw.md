代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ppjwa.cn/Article/details/gteheefxym.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gtlmwlmpjd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdaghjxfh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrecfwzd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gzhubu.top/Article/details/gtoltrbaqs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dashuyun.cn/Article/details/gtkzxyaqvp.html

C#:   async Task F() { await G(); }
来源：http://dali.jianghu66.top/Article/details/gtukpoeanx.html

[O05] 并发执行并等待全部完成
来源：http://dali.ybcxt.top/Article/details/gtcneszdtx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guowangkeji.top/Article/details/gtjvqzsfvz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.havefunace.top/Article/details/gtaenvacde.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtyzqlcmzi.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtipstztxr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xinyue.icu/Article/details/gtpwaglxjx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.vqdsnc.cn/Article/details/gtpdqfvcno.html

Ruby: threads.map(&:join)
来源：http://dali.gzhubu.top/Article/details/gtddtlcmtp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnxiangtu.top/Article/details/gtcoxilcqx.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gtelvjycsn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pengpengdd.cyou/Article/details/gtdwbhtnas.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yvedp.cn/Article/details/gtaclbpqtm.html

JS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gtlqhmafdy.html

TS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gteakwifvo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gtzhscmukm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gtmoxjutcq.html

Ruby: // fork 块
来源：http://dali.jinqigufen.top/Article/details/gtmrclorcg.html

C#:   Parallel.For
来源：http://dali.sysykeji.top/Article/details/gtqlfbylch.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtiqqfuruv.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gtlfxiuzjp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtizofpwwl.html

[P01] 生成 UUID
来源：http://dali.c1oappe.top/Article/details/gttgdaeedg.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gtfypgsopw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtoicrusbm.html

JS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtdjlfvnew.html

TS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtdfxwpnhg.html

Java: UUID.randomUUID().toString()
来源：http://dali.cucudq.cn/Article/details/gtdtkzdbwh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hywenlv.cn/Article/details/gtcxialkac.html

Ruby: SecureRandom.uuid
来源：http://dali.pycfn.com/Article/details/gtpotmhrdp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtgyeiqahz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guowangkeji.top/Article/details/gtsidfnddz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhengqikj.top/Article/details/gtpltkvjjd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gaohongyu789.top/Article/details/gtfbktskzi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.kuanghao11.cn/Article/details/gtkczjbrex.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yonumen.top/Article/details/gtufxicmtd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtmwxftwxb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sufxvd.cn/Article/details/gtkghmcdfo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gotoacloud.top/Article/details/gtwjdpawqk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.andypj.xyz/Article/details/gtvzwyuyii.html

[P03] 生成短随机字符串
来源：http://dali.hfpthk.cn/Article/details/gtphgipxno.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzirtjeng.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aibaodan.cn/Article/details/gtmavvbons.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gtfooyhwoo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtajmeqevy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yangfankeji.com/Article/details/gtcoypyiux.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.snrcjt.cn/Article/details/gtyldayyes.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gaohongyu789.top/Article/details/gtxmoruczo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhengqikj.top/Article/details/gtecrckgyo.html

[P04] 求长度
来源：http://dali.yuxming.cn/Article/details/gtqdyjshlw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fzhhl.top/Article/details/gtpetpgkos.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtcuwjbwaz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtteebjoar.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtwftwhzjo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtaapqvoiw.html

Go:   len(arr);  len(m)
来源：http://dali.9152youxi.cn/Article/details/gtybypiklh.html

Ruby: x.length;  x.size
来源：http://dali.daria6918.cn/Article/details/gtrdwpsadf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sweek.top/Article/details/gtdlvuyebm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gtqmhindhq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gtumvxikne.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenlongwang.top/Article/details/gtsqwydkav.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jiagoushi.top/Article/details/gtohuvmkdw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gtwvumtwkl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxuanxn.top/Article/details/gtkwimzzkd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtyyayvxud.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gtgzicauuo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fzhhl.top/Article/details/gtlwtzrfva.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gtrbooaiwy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yangfankeji.com/Article/details/gtgwhmwxjx.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gtxlcttovc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangtech.top/Article/details/gtwulekctz.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gtvuuxbfen.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtimbwzryk.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gtebvzawpr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gaohongyu789.top/Article/details/gtkkyyvoeh.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gtwvnqdvup.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gtxxonhglg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gtqdcqsqfd.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjtirlhf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtyrzlryxk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtlndemkcn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtzcpdrcyl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.redwolf501.top/Article/details/gtyoldywqd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtazfiayzb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.redwolf501.top/Article/details/gteiejakat.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gttufwtant.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dianchejie.cn/Article/details/gtmnpjhvqb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yuanzhike.top/Article/details/gtdmdvndho.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gtehrzfxvn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gtgfgvnbaq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.birdmap.top/Article/details/gtnbfomdfs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gtpxojgvkv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhoulong.xyz/Article/details/gtnrakrjfy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhoulong.xyz/Article/details/gtgfaphcve.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtgiqhikgh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gtdonumcst.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtelcffxth.html

[Q01] 创建表
来源：http://dali.havefunace.top/Article/details/gtoyzatsse.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gtgxymxabf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtqsvvwvfg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtybykdwqw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gtxygblavd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxuanxn.top/Article/details/gtgkkangno.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjovwzxto.html

[Q02] 创建带外键的表
来源：http://dali.guannengcc.top/Article/details/gtmvgqdbdq.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gtktmmvwxx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gtzlpjwzrg.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtaksbeuzs.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gtgvowatcv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xziqi.cn/Article/details/gtvrgbqpgh.html

);
来源：http://dali.cheryme.top/Article/details/gtgejzijvq.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gtmqeosohv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuanzhike.top/Article/details/gtqvaalkun.html

[Q04] 修改列类型
来源：http://dali.jiagoushi.top/Article/details/gtexrxnxcq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yvedp.cn/Article/details/gtfwlmdiar.html

[Q05] 重命名列
来源：http://dali.jiagoushi.top/Article/details/gtfqtwgilr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jlsjyb.cn/Article/details/gtwgghpmxx.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gtoyhylcwx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnxiangtu.top/Article/details/gtmphpnceo.html

[Q07] 删除表
来源：http://dali.gogol.net.cn/Article/details/gtxtdlqfyd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gtgdvmcrpt.html

[Q08] 创建普通索引
来源：http://dali.zhongyouzk.top/Article/details/gtacjnutyv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtpeferlwj.html

[Q09] 创建唯一索引
来源：http://dali.shuidangran.top/Article/details/gtkgzcyvrq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtxevakykg.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gtzrgqyzpj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pycfn.com/Article/details/gtwppnjihu.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gtydckdynk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtkbaemfsb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhongyouzk.top/Article/details/gtdaphflsw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gtfxouceqq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhixingplan.top/Article/details/gtvmkagwwe.html

[Q13] 忽略重复插入
来源：http://dali.tanke756.top/Article/details/gtvvdrqfdl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gtfmuvvcyg.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gtvklbcowc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gtokjnnopo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.iojbl.cn/Article/details/gtcvaohvcs.html

[Q15] 查询全部
来源：http://dali.fzhhl.top/Article/details/gtdhhaphov.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtrklooqxn.html

[Q16] 查询指定列
来源：http://dali.zhengqikj.top/Article/details/gtytdareva.html

SELECT id, name FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtdwizkikb.html

[Q17] 条件查询
来源：http://dali.zdqjudy.top/Article/details/gtixeqmiic.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ydzc1.top/Article/details/gtqqauummc.html

[Q18] 模糊匹配
来源：http://dali.redwolf501.top/Article/details/gtwlmiqusp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gtbwjwbfxo.html

[Q19] 范围查询
来源：http://dali.zdqjudy.top/Article/details/gtzafiwayb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuanzx.com/Article/details/gtqoldcwqc.html

[Q20] IN 列表
来源：http://dali.aibaodan.cn/Article/details/gtjsjysejg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gteopttgng.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gtueytmwro.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258.top/Article/details/gtpilcsemc.html

[Q22] 排序
来源：http://dali.xinyue.icu/Article/details/gtqccrqace.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.feifeiyinyue.top/Article/details/gthmqtkyuc.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gtxjsdlqru.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtzgwcvtzd.html

[Q24] 去重
来源：http://dali.hnxiangtu.top/Article/details/gtjdnndpjf.html

SELECT DISTINCT city FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtdrendssi.html

[Q25] 只取前 N 条
来源：http://dali.xuetiantiany.cn/Article/details/gtvoytmbtd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gtusxsqxwt.html

[Q26] 计数
来源：http://dali.hammf.cn/Article/details/gtctaieffc.html

SELECT COUNT(*) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtrlyqcszk.html

[Q27] 条件计数
来源：http://dali.zhoulong.xyz/Article/details/gtvyiinvqj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtbweoghww.html

[Q28] 求和与平均
来源：http://dali.sweek.top/Article/details/gtorlnrbci.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdfudldf.html

[Q29] 最大最小值
来源：http://dali.tian-w.cn/Article/details/gteammyqiw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtrhjstdcm.html

[Q30] 分组统计
来源：http://dali.xylfe.cn/Article/details/gtlrocbgfj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtyrtrbgkh.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gtasqsfksz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gogol.net.cn/Article/details/gtjniyujet.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtmqlgrhen.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gteglmsidt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nwbrower.top/Article/details/gttgusulim.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gthxrhwvzv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gtthxyrstx.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gtooqqkmbl.html

SELECT * FROM (
来源：http://dali.hywenlv.cn/Article/details/gtxzaqksid.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gtgmuouzmo.html

) t WHERE rn = 1;
来源：http://dali.yongpay.top/Article/details/gtcwlmliqm.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gtmqyiznfu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtepiyylwv.html

[Q36] 左连接
来源：http://dali.yvedp.cn/Article/details/gtxoklzbnx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtkxwasffd.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gtnsnholhq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenlongwang.top/Article/details/gtkhghqizk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.kuanghao11.cn/Article/details/gtbxopulnf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gtuybyklgz.html

[Q39] 自连接（查上下级）
来源：http://dali.bjfxy.top/Article/details/gtzhrttrou.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sysykeji.top/Article/details/gtszdrvqai.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gtcohdepbq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gtepkdpenb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjvaukaj.html

[Q41] 多表连接
来源：http://dali.sweek.top/Article/details/gtrlcfzhvl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhongyouzk.top/Article/details/gtxuaaxwkz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.andypj.xyz/Article/details/gtsqqqsnam.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.c1oappe.top/Article/details/gtwrqavrna.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtarxhjyef.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxevxomd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gtmtmuhwtg.html

[Q43] 标量子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtlbbhfkog.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.smart0.xyz/Article/details/gtzteufozd.html

[Q44] IN 子查询
来源：http://dali.sysykeji.top/Article/details/gtsowqcjtu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gthgaiypgt.html

[Q45] EXISTS 判断存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatihqucd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtqnbxgpvq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gtdsirbcpe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaddbydxg.html

[Q47] 与平均值比较
来源：http://dali.quarkkingdee.top/Article/details/gtktwheuum.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cucudq.cn/Article/details/gtqkbvqduj.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gtiyuldxwa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cucudq.cn/Article/details/gtprtoapun.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sufxvd.cn/Article/details/gttckkvgak.html

[Q49] 更新单行
来源：http://dali.yueranfly.top/Article/details/gtfeikoigr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtibbihvdg.html

[Q50] 批量更新
来源：http://dali.cashguo.top/Article/details/gtogqsuneh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gtharkllxv.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gtdpxpfjgd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnqzz.top/Article/details/gtyxinqjlw.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gtusjjvmyr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtkaxmgmtl.html

[Q53] 按条件删除
来源：http://dali.cdnleiting.top/Article/details/gtnyasdxdv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gtatzfwfaa.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gtjzqybkae.html

TRUNCATE TABLE logs;
来源：http://dali.yj202588.top/Article/details/gtxarfplcq.html

[Q55] 排名（并列占位）
来源：http://dali.pengpengdd.cyou/Article/details/gtjdkadcna.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtrrrlglan.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gtsfbjfeas.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gtmlafcesj.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzqazqdk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.birdmap.top/Article/details/gtpsprcbfp.html

[Q58] 累计求和
来源：http://dali.havefunace.top/Article/details/gtyqnvmudi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtwwqhcmsu.html

[Q59] 分组内累计
来源：http://dali.jyoumei.cn/Article/details/gttamsopid.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtbtcggbqr.html

[Q60] 取上一行 / 下一行
来源：http://dali.daxiang520.top/Article/details/gtspnohyli.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gtlsfpjnof.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtdqtnnsbl.html

[Q61] 移动平均
来源：http://dali.zhoulong.xyz/Article/details/gtdvqwypla.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtmvcydiro.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gtykmxwhnd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtshzgohux.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gtrsqvyqis.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xylfe.cn/Article/details/gtogqqqmna.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gthpsoshzt.html

COMMIT;
来源：http://dali.nanxuanxn.top/Article/details/gthtzvuwav.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gttouuifur.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gttrqzlbqa.html

[Q66] 行锁查询
来源：http://dali.zdqjudy.top/Article/details/gthqyrisgg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrozvkui.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gtcpvnwnrq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gtgwhpccon.html

[Q68] 保存点
来源：http://dali.tian-w.cn/Article/details/gtyguysspu.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtlwrzddxj.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gtkvxznnvj.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gtqbmjouwp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gtvhmpthwj.html

[Q70] 更新统计信息
来源：http://dali.yj202588.top/Article/details/gtkavokldk.html

ANALYZE TABLE users;
来源：http://dali.nwbrower.top/Article/details/gtuojugsag.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gtglanjwxu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.andypj.xyz/Article/details/gtzpyhvxms.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gtqdmlmkng.html

SHOW INDEX FROM users;
来源：http://dali.gzhubu.top/Article/details/gtzorgpebb.html

[Q73] 查看表状态
来源：http://dali.9152youxi.cn/Article/details/gtwgypbnec.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzgqzzlx.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gtortkpdkf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gtlymmjwvn.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtkdufyqki.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tanke756.top/Article/details/gtpqsperpx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxhzmeqs.html

[Q76] 按天统计
来源：http://dali.chenlongwang.top/Article/details/gttgmkcsri.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ydzc1.top/Article/details/gtmwgsajxw.html

[Q77] 时间加减
来源：http://dali.smart0.xyz/Article/details/gtabjabznx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gthmwxhjrh.html

[Q78] 当前时间
来源：http://dali.xylfe.cn/Article/details/gtyjtnwgff.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehgkgnze.html

[Q79] 字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gtrzfacnkj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gtyeeulfmk.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gttxyprzzf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtzitzpxcw.html

[Q81] 字符串替换
来源：http://dali.sweek.top/Article/details/gtzhsflxwr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cdnleiting.top/Article/details/gteqxoohvo.html

[Q82] 字符长度与字节长度
来源：http://dali.snrcjt.cn/Article/details/gtycfmnbzf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtgjmvgkdf.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtmnjkbvgz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtsptnixvu.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gtnqwcycwe.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtdgnrgkjo.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtilrexgjj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hfpthk.cn/Article/details/gtjeyxokpw.html

[Q86] 读取 JSON 字段
来源：http://dali.chenlongwang.top/Article/details/gtxzldnebg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gtgtfsvidn.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gtzpciemai.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jiagoushi.top/Article/details/gthaxhzcqe.html


<!-- 参考信息 -->