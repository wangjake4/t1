代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.kuanghao11.cn/Article/details/gt2nhgspykw.html

C#:   lock (gate) { shared++; }
来源：http://dali.hammf.cn/Article/details/gt2ndmsflhn.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jymucvyl.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gt2dqqdbeeo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ivvv.top/Article/details/gt2dzzawiph.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gt2mzlozyyw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wkdscwzx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhengqikj.top/Article/details/gt2ohlsywxq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.kuanghao11.cn/Article/details/gt2hcboghhl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hammf.cn/Article/details/gt2ugwqqbzs.html

C#:   async Task F() { await G(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2mymiirvg.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuanzhike.top/Article/details/gt2vrcpatic.html

Py:   asyncio.gather(*tasks)
来源：http://dali.haohaochexian.top/Article/details/gt2lnoaagid.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.andypj.xyz/Article/details/gt2igjxlvnh.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2gmudtlum.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tcgkjpok.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.andypj.xyz/Article/details/gt2rakzjdsr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gt2mqsfmhuw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxmzrfr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.haohaochexian.top/Article/details/gt2rowbmvay.html

[O06] 使用进程池
来源：http://dali.aizwys.cn/Article/details/gt2fkgvuhmi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258.top/Article/details/gt2noswjvsx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gt2brppvwfa.html

JS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gt2nochltbz.html

TS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2qnqzwgkf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.vqdsnc.cn/Article/details/gt2nmckxtnu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigfzy.top/Article/details/gt2qfbbnqbc.html

Ruby: // fork 块
来源：http://dali.tanke756.top/Article/details/gt2bbzadunl.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gt2khcoofjn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2pozvhlty.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gt2tobkzerl.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2rhezpklt.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gt2xhfehejl.html

Py:   str(uuid.uuid4())
来源：http://dali.tian-w.cn/Article/details/gt2qtapazlz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gaohongyu789.top/Article/details/gt2rkrlykxc.html

JS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gt2xcbahqwr.html

TS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gt2kjqopmor.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ritqsyql.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hysaishi.cn/Article/details/gt2pqripxjd.html

Ruby: SecureRandom.uuid
来源：http://dali.0kj1m.cn/Article/details/gt2vvatarxc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guannengcc.top/Article/details/gt2nptafilw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.andypj.xyz/Article/details/gt2uoyxlkro.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fengsongda.top/Article/details/gt2ukmplufw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gt2kinbvggh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxinkj.top/Article/details/gt2teluwwdx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gt2cujywtgy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gt2psbtxzvf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxuanxn.top/Article/details/gt2mqmlwisq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tian-w.cn/Article/details/gt2lwdpojns.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.smart0.xyz/Article/details/gt2xcuvgpjf.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gt2iupbsvjv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnqzz.top/Article/details/gt2uutvnqtk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2noijxklv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gt2cnmedfos.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gt2ypyscida.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xziqi.cn/Article/details/gt2blwdnolp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gt2wrtowtgw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gt2fgdgkcvs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.9152youxi.cn/Article/details/gt2butrrtmd.html

[P04] 求长度
来源：http://dali.dashuyun.cn/Article/details/gt2tttugymy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yongpay.top/Article/details/gt2xoqqyobp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2vkpzimjd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gt2vbegqpxq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gt2dvshgumo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gt2infnmuik.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhriusmx.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gt2krqgirtl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlqlzmpa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gt2lyenstzk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sysykeji.top/Article/details/gt2oeknmekx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhiwuduotai.top/Article/details/gt2giwbutsc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhoulong.xyz/Article/details/gt2faqkmaaj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gt2jwvrkabe.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sysykeji.top/Article/details/gt2yizhkrcj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2pyqozcnd.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gt2fdyyqhkp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhixingplan.top/Article/details/gt2nltpfjhd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gt2zfmuzxgl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gt2aqzyuzfp.html

PHP:  if (empty($x)) {}
来源：http://dali.gotoacloud.top/Article/details/gt2jwpsqhgv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuetiantiany.cn/Article/details/gt2blqnrqqt.html

TS:   if (x == null) {}
来源：http://dali.ppjwa.cn/Article/details/gt2hqnrhxei.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gt2dnylqizv.html

Go:   if x == nil {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnnnvrvv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.kuanghao11.cn/Article/details/gt2fxypwsbu.html

C#:   if (x is null) {}
来源：http://dali.snrcjt.cn/Article/details/gt2vmliveog.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gt2dyvhvsml.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenjidiqi.icu/Article/details/gt2rraedeuh.html

PHP:  // 手写时间戳比较
来源：http://dali.zdqjudy.top/Article/details/gt2wehrmglp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gt2uhuodrak.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2xngxcdge.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuanzx.com/Article/details/gt2btmggsvt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nwbrower.top/Article/details/gt2fvnedbcn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ybcxt.top/Article/details/gt2aubppnfn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ybcxt.top/Article/details/gt2yunbleqt.html

[P08] 处理浮点精度问题
来源：http://dali.shuidangran.top/Article/details/gt2ygjluqbs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenzaomai.com/Article/details/gt2qwhyjmes.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cdnleiting.top/Article/details/gt2kurntcqw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dianchejie.cn/Article/details/gt2ovpmtmkg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gt2lvvbucwr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tanke756.top/Article/details/gt2ttnotyqu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gt2tqraudro.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.birdmap.top/Article/details/gt2ogjjnkvk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gt2dhrlmnzp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2cuyetzoh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sysykeji.top/Article/details/gt2jrnlncec.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2trnigqao.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gt2ntslrhyi.html

CREATE TABLE users (
来源：http://dali.jinqigufen.top/Article/details/gt2efdaxlyu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gt2flviomgd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gt2liamxhtx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cqqwz.cn/Article/details/gt2mbvtamxa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj202588.top/Article/details/gt2lddlembo.html

);
来源：http://dali.bjfxy.top/Article/details/gt2erjkkbrh.html

[Q02] 创建带外键的表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bnysnlzp.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gt2pdesvfnz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gt2zljvadgb.html

user_id INT NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gt2gzddlzrg.html

amount DECIMAL(10, 2),
来源：http://dali.zhixingplan.top/Article/details/gt2xbbbaawc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sxryk.cn/Article/details/gt2bqcexpdy.html

);
来源：http://dali.yuanzhike.top/Article/details/gt2zieptcgu.html

[Q03] 增加列
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjwslrlu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gt2qrhsocfb.html

[Q04] 修改列类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzpnwjjf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pycfn.com/Article/details/gt2lgrzdztr.html

[Q05] 重命名列
来源：http://dali.zycfv.cn/Article/details/gt2gpmuoctx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jianghu66.top/Article/details/gt2cegizuki.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gt2cwvtjsgv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2igcvhfhq.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gt2kunppmgd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ehwqpu.com/Article/details/gt2hlthnwbm.html

[Q08] 创建普通索引
来源：http://dali.xziqi.cn/Article/details/gt2njqjkpca.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gt2zuhfvppg.html

[Q09] 创建唯一索引
来源：http://dali.daxiang520.top/Article/details/gt2fayrrxiw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gt2fhlznjtx.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gt2jnxmkvuf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nwbrower.top/Article/details/gt2tdngohis.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2loeoidvs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daxiang520.top/Article/details/gt2pqnqxqtj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gt2ltvpmmub.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgufenzy.top/Article/details/gt2anhdqamn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gt2gpwskafl.html

[Q13] 忽略重复插入
来源：http://dali.jlsjyb.cn/Article/details/gt2lftefktm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbkvbct.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gt2anpenpmr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cldarvrq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuxming.cn/Article/details/gt2xquvzhnv.html

[Q15] 查询全部
来源：http://dali.nwbrower.top/Article/details/gt2unwyqpnf.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2pmokwvaj.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gt2ergumxvz.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2dkxsnzrl.html

[Q17] 条件查询
来源：http://dali.quarkkingdee.top/Article/details/gt2fkbvlobi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gt2cgcvbzwh.html

[Q18] 模糊匹配
来源：http://dali.cdnleiting.top/Article/details/gt2tyadwhqu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tanke756.top/Article/details/gt2ednxhcjl.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gt2wzqtzqhr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zycfv.cn/Article/details/gt2leeyrdui.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gt2cxrnmkic.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sfokqkhv.html

[Q21] 空值判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itootcfh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gt2hgftdpdr.html

[Q22] 排序
来源：http://dali.haohaochexian.top/Article/details/gt2djsdoicw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gt2adjyzzlm.html

[Q23] 分页
来源：http://dali.zycfv.cn/Article/details/gt2uqvbctgk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxuanxn.top/Article/details/gt2bwzpsqyb.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gt2fmyjnmda.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2gxyjecwj.html

[Q25] 只取前 N 条
来源：http://dali.jinqigufen.top/Article/details/gt2bwldiynr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj202588.top/Article/details/gt2kphdbjuj.html

[Q26] 计数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrdjupuf.html

SELECT COUNT(*) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2utsepvsz.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gt2iclqpwjj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2xugzwhwt.html

[Q28] 求和与平均
来源：http://dali.shuidangran.top/Article/details/gt2jdbtzvut.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2lggooayh.html

[Q29] 最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gt2jgxozohk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2iahgtawy.html

[Q30] 分组统计
来源：http://dali.zhixingplan.top/Article/details/gt2owqvscnt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2icyvcuum.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gt2vzwlnitb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gt2cnycznue.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2xyfftebu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gt2upvcslfr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvmtpeqj.html

[Q33] 多列分组
来源：http://dali.pycfn.com/Article/details/gt2wpitqobh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangdashe.top/Article/details/gt2nbrwsdxy.html

[Q34] 每组取第一条
来源：http://dali.nwbrower.top/Article/details/gt2scqabszy.html

SELECT * FROM (
来源：http://dali.jqgufenzy.top/Article/details/gt2yyytfpum.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hfpthk.cn/Article/details/gt2irlntmtn.html

) t WHERE rn = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2npzjkqcd.html

[Q35] 内连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czctpplt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gt2jqfrdykv.html

[Q36] 左连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ccricism.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gt2yywkopjx.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gt2evlpuinw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gt2livoplcy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gt2vomyldhd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zrfkrmbi.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgufenzy.top/Article/details/gt2yzwoxhmm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.meibo888.top/Article/details/gt2dclvjmws.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhoulong.xyz/Article/details/gt2izqdjdid.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gt2xuvkhejo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucdzihtw.html

[Q41] 多表连接
来源：http://dali.cheryme.top/Article/details/gt2hwpegtdq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ydzc1.top/Article/details/gt2jufbqzym.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hammf.cn/Article/details/gt2uwiowyfg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuanzhike.top/Article/details/gt2nonryqhl.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gt2qggnwbug.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jyoumei.cn/Article/details/gt2mdjancrg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tianlin.xyz/Article/details/gt2ijljtgdw.html

[Q43] 标量子查询
来源：http://dali.wangdashe.top/Article/details/gt2ueuqfytf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xkchobcb.html

[Q44] IN 子查询
来源：http://dali.bjfxy.top/Article/details/gt2wtvhlttj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jianghu66.top/Article/details/gt2bwqvwsjm.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gt2ypvmhelr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gt2etpnozco.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shuidangran.top/Article/details/gt2lujdvmhz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gt2zgvwrdrp.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gt2ayjdzljx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gt2cwmsnroz.html

[Q48] CTE 公用表表达式
来源：http://dali.sufxvd.cn/Article/details/gt2zdhxtgkt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.316326.xyz/Article/details/gt2hrtfdmix.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sxryk.cn/Article/details/gt2rajtxqnd.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gt2dcrnpscb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gt2eugpdmvo.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gt2yickhqps.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dashuyun.cn/Article/details/gt2ujalyxdh.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gt2jpbmezpz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2ypaozgny.html

[Q52] 删除指定行
来源：http://dali.hywenlv.cn/Article/details/gt2tuscpwxb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gt2dqevvglk.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gt2surdxbjf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuxming.cn/Article/details/gt2zoiwhjlv.html

[Q54] 清空表
来源：http://dali.redwolf501.top/Article/details/gt2osvasufu.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gt2wjdferxc.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gt2uqaoibsx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj202588.top/Article/details/gt2qvwgbhwf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxinkj.top/Article/details/gt2nlwpuprw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258.top/Article/details/gt2taqaybwe.html

[Q57] 行号
来源：http://dali.yj202588.top/Article/details/gt2eebftmyy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2blxmynnf.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gt2ttgpgonu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtzusefd.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gt2fkgwuehf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2xnwiuodh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhengqikj.top/Article/details/gt2bilhdrqp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigfzy.top/Article/details/gt2ypeccesk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2dgthsofi.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gt2pxceovlz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2skpelsfy.html

[Q62] 分组占比
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uowfakef.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwvindtr.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gt2jvjaprqh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gt2efmrjdff.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gt2hyznzugz.html

COMMIT;
来源：http://dali.jqgufenzy.top/Article/details/gt2wqvzyinp.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gt2pzqjrgiu.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gt2mhugaidr.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gt2kyltfzbu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shuidangran.top/Article/details/gt2qstutjgn.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zghosmnw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2iubtwurf.html

[Q68] 保存点
来源：http://dali.aizwys.cn/Article/details/gt2xojdlpps.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gt2ikyuvzma.html

ROLLBACK TO sp1;
来源：http://dali.yvedp.cn/Article/details/gt2zvmrfnew.html

[Q69] 查看执行计划
来源：http://dali.ivvv.top/Article/details/gt2wikmggyi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gt2cixjtbho.html

[Q70] 更新统计信息
来源：http://dali.smart0.xyz/Article/details/gt2swjbojkq.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gt2fgjnymrr.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gt2fhjyvydy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guowangkeji.top/Article/details/gt2tuuqotep.html

[Q72] 查看索引
来源：http://dali.hywenlv.cn/Article/details/gt2lzanpurf.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2mvxqaegh.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srmhlmvm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jiagoushi.top/Article/details/gt2qxpmqidd.html

[Q74] 强制使用索引
来源：http://dali.sufxvd.cn/Article/details/gt2hgyomnfx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shzxlz.cn/Article/details/gt2ueqxqpwb.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gt2hsnpfjjg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzpujmzs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gt2qozhbmee.html

[Q76] 按天统计
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzjecavi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gt2ftfpheko.html

[Q77] 时间加减
来源：http://dali.daria6918.cn/Article/details/gt2iijmawte.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gt2fqfwjkeh.html

[Q78] 当前时间
来源：http://dali.tanke756.top/Article/details/gt2tnkvpvpb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gt2nminalfi.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gt2yurojlbv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cficqhhd.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gt2mivjhubq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2dvrrphza.html

[Q81] 字符串替换
来源：http://dali.yj202588.top/Article/details/gt2pifoxixh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2pttspktl.html

[Q82] 字符长度与字节长度
来源：http://dali.jyoumei.cn/Article/details/gt2dcjpuvsm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2roarsfma.html

[Q83] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2rghxuurf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlrkyeku.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gt2iimxgzmr.html

SELECT TRIM(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2fxvlhiym.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gt2btvcwscn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigufen.top/Article/details/gt2vdthszjz.html


<!-- 参考信息 -->