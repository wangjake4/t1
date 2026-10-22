代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.9152youxi.cn/Article/details/gt2czksvuqe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gt2agdyulzl.html

C#:   async Task F() { await G(); }
来源：http://dali.ppjwa.cn/Article/details/gt2isnqdraa.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gt2btwbzwla.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fzhhl.top/Article/details/gt2ucriwuye.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgfzy.top/Article/details/gt2uvwxewzg.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebcooqyc.html

TS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gt2iyfzqhip.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gt2helzthbc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gt2acmqfwls.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gt2adzksmgk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shuidangran.top/Article/details/gt2toepmzho.html

[O06] 使用进程池
来源：http://dali.cucudq.cn/Article/details/gt2ewhbdzjq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hfpthk.cn/Article/details/gt2vpghcbxg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jiagoushi.top/Article/details/gt2xcofuikj.html

JS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gt2iomrwroj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gt2krbywben.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj202588.top/Article/details/gt2cqktlisd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gt2loryjmth.html

Ruby: // fork 块
来源：http://dali.feifeiyinyue.top/Article/details/gt2zuyseqew.html

C#:   Parallel.For
来源：http://dali.zhixingplan.top/Article/details/gt2biftjrkx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2xfafovap.html

P. 常用工具函数
来源：http://dali.daxiang520.top/Article/details/gt2yrtvfcfh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2jktmgfez.html

[P01] 生成 UUID
来源：http://dali.shzxlz.cn/Article/details/gt2qgreqxer.html

Py:   str(uuid.uuid4())
来源：http://dali.yanxiufei.cn/Article/details/gt2wbhyhvch.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.havefunace.top/Article/details/gt2lnfizggu.html

JS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gt2omcmzwpa.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gt2qmiruefp.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umwbgcyv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shzxlz.cn/Article/details/gt2lpnuepkn.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2uqkccchn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guannengcc.top/Article/details/gt2mjwsjqop.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sufxvd.cn/Article/details/gt2brqhdhvi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gt2hqryahya.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdytexab.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shuidangran.top/Article/details/gt2svjszack.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangdashe.top/Article/details/gt2wvgioxua.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fengsongda.top/Article/details/gt2ftrvtzve.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gt2ksntqdhl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2waelklvp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.andypj.xyz/Article/details/gt2faduafjr.html

[P03] 生成短随机字符串
来源：http://dali.gotoacloud.top/Article/details/gt2rbgmuchc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gt2shqyhqwg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenlongwang.top/Article/details/gt2jofnnnsx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gt2yisdfnjd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndbrxzan.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gt2wjhwwpzx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj202588.top/Article/details/gt2aqzzwbuw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guannengcc.top/Article/details/gt2pxkzhnla.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gt2edkodzvh.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gt2lreymjxf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gt2dlcowrek.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2eowvbymc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gt2zsndqctv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gt2vwzsznsr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gt2uwxxmfbn.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gt2qjsezlmk.html

Ruby: x.length;  x.size
来源：http://dali.xylfe.cn/Article/details/gt2rwdjpihe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zycfv.cn/Article/details/gt2wicnjnym.html

[P05] 判断两个对象内容是否相等
来源：http://dali.bjfxy.top/Article/details/gt2rsrjxkoi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gt2usxtitmx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gt2txgwjlii.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shzxlz.cn/Article/details/gt2amckzllo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gt2vvluuvuh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gt2csgrbocv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jyoumei.cn/Article/details/gt2cnktdtjm.html

Ruby: a == b
来源：http://dali.dashuyun.cn/Article/details/gt2xonulzyu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hywenlv.cn/Article/details/gt2zkgfeimi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gt2ixssdhkc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xziqi.cn/Article/details/gt2uwtuqzdh.html

PHP:  if (empty($x)) {}
来源：http://dali.ivvv.top/Article/details/gt2ivoauiuy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ehwqpu.com/Article/details/gt2ejrcomhb.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gt2fggjaauk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gt2yuxmkcsy.html

Go:   if x == nil {}
来源：http://dali.yonumen.top/Article/details/gt2yhdlzmcg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jianghu66.top/Article/details/gt2pjjonqjw.html

C#:   if (x is null) {}
来源：http://dali.yueranfly.top/Article/details/gt2glrnawsk.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gt2eqebuqrc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gt2btwstvco.html

PHP:  // 手写时间戳比较
来源：http://dali.birdmap.top/Article/details/gt2gosjqiwb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2lpopwtrt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gt2wstcetly.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gogol.net.cn/Article/details/gt2wllldofi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhixingplan.top/Article/details/gt2pfvvovyu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.havefunace.top/Article/details/gt2wredhuap.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xylfe.cn/Article/details/gt2eoowttxp.html

[P08] 处理浮点精度问题
来源：http://dali.hywenlv.cn/Article/details/gt2hmhrrxgz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hysaishi.cn/Article/details/gt2wlarljdp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gt2ozdrxxmc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yvedp.cn/Article/details/gt2hibtfkgg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gt2lcwvxkfp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.snrcjt.cn/Article/details/gt2cameqdux.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jiagoushi.top/Article/details/gt2bscivhvc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhoulong.xyz/Article/details/gt2gcorcbpr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.iojbl.cn/Article/details/gt2mfhveoek.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2whimpldz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yangfankeji.com/Article/details/gt2nhlujwcz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2yeabmquw.html

[Q01] 创建表
来源：http://dali.fengsongda.top/Article/details/gt2vdljdmhu.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gt2kecgqfsa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gt2ugioruyv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gt2ppfwtdwx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hywenlv.cn/Article/details/gt2rdpvlkxq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.quarkkingdee.top/Article/details/gt2wtnwrosk.html

);
来源：http://dali.cdnleiting.top/Article/details/gt2lqchzgsc.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uukeocct.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gt2pjpjdkol.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibvsntum.html

user_id INT NOT NULL,
来源：http://dali.pycfn.com/Article/details/gt2fzmrcxhs.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangtech.top/Article/details/gt2luuzdyci.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yanxiufei.cn/Article/details/gt2djgnixin.html

);
来源：http://dali.sysykeji.top/Article/details/gt2wcisawgi.html

[Q03] 增加列
来源：http://dali.gotoacloud.top/Article/details/gt2svopvbmr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.haohaochexian.top/Article/details/gt2uafzeahw.html

[Q04] 修改列类型
来源：http://dali.bjfxy.top/Article/details/gt2nczqntos.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gt2gdxficed.html

[Q05] 重命名列
来源：http://dali.yuxming.cn/Article/details/gt2lzpkxcvs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2euahdkoi.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gt2mojhlzdn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daria6918.cn/Article/details/gt2ddzeheym.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gt2phkvnuxc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.316326.xyz/Article/details/gt2iuoljbzd.html

[Q08] 创建普通索引
来源：http://dali.kuanghao11.cn/Article/details/gt2peyhetmv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gt2rxfvvctx.html

[Q09] 创建唯一索引
来源：http://dali.316326.xyz/Article/details/gt2xfypyabj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gt2mlqjbmyi.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbhjofyl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gt2cpfkxmll.html

[Q11] 一次插入多行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihulkcsm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gt2lmergjvi.html

[Q12] 插入后取自增 ID
来源：http://dali.gzhubu.top/Article/details/gt2jotiuffi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jianghu66.top/Article/details/gt2xnikearq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daria6918.cn/Article/details/gt2vwcrgdqi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgdeamq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gt2bdbntopx.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gt2rditucgc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigufen.top/Article/details/gt2ysifzvwz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hywenlv.cn/Article/details/gt2raocoens.html

[Q15] 查询全部
来源：http://dali.pengpengdd.cyou/Article/details/gt2apbzvuxc.html

SELECT * FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2xfzoishi.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gt2ylgdklvs.html

SELECT id, name FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2zkjbtppz.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gt2rpfjvqdz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ydzc1.top/Article/details/gt2pipcexqv.html

[Q18] 模糊匹配
来源：http://dali.pycfn.com/Article/details/gt2yhroudvg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dashuyun.cn/Article/details/gt2pvlxckyq.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gt2ooyjqyqr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gt2zcvgugkh.html

[Q20] IN 列表
来源：http://dali.wangshuangyany.cn/Article/details/gt2xnmwtwqk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fengsongda.top/Article/details/gt2ntxmpmia.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gt2dadlasbb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gt2cwdyrdmc.html

[Q22] 排序
来源：http://dali.hnqzz.top/Article/details/gt2drjndvsf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yongpay.top/Article/details/gt2cjehzbnn.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gt2zcrhcoca.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gt2azgzmdtv.html

[Q24] 去重
来源：http://dali.jqgufenzy.top/Article/details/gt2kiyywzel.html

SELECT DISTINCT city FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2lxyrfrxw.html

[Q25] 只取前 N 条
来源：http://dali.feifeiyinyue.top/Article/details/gt2fyiobtib.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcfyieie.html

[Q26] 计数
来源：http://dali.pycfn.com/Article/details/gt2grdkjoqx.html

SELECT COUNT(*) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2olxsacxa.html

[Q27] 条件计数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhjpadqd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2ezeettkg.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxurdjvh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2uoeuhhsd.html

[Q29] 最大最小值
来源：http://dali.dianchejie.cn/Article/details/gt2sgubylgh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2eiqlqygl.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gt2povkweld.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gt2feyupksn.html

[Q31] 分组后过滤
来源：http://dali.nwbrower.top/Article/details/gt2inshionm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.birdmap.top/Article/details/gt2hmtmeake.html

[Q32] 分组拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2lmdhqpgi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2niuwxmyp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zdqjudy.top/Article/details/gt2ysvlherg.html

[Q33] 多列分组
来源：http://dali.0kj1m.cn/Article/details/gt2kswtnoua.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yangfankeji.com/Article/details/gt2hghrjlal.html

[Q34] 每组取第一条
来源：http://dali.bjfxy.top/Article/details/gt2iqysuxbq.html

SELECT * FROM (
来源：http://dali.ybcxt.top/Article/details/gt2gcwpbccu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.redwolf501.top/Article/details/gt2pndytweb.html

) t WHERE rn = 1;
来源：http://dali.xylfe.cn/Article/details/gt2crqblsrc.html

[Q35] 内连接
来源：http://dali.xuanzx.com/Article/details/gt2nnfhbgdi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gt2sqbbijmz.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gcxstlig.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gt2tzcselbw.html

[Q37] 右连接
来源：http://dali.sxryk.cn/Article/details/gt2tqwtsckk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhengqikj.top/Article/details/gt2fcbzhsip.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fzhhl.top/Article/details/gt2gwpwryhd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sysykeji.top/Article/details/gt2vtcesuby.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gt2izjwcgnn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ivvv.top/Article/details/gt2dsttgjci.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gt2qwrmfmwe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zycfv.cn/Article/details/gt2sutiwyav.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxomlkju.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gt2eyqelnff.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtggmjwc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gt2nbqttvrd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.bjfxy.top/Article/details/gt2flkbowfc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gdltvdps.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gt2plcogiqf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gt2rwanrfmo.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gt2hofafnsv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npfchfzo.html

[Q44] IN 子查询
来源：http://dali.xinyue.icu/Article/details/gt2zpenkndq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ydzc1.top/Article/details/gt2azldrurf.html

[Q45] EXISTS 判断存在
来源：http://dali.daria6918.cn/Article/details/gt2ofkcuree.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gt2ruwucski.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gt2wmqgryfg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gt2uivfaflf.html

[Q47] 与平均值比较
来源：http://dali.tianlin.xyz/Article/details/gt2fiwgxvqj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gt2ifbllxia.html

[Q48] CTE 公用表表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2ukuhqhbp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hysaishi.cn/Article/details/gt2qxkuiyml.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gt2hhbcrbgm.html

[Q49] 更新单行
来源：http://dali.gogol.net.cn/Article/details/gt2oswtolwc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gt2irdrixkt.html

[Q50] 批量更新
来源：http://dali.zdqjudy.top/Article/details/gt2wyqdmubw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gt2keqohsww.html

[Q51] 用子查询更新
来源：http://dali.sxryk.cn/Article/details/gt2hrkcxfrg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nwbrower.top/Article/details/gt2htybopkp.html

[Q52] 删除指定行
来源：http://dali.meibo888.top/Article/details/gt2vloeoccb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2sufpdnvz.html

[Q53] 按条件删除
来源：http://dali.hfpthk.cn/Article/details/gt2svsotpyh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ybcxt.top/Article/details/gt2uvwufjgt.html

[Q54] 清空表
来源：http://dali.ydzc1.top/Article/details/gt2gixkynrr.html

TRUNCATE TABLE logs;
来源：http://dali.andypj.xyz/Article/details/gt2hnfuikar.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gt2bckmootq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gt2xwdtobqt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zdqjudy.top/Article/details/gt2ivornpdf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.andypj.xyz/Article/details/gt2gknooirs.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gt2vncrkfeq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2ynhtcgra.html

[Q58] 累计求和
来源：http://dali.kuanghao11.cn/Article/details/gt2hbtlmtlg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2dkurvqxr.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gt2jvaorazt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2gbdpplls.html

[Q60] 取上一行 / 下一行
来源：http://dali.sufxvd.cn/Article/details/gt2dyrwlxyo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gt2ipwsooxz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2lqpvfquy.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gt2uwjvnfxq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2fvtagtrw.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gt2jibsjuwt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gt2twiulhcb.html

[Q63] 开启事务
来源：http://dali.haohaochexian.top/Article/details/gt2cxaydlwg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnqzz.top/Article/details/gt2btmswtvr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qzopzkzn.html

COMMIT;
来源：http://dali.ehwqpu.com/Article/details/gt2okbnifql.html

[Q65] 回滚事务
来源：http://dali.gaohongyu789.top/Article/details/gt2krhhobpj.html

ROLLBACK;
来源：http://dali.gzhubu.top/Article/details/gt2ftctbqow.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gt2awnhreru.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gt2yqoeoqbw.html

[Q67] 设置隔离级别
来源：http://dali.ydzc1.top/Article/details/gt2jgkibpdt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrydxslv.html

[Q68] 保存点
来源：http://dali.nanxinkj.top/Article/details/gt2kuktsaru.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2idxtpmry.html

ROLLBACK TO sp1;
来源：http://dali.fzhhl.top/Article/details/gt2qvkobdnd.html

[Q69] 查看执行计划
来源：http://dali.birdmap.top/Article/details/gt2kxgrbzvs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gt2brsvyjab.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gt2ekmnssmx.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gt2xfuddhcz.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gt2bwupomnd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.quarkkingdee.top/Article/details/gt2heexyhwi.html

[Q72] 查看索引
来源：http://dali.daria6918.cn/Article/details/gt2tlschnja.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2qqaxilzv.html

[Q73] 查看表状态
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytmmvwwn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zycfv.cn/Article/details/gt2toiwygsf.html

[Q74] 强制使用索引
来源：http://dali.cqqwz.cn/Article/details/gt2lzbfeydo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gt2cotgmzns.html

[Q75] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gt2nxpbykst.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2imauktwi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yonumen.top/Article/details/gt2ohihpljj.html

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gt2qwjeivbq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbukrhiu.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gt2qgsseqcw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhongyouzk.top/Article/details/gt2olfntcjs.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjhrjhrm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daxiang520.top/Article/details/gt2awqsalvd.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gt2adadisyw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.0kj1m.cn/Article/details/gt2piwlzjit.html

[Q80] 字符串截取
来源：http://dali.kuanghao11.cn/Article/details/gt2fojtsyxs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2qmqkdmtw.html

[Q81] 字符串替换
来源：http://dali.yj20258.top/Article/details/gt2jjgbzerd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2tyaptrix.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gt2wsnanuhv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2xfbitiad.html

[Q83] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2fvonjnlo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2kejhlouy.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncsptqva.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2rejhzpbo.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gt2szostpxz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gt2lccpstte.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gt2pisrriwn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2alzwvejo.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigfzy.top/Article/details/gt2jnzdjyqy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gt2iykxfdro.html

[Q88] 行转列（条件聚合）
来源：http://dali.mhx1999.top/Article/details/gt2yqeubdqk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvjshzpr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2alpsdrdu.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynegpxzz.html


<!-- 参考信息 -->