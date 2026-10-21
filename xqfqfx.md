代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gtvpfcfeik.html

JS:   async function f() { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtrwdxggrz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtizeobwst.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ivvv.top/Article/details/gtzpoksipd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvaftgjh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gtxxucsvom.html

C#:   async Task F() { await G(); }
来源：http://dali.fzhhl.top/Article/details/gtamnfuafp.html

[O05] 并发执行并等待全部完成
来源：http://dali.gotoacloud.top/Article/details/gtmggaxikr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gtlwvkpihs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guannengcc.top/Article/details/gtgyokpeck.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtkkpmryrq.html

TS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gtneiutuij.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gtrajkqbcw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cheryme.top/Article/details/gtjymrdpdp.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtgsbkkaqv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenlongwang.top/Article/details/gtpcgafiwk.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gtsgwaldvu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gtjerdxmoq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangdashe.top/Article/details/gtedvayrhh.html

JS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gtzowiuqnl.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtwnecento.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gtjafalool.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gtizpdhvyo.html

Ruby: // fork 块
来源：http://dali.pengpengdd.cyou/Article/details/gtvqyrehip.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gtsaffgvte.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtjygryvzz.html

P. 常用工具函数
来源：http://dali.hongshengwenyu.top/Article/details/gtoahldvlv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtushcsvoa.html

[P01] 生成 UUID
来源：http://dali.shuidangran.top/Article/details/gtgllfcaxm.html

Py:   str(uuid.uuid4())
来源：http://dali.zhoulong.xyz/Article/details/gtvfopcscv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gtgsfkzuta.html

JS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtxkooixns.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gttqomwpuh.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gtmjeiphzv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gtxkrxwfzg.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gtjruofspw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozdmjnwp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sxryk.cn/Article/details/gtkbulhojv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guowangkeji.top/Article/details/gtavvbpnwn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gtfkabmuwx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gtezdvcbwt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gogol.net.cn/Article/details/gtcajjdhje.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtuerjoruv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yonumen.top/Article/details/gtokjkshbu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gtboahesjc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gtjpzqeoee.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gtqlfqrsvt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gtsipvbbbm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gthlwuutdk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvtmtgff.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtasinlhwo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258.top/Article/details/gteamnhwfo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daria6918.cn/Article/details/gtnkisafqf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ydzc1.top/Article/details/gtoatilswl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gtpezykpup.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gtdlmutulk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gttpxzpavm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtewoawkyh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtgjxtzeam.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gtnmhtkffh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.c1oappe.top/Article/details/gtytchpmhe.html

Go:   len(arr);  len(m)
来源：http://dali.zhiwuduotai.top/Article/details/gttmtuyjhz.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gtgzyasoig.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gtkqekvtor.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fzhhl.top/Article/details/gtpjmluszk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvuahterp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gtlyhfqyml.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guowangkeji.top/Article/details/gtzyqohdvr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gtvtwmkgcl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenlongwang.top/Article/details/gtqwozbsbp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtteclmtcw.html

Ruby: a == b
来源：http://dali.yueranfly.top/Article/details/gtrcimqriv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gtmocvehsj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gtizlgcxzv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daxiang520.top/Article/details/gtivanjhbp.html

PHP:  if (empty($x)) {}
来源：http://dali.tianlin.xyz/Article/details/gtkfwpbxok.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuanzhike.top/Article/details/gtnvrgursd.html

TS:   if (x == null) {}
来源：http://dali.xylfe.cn/Article/details/gtjrwcxbct.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtxgxzwanp.html

Go:   if x == nil {}
来源：http://dali.ydzc1.top/Article/details/gtdntvophk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnxiangtu.top/Article/details/gtkeoruxpc.html

C#:   if (x is null) {}
来源：http://dali.ehwqpu.com/Article/details/gtwyrjohhk.html

[P07] 防抖与节流
来源：http://dali.jlsjyb.cn/Article/details/gthslpzxsv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gtundkqeje.html

PHP:  // 手写时间戳比较
来源：http://dali.cucudq.cn/Article/details/gtuqssnfls.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtwaijpbgd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtpihxvulc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gturhqhrcz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yvedp.cn/Article/details/gtvlrknpdx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnujbobzz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhixingplan.top/Article/details/gtddakpigl.html

[P08] 处理浮点精度问题
来源：http://dali.kuanghao11.cn/Article/details/gtpwszxylw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpnuhynh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.haohaochexian.top/Article/details/gtbpzxcfoe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gtbonnkela.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtaysgbbdw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.316326.xyz/Article/details/gtxazjdvre.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gtupoidybo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.316326.xyz/Article/details/gtibpqqewg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gtdtqxgfgn.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtzsedqwwr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fzhhl.top/Article/details/gtmwufkges.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtrcobeuyz.html

[Q01] 创建表
来源：http://dali.hnxiangtu.top/Article/details/gtekqzobgo.html

CREATE TABLE users (
来源：http://dali.birdmap.top/Article/details/gtxqwgcxtc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtgallxpbn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtocyzefxh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gtbuwrmivy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.kuanghao11.cn/Article/details/gtvxwdbmdv.html

);
来源：http://dali.0kj1m.cn/Article/details/gtahkdqfll.html

[Q02] 创建带外键的表
来源：http://dali.redwolf501.top/Article/details/gtuzeewtku.html

CREATE TABLE orders (
来源：http://dali.xuanzx.com/Article/details/gtseduwrjf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gthsxnfgpp.html

user_id INT NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gtuvfydxku.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gtznlxvvfv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenlongwang.top/Article/details/gteafhaiwg.html

);
来源：http://dali.ivvv.top/Article/details/gtngmvgjwq.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gtmoqivpro.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gtqzhsjato.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdtmtybn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xylfe.cn/Article/details/gtwcwizbwj.html

[Q05] 重命名列
来源：http://dali.chenlongwang.top/Article/details/gtkfxyhgki.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gtbyqvnhvd.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gtzfeboiff.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.c1oappe.top/Article/details/gtsyqnwthu.html

[Q07] 删除表
来源：http://dali.nwbrower.top/Article/details/gtsycvxjfs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gotoacloud.top/Article/details/gtuwucsrjc.html

[Q08] 创建普通索引
来源：http://dali.chenzaomai.com/Article/details/gtenrgohtn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtiduwldcg.html

[Q09] 创建唯一索引
来源：http://dali.zdqjudy.top/Article/details/gtunwwzuur.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtpgwtpxeo.html

[Q10] 插入单行
来源：http://dali.nanxuanxn.top/Article/details/gttuvyjhtd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqyurdth.html

[Q11] 一次插入多行
来源：http://dali.smart0.xyz/Article/details/gtokythgpz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gtlhhqtbdb.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gthukbiscw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shzxlz.cn/Article/details/gtjhthnxdk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shangyingyoupin.top/Article/details/gtyqcofzlf.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gtgpfkbpsl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtswpdcknj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhiwuduotai.top/Article/details/gtypqvexzg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ydzc1.top/Article/details/gtffakuyyq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenjidiqi.icu/Article/details/gtfodzpboq.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gtrnvghnfn.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemotopor.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gtkbuzotde.html

SELECT id, name FROM users;
来源：http://dali.xuanzx.com/Article/details/gtfynmhvdd.html

[Q17] 条件查询
来源：http://dali.tian-w.cn/Article/details/gtkkgvzbuq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtogpxymby.html

[Q18] 模糊匹配
来源：http://dali.smart0.xyz/Article/details/gtwwvldvpc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhuoyrfs.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gtirikuywn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gtszmewjkk.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gtjlpecrta.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gtbvdiwxyu.html

[Q21] 空值判断
来源：http://dali.fzhhl.top/Article/details/gttrijitsr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtxbexvnyc.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gtlaibjdkh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nwbrower.top/Article/details/gtyeawutud.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gtbuntoaxw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zycfv.cn/Article/details/gtcfjwkogu.html

[Q24] 去重
来源：http://dali.aibaodan.cn/Article/details/gtwfwwzbmv.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtwyimdtrh.html

[Q25] 只取前 N 条
来源：http://dali.smart0.xyz/Article/details/gtrjfeibys.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.0kj1m.cn/Article/details/gtyqtgrpqy.html

[Q26] 计数
来源：http://dali.pycfn.com/Article/details/gttfyqpefk.html

SELECT COUNT(*) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtnjsmfsjm.html

[Q27] 条件计数
来源：http://dali.ydzc1.top/Article/details/gtpjaxtxie.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258888.top/Article/details/gtmhqzadbj.html

[Q28] 求和与平均
来源：http://dali.tianlin.xyz/Article/details/gtvkmuvqaj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtbdadkpbu.html

[Q29] 最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gthhtwamts.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtkikdcytp.html

[Q30] 分组统计
来源：http://dali.316326.xyz/Article/details/gtuiyrpxna.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtlszvyibg.html

[Q31] 分组后过滤
来源：http://dali.zhongyouzk.top/Article/details/gtgypglgcc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zdqjudy.top/Article/details/gttawpmmff.html

[Q32] 分组拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtnbjrtkrf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gthkanikef.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgfzy.top/Article/details/gtvdputfxg.html

[Q33] 多列分组
来源：http://dali.mhx1999.top/Article/details/gtihpsxbqq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gttljfivwo.html

[Q34] 每组取第一条
来源：http://dali.wangshuangyany.cn/Article/details/gttdutrdxj.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gtnaawqhbq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hywenlv.cn/Article/details/gtdlktkneo.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzerciqi.html

[Q35] 内连接
来源：http://dali.shangyingyoupin.top/Article/details/gtechmwfvy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtcmakjbsx.html

[Q36] 左连接
来源：http://dali.yvedp.cn/Article/details/gtmmwljara.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtvxxedwny.html

[Q37] 右连接
来源：http://dali.gzhubu.top/Article/details/gtgneutvrl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gtijfnxbtj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.bjfxy.top/Article/details/gtnbjmatrx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gtmjrewmyl.html

[Q39] 自连接（查上下级）
来源：http://dali.yonumen.top/Article/details/gttrumrpbg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.mhx1999.top/Article/details/gtjtgqtvkt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gtwrwqpylk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yueranfly.top/Article/details/gtcsrhaqhe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ybcxt.top/Article/details/gtfhsoomhn.html

[Q41] 多表连接
来源：http://dali.tianlin.xyz/Article/details/gtglmhjosc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ppjwa.cn/Article/details/gtuegbbcla.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guowangkeji.top/Article/details/gtsxccpisl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.0kj1m.cn/Article/details/gtdjpyppyp.html

[Q42] 连接条件附加过滤
来源：http://dali.cucudq.cn/Article/details/gtqaetuckf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtggxcmesl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gtgiprtieg.html

[Q43] 标量子查询
来源：http://dali.zhengqikj.top/Article/details/gtrwonocue.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.quarkkingdee.top/Article/details/gtdfpuqxrf.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gtgxzvxzbu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gtkcncyyri.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gtoeoalxgh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtswuvbtxv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtwlxyxrxt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtccpjjayt.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gthhovrbzw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gtetullkhk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrftiwna.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gtkhtaxsdn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhiwuduotai.top/Article/details/gtcphvuydr.html

[Q49] 更新单行
来源：http://dali.0kj1m.cn/Article/details/gtmntxfneo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtfrcixrpx.html

[Q50] 批量更新
来源：http://dali.pengpengdd.cyou/Article/details/gtxygjoesv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.iojbl.cn/Article/details/gtrusrwqip.html

[Q51] 用子查询更新
来源：http://dali.feifeiyinyue.top/Article/details/gturwwvaph.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ivvv.top/Article/details/gtzrxtinyr.html

[Q52] 删除指定行
来源：http://dali.ydzc1.top/Article/details/gtlsavoaeo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtshgbulzy.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gtjzxowqdq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtuusrgnxg.html

[Q54] 清空表
来源：http://dali.0kj1m.cn/Article/details/gtaubffyom.html

TRUNCATE TABLE logs;
来源：http://dali.zhixingplan.top/Article/details/gtsfqegtrf.html

[Q55] 排名（并列占位）
来源：http://dali.pengpengdd.cyou/Article/details/gtyulpdyuk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gtdwtncpbl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zdqjudy.top/Article/details/gtijzxsrnf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtrhrhqijx.html

[Q57] 行号
来源：http://dali.jqgufenzy.top/Article/details/gtlmjrjdrt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtqdlvdbpq.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiwvkwgb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtfcgoqqgr.html

[Q59] 分组内累计
来源：http://dali.nanxuanxn.top/Article/details/gtgitrpbej.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gthbmdcbin.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gtdyywwlmh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daxiang520.top/Article/details/gtyothtqsk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtrnzgdikb.html

[Q61] 移动平均
来源：http://dali.shangyingyoupin.top/Article/details/gttpqjqisk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gthmxkhbeq.html

[Q62] 分组占比
来源：http://dali.gogol.net.cn/Article/details/gtbzcbjmbm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtelpqvsbh.html

[Q63] 开启事务
来源：http://dali.tanke756.top/Article/details/gtxggmphcp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hfpthk.cn/Article/details/gtjfmznemr.html

[Q64] 提交事务
来源：http://dali.zhixingplan.top/Article/details/gtckxpggpu.html

COMMIT;
来源：http://dali.svipenyu.cn/Article/details/gtxotoimzp.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gtklwlbwtp.html

ROLLBACK;
来源：http://dali.shangyingyoupin.top/Article/details/gtbzgsmacl.html

[Q66] 行锁查询
来源：http://dali.zycfv.cn/Article/details/gtmkzujcho.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gtjifwyoss.html

[Q67] 设置隔离级别
来源：http://dali.redwolf501.top/Article/details/gtvohblxvr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gtwislrggs.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gteemmapnv.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gtvagocyni.html

ROLLBACK TO sp1;
来源：http://dali.birdmap.top/Article/details/gtqobexyft.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gtzmalystr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.redwolf501.top/Article/details/gtxchgpaqz.html

[Q70] 更新统计信息
来源：http://dali.feifeiyinyue.top/Article/details/gteblhbdhv.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gteqzmjyql.html

[Q71] 查看建表语句
来源：http://dali.chenlongwang.top/Article/details/gtaksdtqgr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gtplrjvzpg.html

[Q72] 查看索引
来源：http://dali.0kj1m.cn/Article/details/gtovenleih.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtlaruhlvy.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gtodfrhwah.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gttpzprxsm.html

[Q74] 强制使用索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakcoxptw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gtemchesvu.html

[Q75] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtaszfbuci.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtsdssjjbc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gtpzxlatet.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gthgirrygl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gtgwclbatx.html

[Q77] 时间加减
来源：http://dali.zhengqikj.top/Article/details/gtiywrbjil.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gtznqmhrns.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhfkmfrn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.havefunace.top/Article/details/gtmptfcoyq.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gthcezmljl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxinkj.top/Article/details/gtricalgof.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gtnishqufu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtgfdaedol.html

[Q81] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gtrrltmsbx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ehwqpu.com/Article/details/gthufqxmha.html

[Q82] 字符长度与字节长度
来源：http://dali.gogol.net.cn/Article/details/gthixawauf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtbbmtscfa.html

[Q83] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtabncqshp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtgiuqruqh.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gtnvksvkza.html

SELECT TRIM(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtvdsdawlh.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gtxijhuzer.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nwbrower.top/Article/details/gtnclhrjtg.html

[Q86] 读取 JSON 字段
来源：http://dali.yonumen.top/Article/details/gtstlvuhhm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hywenlv.cn/Article/details/gtahsehqlm.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gtryoanvep.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gtawqzhamu.html


<!-- 参考信息 -->