代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cdnleiting.top/Article/details/gt2wmldvfiu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuanzhike.top/Article/details/gt2gomkuwzk.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gt2asyltaqt.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gt2arosbwpd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.316326.xyz/Article/details/gt2wzssfilr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gt2bmsbfscj.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2gciaohzf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prdprawk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yvedp.cn/Article/details/gt2bncxjrhf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gt2tlizzukk.html

Ruby: threads.map(&:join)
来源：http://dali.fengsongda.top/Article/details/gt2vfjibjbo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhengqikj.top/Article/details/gt2towpjghl.html

[O06] 使用进程池
来源：http://dali.yangfankeji.com/Article/details/gt2osqjxdas.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigufen.top/Article/details/gt2vohqcwse.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gt2rsjqlobw.html

JS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gt2edcgcvzj.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gt2eqdvlrkk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gt2mbprepov.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuetiantiany.cn/Article/details/gt2tkjevgqq.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gt2xmeulsza.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gt2posgzndv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2lsiczpfl.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gt2syvrdmci.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vyqnbguy.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gt2qojyyzjm.html

Py:   str(uuid.uuid4())
来源：http://dali.yangfankeji.com/Article/details/gt2kqasfykc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2crplsnbl.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2llroraey.html

TS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gt2bxzerrvb.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2miedaefa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqyfzpnl.html

Ruby: SecureRandom.uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idexnbiy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvkjisip.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihugeiak.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangdashe.top/Article/details/gt2fhqkudhf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2wltkizpi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2teqkvope.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tianlin.xyz/Article/details/gt2msflckny.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gt2xlotrrbn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.feifeiyinyue.top/Article/details/gt2hskxmtbh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gt2takihlek.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.feifeiyinyue.top/Article/details/gt2scyrkcrp.html

[P03] 生成短随机字符串
来源：http://dali.nanxinkj.top/Article/details/gt2eycrhgwe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwwlwgo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fzhhl.top/Article/details/gt2jomjehyc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gt2pmiajtgv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gt2dhuuvdwq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.svipenyu.cn/Article/details/gt2lqaedyyg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dovbcwwk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shzxlz.cn/Article/details/gt2wygdqokp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gt2ygumhahb.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gt2tbhvgrkn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjbdnbvj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2zzsfzvrx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gt2tppdyoag.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gt2lnruiumw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nwbrower.top/Article/details/gt2kztggtda.html

Go:   len(arr);  len(m)
来源：http://dali.tianlin.xyz/Article/details/gt2pphsewkb.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2felooblt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zycfv.cn/Article/details/gt2squdjhgd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fzhhl.top/Article/details/gt2cozfcmrv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gt2rqqhcsxc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gt2aaemaihq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pycfn.com/Article/details/gt2ebfigtwr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gt2ieeiuysk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gt2frvnvmgx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2xtchjdde.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gt2lvacboye.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gt2dirzpjod.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tian-w.cn/Article/details/gt2elemdxso.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhixingplan.top/Article/details/gt2sgyvjoii.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gt2wdwhtltc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shzxlz.cn/Article/details/gt2uzsdbuqp.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gt2gcrimbqn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gt2rvggsgrk.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gt2tsnrqqjs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxhmkebi.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gt2jwqyzogv.html

[P07] 防抖与节流
来源：http://dali.zhoulong.xyz/Article/details/gt2zwqwdzbz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigfzy.top/Article/details/gt2sqgakwat.html

PHP:  // 手写时间戳比较
来源：http://dali.ehwqpu.com/Article/details/gt2jzkwzngb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gt2ursdacze.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gt2pkqifomo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gt2klfttexd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhixingplan.top/Article/details/gt2tlthimou.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gt2hbldzsaq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxuanxn.top/Article/details/gt2zycocaac.html

[P08] 处理浮点精度问题
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnbchvey.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gt2hjbgeaxl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guannengcc.top/Article/details/gt2jufibzdz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigufen.top/Article/details/gt2lmpmhxdy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gt2agpqzytd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ydzc1.top/Article/details/gt2titmtynp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kaxmophk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.birdmap.top/Article/details/gt2ihgucoyg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzlybndn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2tkzuovue.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.smart0.xyz/Article/details/gt2hyapudpp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2vpbtdwmb.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gt2vnpdauex.html

CREATE TABLE users (
来源：http://dali.daxiang520.top/Article/details/gt2oyivxepf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gt2yvadimnp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gt2emhwzfix.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gt2mtjwrmsl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.kuanghao11.cn/Article/details/gt2fuphqjci.html

);
来源：http://dali.xinyue.icu/Article/details/gt2uvzyvkqv.html

[Q02] 创建带外键的表
来源：http://dali.yuanzhike.top/Article/details/gt2hvowbwvo.html

CREATE TABLE orders (
来源：http://dali.vqdsnc.cn/Article/details/gt2gxuxdvuc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gt2yqzirate.html

user_id INT NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gt2aghkgcsu.html

amount DECIMAL(10, 2),
来源：http://dali.kuanghao11.cn/Article/details/gt2blftckfy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cdnleiting.top/Article/details/gt2vcvhlwfc.html

);
来源：http://dali.ivvv.top/Article/details/gt2impaahka.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gt2ieratzud.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigfzy.top/Article/details/gt2ltndbfiz.html

[Q04] 修改列类型
来源：http://dali.shzxlz.cn/Article/details/gt2iywveekx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qclanvux.html

[Q05] 重命名列
来源：http://dali.sweek.top/Article/details/gt2qwvnwwua.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fzhhl.top/Article/details/gt2lhqqapyq.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gt2kauhycpu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmbjgjko.html

[Q07] 删除表
来源：http://dali.cdnleiting.top/Article/details/gt2pkgcblaf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258888.top/Article/details/gt2zzkwtsla.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gt2plqqpfbv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nraeedav.html

[Q09] 创建唯一索引
来源：http://dali.yonumen.top/Article/details/gt2xmagttrz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gt2lgavrauu.html

[Q10] 插入单行
来源：http://dali.zdqjudy.top/Article/details/gt2cupufxvr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gt2wftofltj.html

[Q11] 一次插入多行
来源：http://dali.jiagoushi.top/Article/details/gt2ewrpaybw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daxiang520.top/Article/details/gt2lxejyolk.html

[Q12] 插入后取自增 ID
来源：http://dali.kuanghao11.cn/Article/details/gt2fwqotfpg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwjyojdy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gt2igmibgnw.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gt2qudtkrtg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gt2udpplobe.html

[Q14] 存在则更新（upsert）
来源：http://dali.guowangkeji.top/Article/details/gt2ekguduwh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cucudq.cn/Article/details/gt2nyiluocr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nwbrower.top/Article/details/gt2mnuofcke.html

[Q15] 查询全部
来源：http://dali.smart0.xyz/Article/details/gt2jfelxekf.html

SELECT * FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2jhgyoayd.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gt2izmilziz.html

SELECT id, name FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2sgtticdb.html

[Q17] 条件查询
来源：http://dali.jlsjyb.cn/Article/details/gt2uvcpnfcf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2ltkunzxa.html

[Q18] 模糊匹配
来源：http://dali.havefunace.top/Article/details/gt2wueapznp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cashguo.top/Article/details/gt2gopggjmz.html

[Q19] 范围查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwufphhg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhixingplan.top/Article/details/gt2ddlelnpr.html

[Q20] IN 列表
来源：http://dali.iojbl.cn/Article/details/gt2tfksxzpx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2uaifbdes.html

[Q21] 空值判断
来源：http://dali.9152youxi.cn/Article/details/gt2rufkhaau.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zdqjudy.top/Article/details/gt2zbpktjae.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gt2hvhzfvnf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gt2huuqutnq.html

[Q23] 分页
来源：http://dali.hnqzz.top/Article/details/gt2jjdoutxj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gt2uyghcell.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gt2spzhzsas.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2yjnzfmjv.html

[Q25] 只取前 N 条
来源：http://dali.yj202588.top/Article/details/gt2pchuezpu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sweek.top/Article/details/gt2udcpdhwj.html

[Q26] 计数
来源：http://dali.birdmap.top/Article/details/gt2rkfgsjqf.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2abvxqrrt.html

[Q27] 条件计数
来源：http://dali.dianchejie.cn/Article/details/gt2ctdkkhkg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2xgxmahpa.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gt2jxgrklwb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2gzuqytnm.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gt2fmsnwyil.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2wbocrcna.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gt2amcwkoye.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gt2xovewuha.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gt2qtopvyfq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gt2tumhcubk.html

[Q32] 分组拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2kztymusx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gt2rvwtezec.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gt2jjmejumb.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gt2vvkcfxwu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdzagvy.html

[Q34] 每组取第一条
来源：http://dali.zhongyouzk.top/Article/details/gt2ugeywfmz.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gt2vmuyqcdx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gt2cnvdnkou.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2rxmqqzpr.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gt2qzsbbohx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gt2xctvwbbj.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gt2yfsiytug.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gt2slsfeale.html

[Q37] 右连接
来源：http://dali.shuidangran.top/Article/details/gt2deaxwcxx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gt2bsmnmdjs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dianchejie.cn/Article/details/gt2bufcffyg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gt2newsjasb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbjeyge.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cashguo.top/Article/details/gt2txhdmbrh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npcmspvs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gt2wjdwfngr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gt2xiirayyf.html

[Q41] 多表连接
来源：http://dali.tanke756.top/Article/details/gt2jtrrjtvc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cucudq.cn/Article/details/gt2auywecya.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhixingplan.top/Article/details/gt2cdwodrwr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yanxiufei.cn/Article/details/gt2fywodprx.html

[Q42] 连接条件附加过滤
来源：http://dali.svipenyu.cn/Article/details/gt2rgrixuny.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jlsjyb.cn/Article/details/gt2rpglopqo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shuidangran.top/Article/details/gt2zwpaendg.html

[Q43] 标量子查询
来源：http://dali.guannengcc.top/Article/details/gt2numjahje.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gt2qddvpapc.html

[Q44] IN 子查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbmgihyz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gt2blxzmbdx.html

[Q45] EXISTS 判断存在
来源：http://dali.hnxiangtu.top/Article/details/gt2ycbdijxk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gt2seronxca.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdylqgkn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gt2mtxpdtfh.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gt2fbtkuzmz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yongpay.top/Article/details/gt2byapykpn.html

[Q48] CTE 公用表表达式
来源：http://dali.gogol.net.cn/Article/details/gt2uyemmwvf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gt2jgojnjym.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gt2oxcjglbl.html

[Q49] 更新单行
来源：http://dali.zhixingplan.top/Article/details/gt2dmpcrydn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2bemxszjd.html

[Q50] 批量更新
来源：http://dali.jinqigfzy.top/Article/details/gt2khsszotq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gt2daudikuk.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gt2jmtlovzf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2rvqmvfaz.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gt2khnknrjg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gt2ecwmtyux.html

[Q53] 按条件删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2upzslvgm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gt2ilbcrvxt.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gt2auraorko.html

TRUNCATE TABLE logs;
来源：http://dali.c1oappe.top/Article/details/gt2ukkdzegj.html

[Q55] 排名（并列占位）
来源：http://dali.snrcjt.cn/Article/details/gt2dxxtvbpn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2svpbckmi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenjidiqi.icu/Article/details/gt2puzbhakr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gt2xvxkowob.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gt2jnqejspr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2haevpvre.html

[Q58] 累计求和
来源：http://dali.hammf.cn/Article/details/gt2qpoebydf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2mptrcovh.html

[Q59] 分组内累计
来源：http://dali.tianlin.xyz/Article/details/gt2rwxhdqsn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2runeknpa.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gt2yoflydtw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fzhhl.top/Article/details/gt2pktdnbir.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gt2dqsrxrrr.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gt2wrpziekg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwrqttsv.html

[Q62] 分组占比
来源：http://dali.316326.xyz/Article/details/gt2haxdufvu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gt2lmuahrki.html

[Q63] 开启事务
来源：http://dali.yuanzhike.top/Article/details/gt2bgsofqdi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vpggtroe.html

[Q64] 提交事务
来源：http://dali.zhongyouzk.top/Article/details/gt2fgndasvt.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gt2ittvedzx.html

[Q65] 回滚事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmbenoqv.html

ROLLBACK;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvuzoist.html

[Q66] 行锁查询
来源：http://dali.gogol.net.cn/Article/details/gt2njzbbcko.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gt2ijbomlcp.html

[Q67] 设置隔离级别
来源：http://dali.yueranfly.top/Article/details/gt2ojlhzave.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.svipenyu.cn/Article/details/gt2lreuekpy.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gt2yhlxjvjw.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gt2pmxonkis.html

ROLLBACK TO sp1;
来源：http://dali.xinyue.icu/Article/details/gt2scwrhpoq.html

[Q69] 查看执行计划
来源：http://dali.svipenyu.cn/Article/details/gt2laisoqsp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnqzz.top/Article/details/gt2qqhrkmtt.html

[Q70] 更新统计信息
来源：http://dali.kuanghao11.cn/Article/details/gt2gcvrzxsf.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gt2xvhmypzr.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gt2rrczlxug.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jlsjyb.cn/Article/details/gt2drjjmpbp.html

[Q72] 查看索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2kliozgjw.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2vyuipkoi.html

[Q73] 查看表状态
来源：http://dali.aizwys.cn/Article/details/gt2jsxpkgwv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hammf.cn/Article/details/gt2lghpmwbu.html

[Q74] 强制使用索引
来源：http://dali.zhongyouzk.top/Article/details/gt2uauzbfha.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aizwys.cn/Article/details/gt2exgrsyph.html

[Q75] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gt2sdcophxh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2eaifiver.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuanzhike.top/Article/details/gt2uqkwaexi.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gt2zibsawch.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gt2abcwqiqp.html

[Q77] 时间加减
来源：http://dali.zhoulong.xyz/Article/details/gt2ihyqmtap.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gt2ylyyropa.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2vvnjgyoj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.iojbl.cn/Article/details/gt2ylvmfbdp.html

[Q79] 字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnabriwx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gt2qsbssuzy.html

[Q80] 字符串截取
来源：http://dali.tanke756.top/Article/details/gt2krjwpvwb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2xkkajfnw.html

[Q81] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gt2vbgobfqj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2hrhwqfpl.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gt2lveawzfv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2gvvuyufq.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2xsrdqhsu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2wzpwsuvu.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gt2qwhzyyca.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2hmeowusf.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gt2mjoloajp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.smart0.xyz/Article/details/gt2wppuitfh.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gt2dfitaelb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnxiangtu.top/Article/details/gt2foizeipn.html

[Q87] JSON 字段做条件
来源：http://dali.wangdashe.top/Article/details/gt2yrthbhzo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gt2shwvrace.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gt2jximtmuq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cqqwz.cn/Article/details/gt2orhydlap.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2lzylgkwj.html

[Q89] 判断表是否存在
来源：http://dali.guannengcc.top/Article/details/gt2rzvsnbln.html


<!-- 参考信息 -->