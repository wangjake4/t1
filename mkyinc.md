代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.bjfxy.top/Article/details/gt2nvbuxdhg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgfzy.top/Article/details/gt2xdxfngvl.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gt2iogxehtw.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gt2zhxnxlyb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vriblnnj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuanzhike.top/Article/details/gt2efcbtqzw.html

JS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2bwqzyftd.html

TS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gt2toctklrg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gt2igsodbil.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gt2dsmyhnjc.html

Ruby: threads.map(&:join)
来源：http://dali.fengsongda.top/Article/details/gt2gefpjabm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gt2iznfczeg.html

[O06] 使用进程池
来源：http://dali.jqgufenzy.top/Article/details/gt2buifkcxl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdurtuso.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigufen.top/Article/details/gt2bnskwhoq.html

JS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gt2cutkuvya.html

TS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gt2duyimiwk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258.top/Article/details/gt2tjjclbtw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gt2feoxagwd.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gt2tdlybkcw.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gt2cpnitxvx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2vatbfacm.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gt2chjdaxal.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2dobibjzj.html

[P01] 生成 UUID
来源：http://dali.cdnleiting.top/Article/details/gt2rlhlmfkj.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigfzy.top/Article/details/gt2wijxsazw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttcvqvpy.html

JS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gt2bsuaoxkn.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gt2znvelqzb.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gt2anuilffg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guannengcc.top/Article/details/gt2hfvmkapc.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2htjpaygi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gt2azwhrtme.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhoulong.xyz/Article/details/gt2hujoxqbc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guowangkeji.top/Article/details/gt2lozkmtdi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntaaayjj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cqqwz.cn/Article/details/gt2oazzkmmd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gt2yefzmnnz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2bjcwtjrw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gt2pzxkoidy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenzaomai.com/Article/details/gt2xzmwrkmg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zdqjudy.top/Article/details/gt2hloxlppu.html

[P03] 生成短随机字符串
来源：http://dali.yongpay.top/Article/details/gt2nrrqiiwe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yueranfly.top/Article/details/gt2xwsaebdb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gt2rmikcjfp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2ffkxswal.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gt2fnvbeqnw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sysykeji.top/Article/details/gt2yvidqimd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gotoacloud.top/Article/details/gt2pjpniqrr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jyoumei.cn/Article/details/gt2uylmsabl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.havefunace.top/Article/details/gt2ieedoben.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gt2izgmippe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftmrysap.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2xfndiusg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gt2scrpxdhz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gt2oxplfbtg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxinkj.top/Article/details/gt2qbapildp.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gt2qrucharc.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozgqgype.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gt2omfwjqie.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cashguo.top/Article/details/gt2vxkbozkg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gogol.net.cn/Article/details/gt2vlwhxvqx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangdashe.top/Article/details/gt2vqwmvmdb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xziqi.cn/Article/details/gt2shmgtlpa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gt2wlfxgsfv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gt2walsjzzp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gt2sclyntgl.html

Ruby: a == b
来源：http://dali.yonumen.top/Article/details/gt2qldeivuq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gt2jebcowpf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gt2sygwydvz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gt2acwekkfb.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gt2jcizddgo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pycfn.com/Article/details/gt2cpwrywlt.html

TS:   if (x == null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqwvfany.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gt2chopixom.html

Go:   if x == nil {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqkuujwl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aizwys.cn/Article/details/gt2mcyncwax.html

C#:   if (x is null) {}
来源：http://dali.c1oappe.top/Article/details/gt2tbyzbajq.html

[P07] 防抖与节流
来源：http://dali.yonumen.top/Article/details/gt2orxioehs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aizwys.cn/Article/details/gt2ywfmazed.html

PHP:  // 手写时间戳比较
来源：http://dali.dianchejie.cn/Article/details/gt2mdgursky.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2nsaclcqv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmcccsle.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hammf.cn/Article/details/gt2mfnlkrim.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.feifeiyinyue.top/Article/details/gt2aduogini.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnxiangtu.top/Article/details/gt2pnmjgryg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdcgabmc.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gt2trrunmwg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gt2tttjnhtq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fzhhl.top/Article/details/gt2pegkwkhg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gt2wocinref.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gt2igwqhqor.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gt2ewuwedmb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigufen.top/Article/details/gt2vbhjxmob.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gt2vkfyzmgy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2afnzdtej.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ixqpbrjm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.smart0.xyz/Article/details/gt2wthkjsme.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2iqvlwilr.html

[Q01] 创建表
来源：http://dali.nanxinkj.top/Article/details/gt2ixcwfxbq.html

CREATE TABLE users (
来源：http://dali.fengsongda.top/Article/details/gt2lxldvrtl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gt2ajrteyfh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gt2gmpbzzzv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gt2tqeuqjxh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sweek.top/Article/details/gt2wljirtyo.html

);
来源：http://dali.cashguo.top/Article/details/gt2oovygnxl.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gt2fcmnjevw.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gt2xfznebms.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gt2hzawcqfl.html

user_id INT NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gt2eldoilwi.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gt2olkkgwfr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgfzy.top/Article/details/gt2gvhqtwzc.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fosllqlh.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gt2sbvoxqap.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuanzhike.top/Article/details/gt2lhzmcwxq.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gt2hmanhsbl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gt2fmnrvvep.html

[Q05] 重命名列
来源：http://dali.0kj1m.cn/Article/details/gt2mxuamwpr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnxiangtu.top/Article/details/gt2fctisnox.html

[Q06] 删除列
来源：http://dali.ybcxt.top/Article/details/gt2qpqnxcdc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.feifeiyinyue.top/Article/details/gt2luatwisz.html

[Q07] 删除表
来源：http://dali.quarkkingdee.top/Article/details/gt2lbdnbyuy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2brtjjktk.html

[Q08] 创建普通索引
来源：http://dali.nanxuanxn.top/Article/details/gt2ndybaplp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gt2gahwwgdv.html

[Q09] 创建唯一索引
来源：http://dali.yvedp.cn/Article/details/gt2vmtwlmsq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gt2jhceflei.html

[Q10] 插入单行
来源：http://dali.havefunace.top/Article/details/gt2cijqcuyq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2donyajsn.html

[Q11] 一次插入多行
来源：http://dali.redwolf501.top/Article/details/gt2ucnkulkc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.mhx1999.top/Article/details/gt2kbrrprly.html

[Q12] 插入后取自增 ID
来源：http://dali.tanke756.top/Article/details/gt2sozprokb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.0kj1m.cn/Article/details/gt2fudgjeai.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sufxvd.cn/Article/details/gt2pkyjfzmn.html

[Q13] 忽略重复插入
来源：http://dali.jinqigufen.top/Article/details/gt2orxwbgbi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2tozvxgst.html

[Q14] 存在则更新（upsert）
来源：http://dali.yanxiufei.cn/Article/details/gt2hetrugfg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gt2bvbelitr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aibaodan.cn/Article/details/gt2hngxobyh.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gt2nnndeaqk.html

SELECT * FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2sqbqdugm.html

[Q16] 查询指定列
来源：http://dali.feifeiyinyue.top/Article/details/gt2vegfhrnz.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2foaklbgt.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gt2jahsjdts.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ivvv.top/Article/details/gt2ualchakg.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gt2coduljtp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gt2jabqvwva.html

[Q19] 范围查询
来源：http://dali.nanxinkj.top/Article/details/gt2jvsudimx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gt2diorgqeg.html

[Q20] IN 列表
来源：http://dali.jianghu66.top/Article/details/gt2ocaemxdi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gt2oslusotw.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gt2hfawmcck.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gihznodw.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gt2ykqzndxc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guannengcc.top/Article/details/gt2omhwrxfa.html

[Q23] 分页
来源：http://dali.andypj.xyz/Article/details/gt2eqnfdcbs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gt2ecpdkfuo.html

[Q24] 去重
来源：http://dali.daria6918.cn/Article/details/gt2rcwqaplu.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gt2gfkcsbvl.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gt2tqngxpxy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljmnchxq.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gt2yohlxebq.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yluftwnp.html

[Q27] 条件计数
来源：http://dali.hfpthk.cn/Article/details/gt2hlkjczhq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2hpipkect.html

[Q28] 求和与平均
来源：http://dali.hnxiangtu.top/Article/details/gt2kzfyerwb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2gmormlge.html

[Q29] 最大最小值
来源：http://dali.daxiang520.top/Article/details/gt2qppqmtpf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2anoojwqz.html

[Q30] 分组统计
来源：http://dali.gogol.net.cn/Article/details/gt2mbxinsoc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gt2owapocvz.html

[Q31] 分组后过滤
来源：http://dali.ybcxt.top/Article/details/gt2jcbnjtxw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gt2elynhzxk.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2mgbqhinu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2norwicdo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxuanxn.top/Article/details/gt2rekbbuuk.html

[Q33] 多列分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2swutsyea.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.meibo888.top/Article/details/gt2mxbdtigm.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gt2ofluxaaq.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gt2xbvftuux.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjdhsntb.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2nkviqbvx.html

[Q35] 内连接
来源：http://dali.jqgufenzy.top/Article/details/gt2msoehcwx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gt2sfdrbmou.html

[Q36] 左连接
来源：http://dali.haohaochexian.top/Article/details/gt2tfytogmo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2xafttrmx.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gt2fykgvmbn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenlongwang.top/Article/details/gt2wftveagj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258888.top/Article/details/gt2shlnalmh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gt2lksuhxot.html

[Q39] 自连接（查上下级）
来源：http://dali.gaohongyu789.top/Article/details/gt2rivazesv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdgneeaw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hfpthk.cn/Article/details/gt2yriwylnk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gt2ohtkunxn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gt2pmslpbxh.html

[Q41] 多表连接
来源：http://dali.cheryme.top/Article/details/gt2orxziyxa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dianchejie.cn/Article/details/gt2tlitzhsn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2natelvuh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gt2kbxjzjvj.html

[Q42] 连接条件附加过滤
来源：http://dali.snrcjt.cn/Article/details/gt2tnhyzysq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gt2bbejpmbx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sxryk.cn/Article/details/gt2tmdrfkdx.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wohhuywe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gt2kgccdzmj.html

[Q44] IN 子查询
来源：http://dali.smart0.xyz/Article/details/gt2oxfozdke.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hywenlv.cn/Article/details/gt2jmhoibqj.html

[Q45] EXISTS 判断存在
来源：http://dali.yanxiufei.cn/Article/details/gt2xfmvpwlo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2pjfvkqjp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gt2qcckwimi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gt2xubppggu.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gt2xpfjyoym.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gogol.net.cn/Article/details/gt2mciamecy.html

[Q48] CTE 公用表表达式
来源：http://dali.9152youxi.cn/Article/details/gt2rnyajqzl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gt2yutzhmsq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gt2gqzzlymh.html

[Q49] 更新单行
来源：http://dali.wangshuangyany.cn/Article/details/gt2fboupaek.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gt2fzuckyjd.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gt2bvxgpzqb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.birdmap.top/Article/details/gt2aecoakha.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gt2rwuazqhx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2oyqyplfs.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gt2wuevmsgs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gt2kkjolfrb.html

[Q53] 按条件删除
来源：http://dali.pengpengdd.cyou/Article/details/gt2owfzqzgl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gt2hoaxkisg.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cobmoasy.html

TRUNCATE TABLE logs;
来源：http://dali.snrcjt.cn/Article/details/gt2rbbsexja.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gt2sjmzhqfn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gt2vsqaolsy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hammf.cn/Article/details/gt2hdblifpg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pruddzgz.html

[Q57] 行号
来源：http://dali.yongpay.top/Article/details/gt2labhfncw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2qvsrpchs.html

[Q58] 累计求和
来源：http://dali.xziqi.cn/Article/details/gt2xpshqzdw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2tmhroaoc.html

[Q59] 分组内累计
来源：http://dali.xylfe.cn/Article/details/gt2wslvtsed.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2bfmqjxko.html

[Q60] 取上一行 / 下一行
来源：http://dali.quarkkingdee.top/Article/details/gt2xoexkfuz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gt2tolbgxxb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2bnawhesl.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gt2xczxwygl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2ceiqjnhn.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gt2eydqrzvi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gt2ouwqutpk.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gt2czqxrtkf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.svipenyu.cn/Article/details/gt2owaixkfa.html

[Q64] 提交事务
来源：http://dali.chenzaomai.com/Article/details/gt2pojfiche.html

COMMIT;
来源：http://dali.hnqzz.top/Article/details/gt2upoupkav.html

[Q65] 回滚事务
来源：http://dali.sysykeji.top/Article/details/gt2qtatwjit.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gt2podthaxv.html

[Q66] 行锁查询
来源：http://dali.yvedp.cn/Article/details/gt2fngsyyya.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gt2ldrjgjua.html

[Q67] 设置隔离级别
来源：http://dali.iojbl.cn/Article/details/gt2ichgumqp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.redwolf501.top/Article/details/gt2dedqrior.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gt2lcmvjyrx.html

SAVEPOINT sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohgaattg.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gt2xkoilxyj.html

[Q69] 查看执行计划
来源：http://dali.zycfv.cn/Article/details/gt2wqrdvjmk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ivvv.top/Article/details/gt2odcirxbg.html

[Q70] 更新统计信息
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbvxbwsr.html

ANALYZE TABLE users;
来源：http://dali.andypj.xyz/Article/details/gt2tqhqxefe.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gt2txellfyf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guowangkeji.top/Article/details/gt2tlzszygt.html

[Q72] 查看索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2tngrhwdj.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sgdfbgmw.html

[Q73] 查看表状态
来源：http://dali.iojbl.cn/Article/details/gt2orffywox.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gt2nhpdzwpy.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gt2moadczha.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlctnfsk.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gt2cjbzypsc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2nlqvhnvc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gt2hxqkbotv.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gt2gbkgphtr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gt2hrexpaeq.html

[Q77] 时间加减
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cafwjxuy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhongyouzk.top/Article/details/gt2psuraqnz.html

[Q78] 当前时间
来源：http://dali.hammf.cn/Article/details/gt2ydarifoi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gt2jfyqzpyo.html

[Q79] 字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gt2jktmiixt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gt2hhuhgwvh.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gt2bjhlrkxi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2upzpvxdv.html

[Q81] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gt2zhdcowwq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2gqwphqfj.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrcncjol.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2wsvgxfcb.html

[Q83] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gt2sucjxnmo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypevxveq.html

[Q84] 去除首尾空格
来源：http://dali.dashuyun.cn/Article/details/gt2nfzybpao.html

SELECT TRIM(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2htvwuetg.html

[Q85] 数值取整
来源：http://dali.bjfxy.top/Article/details/gt2dwtnuqpj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aibaodan.cn/Article/details/gt2htstbggv.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gt2ivvhuesr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangshuangyany.cn/Article/details/gt2qedhamqy.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gt2ujmvfesz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guannengcc.top/Article/details/gt2crbysqfp.html

[Q88] 行转列（条件聚合）
来源：http://dali.xinyue.icu/Article/details/gt2kblrhcvl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ivvv.top/Article/details/gt2ojyvchid.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2sxorlzzu.html

[Q89] 判断表是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbsgkcoe.html


<!-- 参考信息 -->