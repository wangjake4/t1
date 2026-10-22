代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gt2xebklorn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wzetczad.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gt2ftivdomi.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gt2gmstbqop.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2hdkweosy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.redwolf501.top/Article/details/gt2tsqjspmg.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2dxzbdvvz.html

TS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gt2coklnxsm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gt2dloiqvec.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gt2wcudbcie.html

Ruby: threads.map(&:join)
来源：http://dali.yongpay.top/Article/details/gt2hngqosip.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gt2fqwukxxb.html

[O06] 使用进程池
来源：http://dali.tanke756.top/Article/details/gt2ccopskhz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gt2pfkbbgrl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gt2vzzywcoo.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2wmacxgkc.html

TS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gt2rqlhemzn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gt2mqhhrumk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuanzhike.top/Article/details/gt2sehdazys.html

Ruby: // fork 块
来源：http://dali.vqdsnc.cn/Article/details/gt2rqvfxtgw.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gt2kkvvzjly.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2grmyjzzu.html

P. 常用工具函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2caaflyta.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2zdddklbe.html

[P01] 生成 UUID
来源：http://dali.sweek.top/Article/details/gt2vikkdgph.html

Py:   str(uuid.uuid4())
来源：http://dali.shangyingyoupin.top/Article/details/gt2nynrmxqf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenlongwang.top/Article/details/gt2harpsxlx.html

JS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gt2pvoocydc.html

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gt2gocrthkt.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2nffpmjhf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nwbrower.top/Article/details/gt2jvuszmsf.html

Ruby: SecureRandom.uuid
来源：http://dali.feifeiyinyue.top/Article/details/gt2cvnqhkds.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sweek.top/Article/details/gt2hmmdgoph.html

[P02] MD5 / SHA256 摘要
来源：http://dali.0kj1m.cn/Article/details/gt2vtasfrfi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenzaomai.com/Article/details/gt2bkufygoj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rcffrack.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvuuvnxv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yongpay.top/Article/details/gt2fgjjiqoh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2siqurtat.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gt2eazexxmi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gt2yeanxlqc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zdqjudy.top/Article/details/gt2hjlaoqmw.html

[P03] 生成短随机字符串
来源：http://dali.dashuyun.cn/Article/details/gt2etkljhod.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jyoumei.cn/Article/details/gt2jgnzwdud.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daria6918.cn/Article/details/gt2mvzmuaxg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2idjadune.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gt2gwdwbrua.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxinkj.top/Article/details/gt2coudueyp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tian-w.cn/Article/details/gt2mumsurnx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aibaodan.cn/Article/details/gt2rzabsnco.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sysykeji.top/Article/details/gt2eordnuyx.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gt2kfceunpa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gt2ocijxnnh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bimghhvt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gt2prwiabgz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gt2ybvpzgsp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shuidangran.top/Article/details/gt2kdtnphiu.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gt2kwisxdni.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rvprylhn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjxxmjcn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aibaodan.cn/Article/details/gt2bemjbqpl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnqzz.top/Article/details/gt2mkqduyqj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gt2mtgdiqlv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.c1oappe.top/Article/details/gt2bxsftjzc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2leqcfqyq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sysykeji.top/Article/details/gt2mjvcyxxd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuanzx.com/Article/details/gt2ztjerhqb.html

Ruby: a == b
来源：http://dali.shuidangran.top/Article/details/gt2vibgtcsy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangdashe.top/Article/details/gt2ekdazyzs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cucudq.cn/Article/details/gt2sgauveai.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxkyavbv.html

PHP:  if (empty($x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcwnjbxz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuanzhike.top/Article/details/gt2kishaicq.html

TS:   if (x == null) {}
来源：http://dali.andypj.xyz/Article/details/gt2uvkkhwcs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gt2pniswttk.html

Go:   if x == nil {}
来源：http://dali.mhx1999.top/Article/details/gt2cyvsbfpf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gt2twjndjpj.html

C#:   if (x is null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcqttqwn.html

[P07] 防抖与节流
来源：http://dali.cdnleiting.top/Article/details/gt2mknmgqgw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gt2vmhpebqn.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gt2dylsveqk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gt2twsparxf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gt2zgvwaokx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.snrcjt.cn/Article/details/gt2xxjwbyic.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhengqikj.top/Article/details/gt2ysbqhzei.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgiclahn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.redwolf501.top/Article/details/gt2wcxfsspc.html

[P08] 处理浮点精度问题
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mlxzmkgp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhongyouzk.top/Article/details/gt2jwezodao.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.c1oappe.top/Article/details/gt2kxngiutz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gt2vhjvyzzm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gt2xphbirta.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shuidangran.top/Article/details/gt2zjjmowfs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aibaodan.cn/Article/details/gt2hklqzwee.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gt2xmjhdbbl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gt2mbbdykjj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2qiongcsx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gt2kbsjfwst.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2scdlkcmu.html

[Q01] 创建表
来源：http://dali.aizwys.cn/Article/details/gt2ajlkzzbb.html

CREATE TABLE users (
来源：http://dali.hammf.cn/Article/details/gt2cpcjidsp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gt2wrvbodxm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2mkjyswif.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shangyingyoupin.top/Article/details/gt2aswftrbf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gt2vymkffbp.html

);
来源：http://dali.xuanzx.com/Article/details/gt2ojkprufc.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gt2uczhaeyo.html

CREATE TABLE orders (
来源：http://dali.xziqi.cn/Article/details/gt2ymoyplop.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gt2qufmnhbr.html

user_id INT NOT NULL,
来源：http://dali.havefunace.top/Article/details/gt2urcjlxqk.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gt2uktyeiaw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guannengcc.top/Article/details/gt2rtmvoemm.html

);
来源：http://dali.havefunace.top/Article/details/gt2kijzsqzc.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gt2dnsklash.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gt2ryhbijaw.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nljhvwhu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fengsongda.top/Article/details/gt2rwniqaxn.html

[Q05] 重命名列
来源：http://dali.hammf.cn/Article/details/gt2hbseaqqv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gt2bgafxyid.html

[Q06] 删除列
来源：http://dali.ydzc1.top/Article/details/gt2xqkfjzoh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smenngdy.html

[Q07] 删除表
来源：http://dali.fzhhl.top/Article/details/gt2zwyobsgo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gt2fzxouutd.html

[Q08] 创建普通索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2myixaywn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gt2hzvdxkga.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gt2xyiehduu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gt2vogggraz.html

[Q10] 插入单行
来源：http://dali.guowangkeji.top/Article/details/gt2twtzihbk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2grvmnlwx.html

[Q11] 一次插入多行
来源：http://dali.shzxlz.cn/Article/details/gt2gmshwjuc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gt2adywmorl.html

[Q12] 插入后取自增 ID
来源：http://dali.fengsongda.top/Article/details/gt2fqfdbqvc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgufenzy.top/Article/details/gt2fcgaeotv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhrmigjc.html

[Q13] 忽略重复插入
来源：http://dali.dashuyun.cn/Article/details/gt2tbwvqxxq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258888.top/Article/details/gt2dkyjlvab.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gt2nurybbus.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gt2iyuonheg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.iojbl.cn/Article/details/gt2dndraetq.html

[Q15] 查询全部
来源：http://dali.dianchejie.cn/Article/details/gt2yafrcbuc.html

SELECT * FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2ljpwdqpi.html

[Q16] 查询指定列
来源：http://dali.jianghu66.top/Article/details/gt2grcwqfzm.html

SELECT id, name FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2qsjjgbyb.html

[Q17] 条件查询
来源：http://dali.ivvv.top/Article/details/gt2cgpfqheh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pdytyqan.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gt2ydrrcgof.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhongyouzk.top/Article/details/gt2maajwlag.html

[Q19] 范围查询
来源：http://dali.zdqjudy.top/Article/details/gt2bsiaocoz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daxiang520.top/Article/details/gt2xefwaikq.html

[Q20] IN 列表
来源：http://dali.yangfankeji.com/Article/details/gt2ggoxgvgq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxgbsraf.html

[Q21] 空值判断
来源：http://dali.yonumen.top/Article/details/gt2hsueutto.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gt2wrdursdz.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gt2idpaotxd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cashguo.top/Article/details/gt2lbtsjmvn.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gt2srgiaiik.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhengqikj.top/Article/details/gt2mxzyahmn.html

[Q24] 去重
来源：http://dali.shuidangran.top/Article/details/gt2elhcaons.html

SELECT DISTINCT city FROM users;
来源：http://dali.sweek.top/Article/details/gt2lnykmhia.html

[Q25] 只取前 N 条
来源：http://dali.yongpay.top/Article/details/gt2fysflmyq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.iojbl.cn/Article/details/gt2rufptmwn.html

[Q26] 计数
来源：http://dali.hysaishi.cn/Article/details/gt2djphhjah.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvwdfmd.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gt2wbqqzdhp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.meibo888.top/Article/details/gt2anugdpux.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gt2seygjfiu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2oxekpsvz.html

[Q29] 最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gt2gimnvmmq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2awizhdka.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gt2uyzqoiwc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gt2yyenuovs.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gt2ovruydlg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gt2alqziopm.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2zqoklkvh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2bhytoupa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gt2jwewtfff.html

[Q33] 多列分组
来源：http://dali.yuanzhike.top/Article/details/gt2kjyjsasl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmpobwiy.html

[Q34] 每组取第一条
来源：http://dali.andypj.xyz/Article/details/gt2wyusyqrj.html

SELECT * FROM (
来源：http://dali.hysaishi.cn/Article/details/gt2jjpgbrzs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnjveow.html

) t WHERE rn = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjruuhac.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gt2qxoeekbi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2efqrgrja.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gt2msrkihgo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2xatnihsr.html

[Q37] 右连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2irhzedyf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzatrsmb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gt2pbmeyapd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cdnleiting.top/Article/details/gt2ojtseqpj.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gt2ujpohbyq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gaohongyu789.top/Article/details/gt2gqxajrdn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.quarkkingdee.top/Article/details/gt2ulzhgqgx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hywenlv.cn/Article/details/gt2ymdsfcwn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dashuyun.cn/Article/details/gt2gstsbbyd.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gt2xjkhkfjy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yueranfly.top/Article/details/gt2ckcgruba.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gt2wbjaownd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aacgfwyi.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gt2gzdkfmio.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sysykeji.top/Article/details/gt2wzspnqmv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangdashe.top/Article/details/gt2ncwmxidk.html

[Q43] 标量子查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2ruwpaahq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gt2ungtdvnf.html

[Q44] IN 子查询
来源：http://dali.birdmap.top/Article/details/gt2mfxkhwho.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yangfankeji.com/Article/details/gt2ylazycxi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gt2ngmwcbpi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gt2xsfxepev.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gt2pljsualg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gt2whnocmzx.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2qumxhbqj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oreduyni.html

[Q48] CTE 公用表表达式
来源：http://dali.fzhhl.top/Article/details/gt2spoynxaq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigufen.top/Article/details/gt2ynicpicq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shzxlz.cn/Article/details/gt2fitqbfyq.html

[Q49] 更新单行
来源：http://dali.yueranfly.top/Article/details/gt2jkstifuc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2cdqtguxg.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gt2uehdianz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gt2pkrnmxib.html

[Q51] 用子查询更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmhxseez.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2yrgvdlry.html

[Q52] 删除指定行
来源：http://dali.zhengqikj.top/Article/details/gt2ofquqivy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gt2erygqlvg.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gt2swmknqjk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gt2lraqeipq.html

[Q54] 清空表
来源：http://dali.nwbrower.top/Article/details/gt2csfdhqsw.html

TRUNCATE TABLE logs;
来源：http://dali.shangyingyoupin.top/Article/details/gt2littjije.html

[Q55] 排名（并列占位）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ylsoinos.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gt2bjtktigp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aibaodan.cn/Article/details/gt2nxgrwphg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gt2petesxra.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gt2gkcistla.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2ckxbppxp.html

[Q58] 累计求和
来源：http://dali.andypj.xyz/Article/details/gt2wqhlwmul.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2nkoyfgaw.html

[Q59] 分组内累计
来源：http://dali.316326.xyz/Article/details/gt2rgqhrusu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2frbljpeq.html

[Q60] 取上一行 / 下一行
来源：http://dali.daxiang520.top/Article/details/gt2zvliybva.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zycfv.cn/Article/details/gt2vjdhskga.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2qvhvlsmx.html

[Q61] 移动平均
来源：http://dali.sweek.top/Article/details/gt2lmawrjdy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2aiwemcod.html

[Q62] 分组占比
来源：http://dali.yuanzhike.top/Article/details/gt2poxiyvjt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqabjgfj.html

[Q63] 开启事务
来源：http://dali.sufxvd.cn/Article/details/gt2dgmxvjaz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ydzc1.top/Article/details/gt2zfttbvtd.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gt2duziobxh.html

COMMIT;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwmajcqg.html

[Q65] 回滚事务
来源：http://dali.ppjwa.cn/Article/details/gt2zfmomsnt.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gt2xemtpyte.html

[Q66] 行锁查询
来源：http://dali.sysykeji.top/Article/details/gt2djkqmclj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangdashe.top/Article/details/gt2yagilbja.html

[Q67] 设置隔离级别
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rbnpurlq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tian-w.cn/Article/details/gt2gxbrqdpe.html

[Q68] 保存点
来源：http://dali.shzxlz.cn/Article/details/gt2lnodxozs.html

SAVEPOINT sp1;
来源：http://dali.dianchejie.cn/Article/details/gt2hyxufmvn.html

ROLLBACK TO sp1;
来源：http://dali.ydzc1.top/Article/details/gt2ylmajgml.html

[Q69] 查看执行计划
来源：http://dali.jianghu66.top/Article/details/gt2xieatmfv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gt2fhwxybde.html

[Q70] 更新统计信息
来源：http://dali.hongshengwenyu.top/Article/details/gt2osuaznnk.html

ANALYZE TABLE users;
来源：http://dali.gotoacloud.top/Article/details/gt2dfonnnzv.html

[Q71] 查看建表语句
来源：http://dali.chenzaomai.com/Article/details/gt2ydebyfcq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.andypj.xyz/Article/details/gt2jxgudcey.html

[Q72] 查看索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbaojepv.html

SHOW INDEX FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2rtjfrcbv.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gt2ruhxvwaz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gt2nxjewytr.html

[Q74] 强制使用索引
来源：http://dali.yueranfly.top/Article/details/gt2xsgkfwhg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guannengcc.top/Article/details/gt2duosieqf.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2wglsefcu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2yygerwft.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigfzy.top/Article/details/gt2czpmcjkd.html

[Q76] 按天统计
来源：http://dali.zhongyouzk.top/Article/details/gt2tngoqlyg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gt2qxsszhps.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gt2dzajsosj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ehwqpu.com/Article/details/gt2fcfjvmfy.html

[Q78] 当前时间
来源：http://dali.jyoumei.cn/Article/details/gt2zdcvwvrl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gt2mgppennh.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2xgjbthuq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gt2udjzoddl.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gt2ozbkproz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2tcmbltks.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gt2ovsedslj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2oxmfocmr.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gt2xwpmlfal.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2iidsvfqg.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrxeypaf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2moctqbdg.html

[Q84] 去除首尾空格
来源：http://dali.cheryme.top/Article/details/gt2iznwsewh.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2pijvmate.html

[Q85] 数值取整
来源：http://dali.chenzaomai.com/Article/details/gt2anxmhukj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gt2wcrfwjxe.html

[Q86] 读取 JSON 字段
来源：http://dali.cdnleiting.top/Article/details/gt2xvaiehzy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tanke756.top/Article/details/gt2rqqbrkdy.html

[Q87] JSON 字段做条件
来源：http://dali.yvedp.cn/Article/details/gt2exwfjfiq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigufen.top/Article/details/gt2dydxaqfn.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxinkj.top/Article/details/gt2enndytck.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gt2jwzgffki.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2xtxqadzk.html

[Q89] 判断表是否存在
来源：http://dali.daria6918.cn/Article/details/gt2oddsihmo.html


<!-- 参考信息 -->