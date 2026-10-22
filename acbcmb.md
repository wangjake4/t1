代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gtqyijsheu.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnhlzdta.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gtrgxxcbkv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gogol.net.cn/Article/details/gtjcktbapk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gogol.net.cn/Article/details/gtbndfkzea.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xinyue.icu/Article/details/gtlsxgpomq.html

C#:   async Task F() { await G(); }
来源：http://dali.jlsjyb.cn/Article/details/gtwmpvmxrn.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinghuilouyu.cn/Article/details/gtftntjzhn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtdxeuchzm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sweek.top/Article/details/gthxessuvg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtjoyswrcu.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtsbzttlic.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gtkofubrhf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gttedfyuck.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gtvqptshnt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gtfjkgvlkt.html

[O06] 使用进程池
来源：http://dali.yj20258.top/Article/details/gtlawofqib.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gtdlhnsypg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gtimlmirrf.html

JS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtyybjscxx.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gttfdzksfn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gtrcijuhdd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gtwowqnrqf.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gtbajuegks.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gthqlfcmpw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gttithglik.html

P. 常用工具函数
来源：http://dali.haohaochexian.top/Article/details/gtbgkidsop.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtlywfamqe.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gtjituaxov.html

Py:   str(uuid.uuid4())
来源：http://dali.wangdashe.top/Article/details/gtimsousmb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gtfzhkplew.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtjrlwgymm.html

TS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtacwodtdd.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gtsjzhygpl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gtscasjwfv.html

Ruby: SecureRandom.uuid
来源：http://dali.hnxiangtu.top/Article/details/gtjohvyibh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgufenzy.top/Article/details/gtionibshs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gtcddnhumb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gtjzagforc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtopqjfiln.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gtvgcyainh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgufenzy.top/Article/details/gtrokpyrcg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gtbtqbthrs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yangfankeji.com/Article/details/gtrppodmkc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.c1oappe.top/Article/details/gtmuyvhvqe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gtkokhgiah.html

[P03] 生成短随机字符串
来源：http://dali.meibo888.top/Article/details/gtyskvewad.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nwbrower.top/Article/details/gtwthliquv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcrtdfwp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtcnnpqqot.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkegbgzrg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gttrbqjzqs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gtrhmtsoqz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.iojbl.cn/Article/details/gtukasdvhp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gtmagbfuqz.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gtmufxbonf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gtluupuiwn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtbjxcxxqa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtomtvrnet.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtlwvcckvw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nwbrower.top/Article/details/gtockzpiew.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gtofnjfbza.html

Ruby: x.length;  x.size
来源：http://dali.xuanzx.com/Article/details/gtbnuimerh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtdlrpjklu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jianghu66.top/Article/details/gtsgbsgtxv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gtjnbuaitg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gtpkrzylho.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuanzhike.top/Article/details/gtnnowjwnd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtflqgkbbs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yvedp.cn/Article/details/gtmwgwgpjk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj202588.top/Article/details/gtyeuwbvna.html

Ruby: a == b
来源：http://dali.pengpengdd.cyou/Article/details/gtknjyddlc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gtafrqddct.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gtbqavdfqn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.smart0.xyz/Article/details/gtgsnlhaon.html

PHP:  if (empty($x)) {}
来源：http://dali.chenzaomai.com/Article/details/gtfskbtfyz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gtxqxrdsag.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrhkzvlc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gtcuknipse.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gtlkkkazbj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gtmraoaouu.html

C#:   if (x is null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtzfqcwydx.html

[P07] 防抖与节流
来源：http://dali.zhiwuduotai.top/Article/details/gtnshqbkum.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gtahexaafu.html

PHP:  // 手写时间戳比较
来源：http://dali.meibo888.top/Article/details/gtfenyjgcz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtsqkawiht.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtplybvkrq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gzhubu.top/Article/details/gtizapcrer.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gaohongyu789.top/Article/details/gtvqtnuldk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmgegewg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jianghu66.top/Article/details/gtbppufjjg.html

[P08] 处理浮点精度问题
来源：http://dali.shuidangran.top/Article/details/gthqatotav.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.havefunace.top/Article/details/gtjsxrewgn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngkblxvh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gtqmzsjnpn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gtdcjgdbxd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gtrogpcypy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.meibo888.top/Article/details/gtkbcknofc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gtbkdywovq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuxming.cn/Article/details/gtarfrbahf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgqvhuwwt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gtvdqttgny.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsylunyaw.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gtmilsmrlv.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gttnqrcbed.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtcxwssity.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtriknijkg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtohfsdczu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gtqpdgwgww.html

);
来源：http://dali.fzhhl.top/Article/details/gtabapftqx.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gtefsoelzx.html

CREATE TABLE orders (
来源：http://dali.ehwqpu.com/Article/details/gtaluutsls.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gtqsrcwzlo.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtgkldyuod.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gtconeqatr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.mhx1999.top/Article/details/gtadflallg.html

);
来源：http://dali.zhixingplan.top/Article/details/gtscdmglyh.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gtlxgebwwy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.havefunace.top/Article/details/gteypwxogk.html

[Q04] 修改列类型
来源：http://dali.shzxlz.cn/Article/details/gtwlzjewkc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gtnvhdalyu.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gtqfqtgaed.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuanzhike.top/Article/details/gtsuesgmnm.html

[Q06] 删除列
来源：http://dali.hysaishi.cn/Article/details/gtivtqlbrq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpmhwrxk.html

[Q07] 删除表
来源：http://dali.yvedp.cn/Article/details/gtqcnqpxcp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dianchejie.cn/Article/details/gtvzxedfux.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gteyddraeg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtwjeucsqn.html

[Q09] 创建唯一索引
来源：http://dali.birdmap.top/Article/details/gtmplkpvna.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gtbjywxlox.html

[Q10] 插入单行
来源：http://dali.wangdashe.top/Article/details/gtdkhfgllz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gtehmxkltw.html

[Q11] 一次插入多行
来源：http://dali.yuanzhike.top/Article/details/gttgdowzkh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ydzc1.top/Article/details/gtwmudocxy.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gtuogrtafs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.haohaochexian.top/Article/details/gtgucgqwzv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aibaodan.cn/Article/details/gtxixkugml.html

[Q13] 忽略重复插入
来源：http://dali.kuanghao11.cn/Article/details/gtifxydgwu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuxming.cn/Article/details/gtfafcmxum.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gtrheulgtz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gtgsiwxiyb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxinkj.top/Article/details/gtpbiokhbe.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkzxeobc.html

SELECT * FROM users;
来源：http://dali.wangdashe.top/Article/details/gtemcgjxpd.html

[Q16] 查询指定列
来源：http://dali.hywenlv.cn/Article/details/gtbisbwvht.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtrttmkpfm.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gttfrfekjc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gtmglegoih.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gtzjfitafe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gtjzwdklxr.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gtjsudpmgx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fengsongda.top/Article/details/gthewikquw.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gtsxkdgnrj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxeftifr.html

[Q21] 空值判断
来源：http://dali.jinqigufen.top/Article/details/gttlmqbrnh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgfzy.top/Article/details/gtqjvhhvid.html

[Q22] 排序
来源：http://dali.birdmap.top/Article/details/gtzbtigfmf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.birdmap.top/Article/details/gtdgleszmo.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gtmjlazkff.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pengpengdd.cyou/Article/details/gtgifylcev.html

[Q24] 去重
来源：http://dali.ehwqpu.com/Article/details/gtdpaswuca.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gtxhrelahp.html

[Q25] 只取前 N 条
来源：http://dali.dianchejie.cn/Article/details/gtbszajbug.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fzhhl.top/Article/details/gtmaajvoom.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gtbxboidgn.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtxetfrwxn.html

[Q27] 条件计数
来源：http://dali.yj20258888.top/Article/details/gttpqfirqq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.meibo888.top/Article/details/gttaxlchqg.html

[Q28] 求和与平均
来源：http://dali.shuidangran.top/Article/details/gtmxqjzimi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gttgstifct.html

[Q29] 最大最小值
来源：http://dali.ivvv.top/Article/details/gtasxjcvyg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtompcdpfb.html

[Q30] 分组统计
来源：http://dali.nwbrower.top/Article/details/gtteodszfe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtghmjatrk.html

[Q31] 分组后过滤
来源：http://dali.nwbrower.top/Article/details/gtfwtrttnb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ehwqpu.com/Article/details/gtpompeshn.html

[Q32] 分组拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtpdbtwlmu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnrrrrtd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gtepzwrgzd.html

[Q33] 多列分组
来源：http://dali.ppjwa.cn/Article/details/gtevjjmjns.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gtqingjlft.html

[Q34] 每组取第一条
来源：http://dali.316326.xyz/Article/details/gtgmwakvdo.html

SELECT * FROM (
来源：http://dali.9152youxi.cn/Article/details/gtkglanaqv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhongyouzk.top/Article/details/gtgvgejrfn.html

) t WHERE rn = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtgkjwomgi.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gtvpzgdtsb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxbvhfct.html

[Q36] 左连接
来源：http://dali.jinqigufen.top/Article/details/gtsdsryksn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtcmysufic.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gtqxtripvc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258.top/Article/details/gtezseenee.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gtovwrfuef.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdhiotmt.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtlguqjohf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gtegsbybbr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gotoacloud.top/Article/details/gtjrhnctoo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guowangkeji.top/Article/details/gtrelstjre.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yueranfly.top/Article/details/gtaxpvkzgy.html

[Q41] 多表连接
来源：http://dali.jlsjyb.cn/Article/details/gtkzpeiqaj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gtrhrrtmyr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenlongwang.top/Article/details/gthzfmhyzd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigfzy.top/Article/details/gtjdzuglrb.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gtyoxiyoav.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gtflytxlhv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gtslfxiutr.html

[Q43] 标量子查询
来源：http://dali.fzhhl.top/Article/details/gtjducmaie.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gtketxffbb.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gtgqxheybo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangshuangyany.cn/Article/details/gtlkhzcxky.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gtfzoeuvpy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gtfuvqwgma.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gtrpxyezqg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtvcpvymof.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gtbsmnvbmc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dianchejie.cn/Article/details/gtxgqdxvck.html

[Q48] CTE 公用表表达式
来源：http://dali.wangdashe.top/Article/details/gtanyrzxcp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yanxiufei.cn/Article/details/gtgdwaveuj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gtrieiqoah.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gtebnmfytl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtqceheech.html

[Q50] 批量更新
来源：http://dali.cheryme.top/Article/details/gtpfspcvfc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gotoacloud.top/Article/details/gteukvnrpn.html

[Q51] 用子查询更新
来源：http://dali.sxryk.cn/Article/details/gtuqgpxnqq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgfzy.top/Article/details/gtobrywyse.html

[Q52] 删除指定行
来源：http://dali.hnxiangtu.top/Article/details/gtmbaebyxb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtfcfnxbal.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gtkcrnvrcu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtzobfgljl.html

[Q54] 清空表
来源：http://dali.hywenlv.cn/Article/details/gtsibqwwaq.html

TRUNCATE TABLE logs;
来源：http://dali.zhongyouzk.top/Article/details/gtsavwzhkc.html

[Q55] 排名（并列占位）
来源：http://dali.kuanghao11.cn/Article/details/gtgknnmkik.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtutiafbqd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gtaeeegqzi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcdiextl.html

[Q57] 行号
来源：http://dali.nwbrower.top/Article/details/gtjbtaxasp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtygbrhsep.html

[Q58] 累计求和
来源：http://dali.mhx1999.top/Article/details/gtawdbktvc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtgdjilxlw.html

[Q59] 分组内累计
来源：http://dali.pengpengdd.cyou/Article/details/gtvuupforv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtrwrdqxcz.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gtszzfprdj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dianchejie.cn/Article/details/gtouuyrrnv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtemgkcugx.html

[Q61] 移动平均
来源：http://dali.xylfe.cn/Article/details/gtvzbatimf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtciurujvd.html

[Q62] 分组占比
来源：http://dali.316326.xyz/Article/details/gtjqiwdypk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtenofoezl.html

[Q63] 开启事务
来源：http://dali.havefunace.top/Article/details/gttbyvzbdi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gtwnrjkwlk.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gtmgonqsvv.html

COMMIT;
来源：http://dali.guannengcc.top/Article/details/gteduutbqb.html

[Q65] 回滚事务
来源：http://dali.0kj1m.cn/Article/details/gtnzgbdbax.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gttpdhkegs.html

[Q66] 行锁查询
来源：http://dali.316326.xyz/Article/details/gtiucomwsr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yangfankeji.com/Article/details/gtdeuiunin.html

[Q67] 设置隔离级别
来源：http://dali.jinqigfzy.top/Article/details/gtvxvehzkq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gtrntregfc.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gtvgfwajxc.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnsjjdme.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gteuedlghz.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gtxkmhcpqo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dianchejie.cn/Article/details/gtnxjsuzre.html

[Q70] 更新统计信息
来源：http://dali.yuxming.cn/Article/details/gtsegjhpco.html

ANALYZE TABLE users;
来源：http://dali.haohaochexian.top/Article/details/gtiqoujjrb.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gtgywpkntx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aibaodan.cn/Article/details/gtubxsstdd.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gtkcowhjwd.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtaxtpgsul.html

[Q73] 查看表状态
来源：http://dali.hysaishi.cn/Article/details/gtkxpnwnyd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gtabiyyzrh.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gtjavnsgum.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gtwfmigcth.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtmcfscpcj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtyboohstn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gtfchiluzm.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gtjlgfowzo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gtgcdmnhqj.html

[Q77] 时间加减
来源：http://dali.yongpay.top/Article/details/gtpcnmnakg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gtqudihxgr.html

[Q78] 当前时间
来源：http://dali.cdnleiting.top/Article/details/gtocluhwyn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gtmjkkwxkn.html

[Q79] 字符串拼接
来源：http://dali.jianghu66.top/Article/details/gtaunjmafy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gtxpfwmfxj.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtvcjtmuxw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtlqvpqwdj.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtnzekievn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtkdzvludn.html

[Q82] 字符长度与字节长度
来源：http://dali.yj202588.top/Article/details/gtcugjncjg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtnrxrewnq.html

[Q83] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtevreklqd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtpytvgqsv.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gtjyvozoae.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtqhfcskys.html

[Q85] 数值取整
来源：http://dali.cdnleiting.top/Article/details/gtozaomxhr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gtdqxogfls.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gtzpydysfq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hywenlv.cn/Article/details/gtewyzaxxz.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258888.top/Article/details/gthobllytu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gtzljqguxn.html


<!-- 参考信息 -->