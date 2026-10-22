代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aibaodan.cn/Article/details/gt2hlzadkky.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gt2ujlofwfj.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gt2ckkzkpey.html

Py:   async def f():⏎    await g()
来源：http://dali.cdnleiting.top/Article/details/gt2ovkzyatz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhengqikj.top/Article/details/gt2snbfrbmd.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmhfjai.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gt2gtbgmpxx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jyoumei.cn/Article/details/gt2ypcowkgl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hlmmjqja.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipnuihrk.html

C#:   async Task F() { await G(); }
来源：http://dali.0kj1m.cn/Article/details/gt2iwocsbhk.html

[O05] 并发执行并等待全部完成
来源：http://dali.daxiang520.top/Article/details/gt2fcweamno.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxinkj.top/Article/details/gt2xlfxvsbq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shuidangran.top/Article/details/gt2fjtbgnwz.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjlcvgdo.html

TS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gt2hgavwlzn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gt2jrmwcvkb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gt2gtgakthy.html

Ruby: threads.map(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gt2hknbomtg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gt2cqmxitte.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gt2enxnubnd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gt2iynurobr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbaajdwe.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkpspgls.html

TS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gt2mukleaza.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guannengcc.top/Article/details/gt2gianefil.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuanzhike.top/Article/details/gt2ylghdvfc.html

Ruby: // fork 块
来源：http://dali.nwbrower.top/Article/details/gt2abnvilet.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gt2mjshlzya.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2epbringd.html

P. 常用工具函数
来源：http://dali.hammf.cn/Article/details/gt2cqpdvuyz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2qkndllqg.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gt2oagfxxmn.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iuofyivm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gt2ujvbetga.html

JS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gt2exiyhonu.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gt2blbrbckt.html

Java: UUID.randomUUID().toString()
来源：http://dali.yueranfly.top/Article/details/gt2iisrtbaf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnxiangtu.top/Article/details/gt2tpstfjhg.html

Ruby: SecureRandom.uuid
来源：http://dali.andypj.xyz/Article/details/gt2dgzckiak.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gt2ulahbulg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gt2srlxxbuk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.snrcjt.cn/Article/details/gt2obrssiho.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gt2unmemwlu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.redwolf501.top/Article/details/gt2bhjbiszd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dianchejie.cn/Article/details/gt2lgcdvjni.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gt2svgdhkod.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gt2hjqtjxdx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gt2rszqweyv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gt2fkjpzmbu.html

[P03] 生成短随机字符串
来源：http://dali.ehwqpu.com/Article/details/gt2uvctiydc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gt2dvpjivjq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbpsvegv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gt2xengnoil.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gt2oukgeahb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zycfv.cn/Article/details/gt2plvfxdax.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gt2vnkvffzk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenzaomai.com/Article/details/gt2ttryzhif.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jianghu66.top/Article/details/gt2vpnkoqgn.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gt2onppovpk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvbluzxi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2bntigspb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gt2hwuiuujx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gt2fbogbwxz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gt2gtdngzex.html

Go:   len(arr);  len(m)
来源：http://dali.gaohongyu789.top/Article/details/gt2dwpimdvd.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gt2vjqckbql.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvlwzldu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hysaishi.cn/Article/details/gt2iigeuajv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.316326.xyz/Article/details/gt2jorizpcx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ydzc1.top/Article/details/gt2tzcgrdto.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gt2bxabpuxk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gt2pvjrqgkr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hywenlv.cn/Article/details/gt2bsytcrhj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2pjusxnhy.html

Ruby: a == b
来源：http://dali.snrcjt.cn/Article/details/gt2ykjrjiwv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.meibo888.top/Article/details/gt2liswhnbo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cthceuht.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hnqzz.top/Article/details/gt2tjzjeaqm.html

PHP:  if (empty($x)) {}
来源：http://dali.xuanzx.com/Article/details/gt2sfqhaovc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gt2ikgatbik.html

TS:   if (x == null) {}
来源：http://dali.fengsongda.top/Article/details/gt2rfvraahn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gt2ujegwvey.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2drdacdls.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gt2wvqbruol.html

C#:   if (x is null) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2rzpssvdx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2sexzgwnr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cashguo.top/Article/details/gt2mbqwzepv.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgfzy.top/Article/details/gt2aczuprtq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gt2mmnbixuu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsojtneh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jyoumei.cn/Article/details/gt2ylmuezmh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gt2lrbdthkf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.bjfxy.top/Article/details/gt2osmbyvox.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gt2naqxcjju.html

[P08] 处理浮点精度问题
来源：http://dali.hnqzz.top/Article/details/gt2ocjfpvix.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zdqjudy.top/Article/details/gt2yoiruqmw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.0kj1m.cn/Article/details/gt2wdzhzqwy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jlsjyb.cn/Article/details/gt2hrgwwpte.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmdrlwwy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gt2xxwmgvzw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhnvyyia.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffhwogxv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.vqdsnc.cn/Article/details/gt2doorurmz.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2vumpvcug.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gt2jnueiaum.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2zjmblbgm.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gt2nztisomc.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gt2wbtvqaaj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gt2xlxjddds.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gt2iyeiakmw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ditmtdix.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.vqdsnc.cn/Article/details/gt2axmhcytf.html

);
来源：http://dali.shzxlz.cn/Article/details/gt2crirlosj.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gt2sicinytk.html

CREATE TABLE orders (
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvbqegmg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gt2ypwoejhk.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gt2tzghqklc.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gt2ltrqicld.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ppjwa.cn/Article/details/gt2lvmeupzv.html

);
来源：http://dali.yj20258888.top/Article/details/gt2cjgoyaea.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gt2ziqqqaub.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnxiangtu.top/Article/details/gt2qetomctg.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gt2pbodkcir.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gt2drxnuwvi.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gt2cibrebor.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gt2ssbrovpd.html

[Q06] 删除列
来源：http://dali.yj202588.top/Article/details/gt2tbwkttvs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hywenlv.cn/Article/details/gt2glqjysux.html

[Q07] 删除表
来源：http://dali.wangshuangyany.cn/Article/details/gt2fufxwrot.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hfpthk.cn/Article/details/gt2iwdyfksi.html

[Q08] 创建普通索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2znzqvfme.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gt2euozylua.html

[Q09] 创建唯一索引
来源：http://dali.cashguo.top/Article/details/gt2iovfvpnh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gt2yrkyszji.html

[Q10] 插入单行
来源：http://dali.meibo888.top/Article/details/gt2gwfhtzlk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gt2edntrddj.html

[Q11] 一次插入多行
来源：http://dali.xuetiantiany.cn/Article/details/gt2ptwguarf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrzyyoha.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gt2zarqbykl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gaohongyu789.top/Article/details/gt2lvbjdmro.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hammf.cn/Article/details/gt2fsgywozm.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gt2fzueajbt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2brbozbay.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gt2johmokcv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenjidiqi.icu/Article/details/gt2qggniede.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guannengcc.top/Article/details/gt2qjyggpuh.html

[Q15] 查询全部
来源：http://dali.nanxinkj.top/Article/details/gt2abhgeyzj.html

SELECT * FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2quuwxmeb.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gt2jkwjydzs.html

SELECT id, name FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ebafyknx.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gt2phspxpni.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2jjyavtou.html

[Q18] 模糊匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2ijfqrvvg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jyoumei.cn/Article/details/gt2vsaxuras.html

[Q19] 范围查询
来源：http://dali.0kj1m.cn/Article/details/gt2osltzkio.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gt2tqpnaunp.html

[Q20] IN 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afbdfcyr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cheryme.top/Article/details/gt2xguypahh.html

[Q21] 空值判断
来源：http://dali.hnxiangtu.top/Article/details/gt2bngxhkee.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.0kj1m.cn/Article/details/gt2nahegoig.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gt2amjlzdmp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gt2icrcicpr.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gt2zqmkxugl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hfpthk.cn/Article/details/gt2nqbdunrh.html

[Q24] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gt2pacykfhf.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gt2yjbqldcq.html

[Q25] 只取前 N 条
来源：http://dali.quarkkingdee.top/Article/details/gt2aiiabgxa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj202588.top/Article/details/gt2gtixpqxo.html

[Q26] 计数
来源：http://dali.zhoulong.xyz/Article/details/gt2sfqvkydn.html

SELECT COUNT(*) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2iyllrvbw.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwdrcjyo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yonumen.top/Article/details/gt2trpamwns.html

[Q28] 求和与平均
来源：http://dali.sweek.top/Article/details/gt2sjdwoyop.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2qmujzqzl.html

[Q29] 最大最小值
来源：http://dali.aizwys.cn/Article/details/gt2jvdclnqy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2tuvrwnpe.html

[Q30] 分组统计
来源：http://dali.meibo888.top/Article/details/gt2dyjvofel.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gt2ipqqnvhu.html

[Q31] 分组后过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2dgfzvavi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jkunehnp.html

[Q32] 分组拼接字符串
来源：http://dali.jianghu66.top/Article/details/gt2vuxbwkwx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2mforkalw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gt2uepyecaq.html

[Q33] 多列分组
来源：http://dali.xuanzx.com/Article/details/gt2slncrtsj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkhdapk.html

[Q34] 每组取第一条
来源：http://dali.hammf.cn/Article/details/gt2wzrvszvo.html

SELECT * FROM (
来源：http://dali.yj20258888.top/Article/details/gt2uqwwanax.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gt2tjaebjje.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2mhcdfoch.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gt2ziwsoosh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gt2bevffedb.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gt2mjintgaf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gt2ptsrnayj.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gt2fmpgckdt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.haohaochexian.top/Article/details/gt2mjbpsibf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.haohaochexian.top/Article/details/gt2mdphauhy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tianlin.xyz/Article/details/gt2bqqfqdzd.html

[Q39] 自连接（查上下级）
来源：http://dali.yvedp.cn/Article/details/gt2vbahsgas.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.birdmap.top/Article/details/gt2sgiflqsd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gt2pvrwncek.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywfpamwe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guannengcc.top/Article/details/gt2oeeeabyo.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gt2zxhavzvy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jyoumei.cn/Article/details/gt2ikacdvcq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guowangkeji.top/Article/details/gt2huozrzbw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gt2hmopbrwq.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gt2kafepsde.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gt2hauyeldg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tianlin.xyz/Article/details/gt2rkzolqhm.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gt2twjkateu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhongyouzk.top/Article/details/gt2jrrslaip.html

[Q44] IN 子查询
来源：http://dali.316326.xyz/Article/details/gt2lkguwoif.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgufenzy.top/Article/details/gt2xwzhcork.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvmofsjb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gt2xyykcjsy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aibaodan.cn/Article/details/gt2drwokiyg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gt2fgazbcsf.html

[Q47] 与平均值比较
来源：http://dali.daria6918.cn/Article/details/gt2cijffbof.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gt2jbsgarsq.html

[Q48] CTE 公用表表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2xljhjzcx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2seyleuis.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gt2lrpijsvh.html

[Q49] 更新单行
来源：http://dali.jinqigfzy.top/Article/details/gt2uyjswelk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gt2dzkpjjwb.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgwqzjuc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.9152youxi.cn/Article/details/gt2veunndwf.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gt2tefdkeru.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvivtnsh.html

[Q52] 删除指定行
来源：http://dali.ybcxt.top/Article/details/gt2mqarnhkq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gt2malaxuel.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gt2rfbnmlzg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gt2egvtbrjt.html

[Q54] 清空表
来源：http://dali.0kj1m.cn/Article/details/gt2rakwukuu.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gt2tblzlmuy.html

[Q55] 排名（并列占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydvrryhu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbdaxztt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dashuyun.cn/Article/details/gt2jlnqutrr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yongpay.top/Article/details/gt2kkhtjrqk.html

[Q57] 行号
来源：http://dali.jianghu66.top/Article/details/gt2ngenntkz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cheryme.top/Article/details/gt2jmhpztua.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gt2hoawjzyi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2pzrbcswb.html

[Q59] 分组内累计
来源：http://dali.jlsjyb.cn/Article/details/gt2rninanxx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2gzhhsbll.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gt2gjurkveo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gt2bajjfxtm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2pstansls.html

[Q61] 移动平均
来源：http://dali.yongpay.top/Article/details/gt2fgywjnqo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2fwmwfthx.html

[Q62] 分组占比
来源：http://dali.hywenlv.cn/Article/details/gt2rhezlath.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gt2acikkycr.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gt2mijlknnc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258888.top/Article/details/gt2hcfyxfiq.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojzxxfji.html

COMMIT;
来源：http://dali.quarkkingdee.top/Article/details/gt2vpoztlmv.html

[Q65] 回滚事务
来源：http://dali.andypj.xyz/Article/details/gt2cacjryvp.html

ROLLBACK;
来源：http://dali.daxiang520.top/Article/details/gt2lvtptgzi.html

[Q66] 行锁查询
来源：http://dali.gaohongyu789.top/Article/details/gt2qgzcdlwu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gt2kngopadn.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gt2lbpaaycj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daxiang520.top/Article/details/gt2artpajwr.html

[Q68] 保存点
来源：http://dali.316326.xyz/Article/details/gt2ripebylm.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gt2yfciwecc.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gt2fsrpkchn.html

[Q69] 查看执行计划
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwuqlmmx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gt2onswjaix.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vygwrfuf.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gt2ggeqpxdu.html

[Q71] 查看建表语句
来源：http://dali.yvedp.cn/Article/details/gt2giabuirk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gt2fbqxuthk.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gt2crgvnstm.html

SHOW INDEX FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpeqordt.html

[Q73] 查看表状态
来源：http://dali.xylfe.cn/Article/details/gt2jzyiiqne.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guowangkeji.top/Article/details/gt2qcgaqfjq.html

[Q74] 强制使用索引
来源：http://dali.haohaochexian.top/Article/details/gt2ywshcghb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gt2atmazvld.html

[Q75] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gt2kpsbwmvr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2lmscvmfb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gt2emcncybg.html

[Q76] 按天统计
来源：http://dali.hnxiangtu.top/Article/details/gt2adoklmyt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yvedp.cn/Article/details/gt2sqahovvu.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhvrmefo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gt2viokknyo.html

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gt2xfglfsyt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.0kj1m.cn/Article/details/gt2ulyjvhur.html

[Q79] 字符串拼接
来源：http://dali.tanke756.top/Article/details/gt2clklxmkc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gt2cvevzxaw.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gt2keocqibc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2sgeglcrk.html

[Q81] 字符串替换
来源：http://dali.meibo888.top/Article/details/gt2bsoarqpn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2ouuxtiah.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gt2ygrvvpbo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2rqtjgfju.html

[Q83] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gt2owyjgzto.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2jpozeyon.html

[Q84] 去除首尾空格
来源：http://dali.hammf.cn/Article/details/gt2jhjukbhx.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2vefunroq.html

[Q85] 数值取整
来源：http://dali.jlsjyb.cn/Article/details/gt2taseqspa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhixingplan.top/Article/details/gt2lujthmvd.html


<!-- 参考信息 -->