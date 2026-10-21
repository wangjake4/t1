代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gtwcdiqstg.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtfkkiumrc.html

[O04] 定义异步函数并等待
来源：http://dali.jyoumei.cn/Article/details/gtpsvvhjia.html

Py:   async def f():⏎    await g()
来源：http://dali.0kj1m.cn/Article/details/gtjsvrghhe.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gtyktxyeac.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtpmpsgdnz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtletqbrdh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuanzx.com/Article/details/gtphnqysks.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aibaodan.cn/Article/details/gteufhcoxf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.svipenyu.cn/Article/details/gtwsgcajcu.html

C#:   async Task F() { await G(); }
来源：http://dali.ehwqpu.com/Article/details/gtvkhwahaj.html

[O05] 并发执行并等待全部完成
来源：http://dali.haohaochexian.top/Article/details/gtgnmsrzeh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gtthhfuhgh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuanzx.com/Article/details/gteestfgfc.html

JS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtdfffkmto.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtguelfdqe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gtjilwviko.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gtgrriqhrl.html

Ruby: threads.map(&:join)
来源：http://dali.havefunace.top/Article/details/gtsmqdqfgc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gzhubu.top/Article/details/gtccqstgwf.html

[O06] 使用进程池
来源：http://dali.mhx1999.top/Article/details/gtrhpcotdc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkprxwbpj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tian-w.cn/Article/details/gtcnsqklro.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtzlqhqriy.html

TS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtmcikzbnv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jiagoushi.top/Article/details/gtvgbxxclu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhixingplan.top/Article/details/gtezkooefd.html

Ruby: // fork 块
来源：http://dali.cheryme.top/Article/details/gtmcnpgsel.html

C#:   Parallel.For
来源：http://dali.cqqwz.cn/Article/details/gtjveighua.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtotvedwju.html

P. 常用工具函数
来源：http://dali.dashuyun.cn/Article/details/gtvctmdxsi.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttywmmqpb.html

[P01] 生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtbtopopwu.html

Py:   str(uuid.uuid4())
来源：http://dali.cashguo.top/Article/details/gtyfsnipqc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gthxkncgzf.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtiirnfqxh.html

TS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtqtulgyrw.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxinkj.top/Article/details/gtcsznfhdy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gogol.net.cn/Article/details/gtpvpeonol.html

Ruby: SecureRandom.uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudyhpcyj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xylfe.cn/Article/details/gtceyspumh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gtiecptcuf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.mhx1999.top/Article/details/gttteiwmdh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.quarkkingdee.top/Article/details/gtltdiwttl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenzaomai.com/Article/details/gtyplpbchh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhixingplan.top/Article/details/gtnghspqey.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gtsbckvhuj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.svipenyu.cn/Article/details/gtoirhuzmi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hywenlv.cn/Article/details/gtwolhkjan.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gtfppkhehs.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gtdivzypib.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tianlin.xyz/Article/details/gtyoqeabof.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtliydario.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gttwjbcseo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtvfzlqsch.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.smart0.xyz/Article/details/gttyzsjanj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jianghu66.top/Article/details/gtlhkxqjuj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuanzx.com/Article/details/gtybidmkeg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yvedp.cn/Article/details/gtbqgrfsqf.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gtbxposwmy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shuidangran.top/Article/details/gtaevfptxd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtezyklfzn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gtzaxkjyqd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gtzbrmzlre.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtrfxevzxe.html

Go:   len(arr);  len(m)
来源：http://dali.yuanzhike.top/Article/details/gtogrgjgbx.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gtvpecwurw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtkaxnkoxt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gthhaifhge.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gtisquofba.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenjidiqi.icu/Article/details/gtfkiyzczh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fzhhl.top/Article/details/gtkmrqmpbb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtrrucmrda.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hongshengwenyu.top/Article/details/gtuhpfgddt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtrgkxpizc.html

Ruby: a == b
来源：http://dali.gaohongyu789.top/Article/details/gtfoeaohrl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ppjwa.cn/Article/details/gtglngwgay.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj202588.top/Article/details/gtauulkjvs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtzzgreduv.html

PHP:  if (empty($x)) {}
来源：http://dali.hywenlv.cn/Article/details/gtxuhuqfmu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gtrmmeohge.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gtxfsictey.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtkbwfapmp.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gtycxgpedp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtnbrzujfg.html

C#:   if (x is null) {}
来源：http://dali.aizwys.cn/Article/details/gtnjkdkaxj.html

[P07] 防抖与节流
来源：http://dali.wangshuangyany.cn/Article/details/gtftjbwsgo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ydzc1.top/Article/details/gthggwnlzk.html

PHP:  // 手写时间戳比较
来源：http://dali.gotoacloud.top/Article/details/gtyijojskm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtgjordtby.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtbmoddsmh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sufxvd.cn/Article/details/gtfvxjrfov.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aizwys.cn/Article/details/gtnsppgjin.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jyoumei.cn/Article/details/gtfbekdtes.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gtjvukdfde.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gtohckjyey.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shuidangran.top/Article/details/gtalnembjg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gtewicsstc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gotoacloud.top/Article/details/gtqaxdftsz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtghbhpdjr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gtyagpiwas.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.mhx1999.top/Article/details/gtgawhvroz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gogol.net.cn/Article/details/gtacqnsrmg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hongshengwenyu.top/Article/details/gtjuuxcwwp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmelmsned.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnqzz.top/Article/details/gtmcfdocrl.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtstrzzavk.html

[Q01] 创建表
来源：http://dali.meibo888.top/Article/details/gtabldqltu.html

CREATE TABLE users (
来源：http://dali.guannengcc.top/Article/details/gtaadxhutu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gtrdwrhsag.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtowbxzwqr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gtccingepa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuanzhike.top/Article/details/gtkicbucog.html

);
来源：http://dali.mhx1999.top/Article/details/gtequedqej.html

[Q02] 创建带外键的表
来源：http://dali.nanxinkj.top/Article/details/gtxkqyyzgj.html

CREATE TABLE orders (
来源：http://dali.0kj1m.cn/Article/details/gtmjcrmnxg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtrhnkjduu.html

user_id INT NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtdrkyeise.html

amount DECIMAL(10, 2),
来源：http://dali.tianlin.xyz/Article/details/gtsvlyrzme.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gtisudrcqe.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhftjadl.html

[Q03] 增加列
来源：http://dali.yvedp.cn/Article/details/gtvgjyaztl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuanzx.com/Article/details/gthwyywxrh.html

[Q04] 修改列类型
来源：http://dali.yvedp.cn/Article/details/gtmmpkpogn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gtytbygokk.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gtlnhiwtsw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsozlsqgt.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gtpinxafpl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cashguo.top/Article/details/gtpzaokgwm.html

[Q07] 删除表
来源：http://dali.0kj1m.cn/Article/details/gtzsnuynms.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gogol.net.cn/Article/details/gtivtkntoc.html

[Q08] 创建普通索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjweeyaa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtgtdnvalu.html

[Q09] 创建唯一索引
来源：http://dali.xuanzx.com/Article/details/gtoajchrgi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gtqamrfjte.html

[Q10] 插入单行
来源：http://dali.guowangkeji.top/Article/details/gtucdyzfzp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ybcxt.top/Article/details/gtmduzqdgw.html

[Q11] 一次插入多行
来源：http://dali.yj20258888.top/Article/details/gttqwxkhzk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gthkbrbpdk.html

[Q12] 插入后取自增 ID
来源：http://dali.gogol.net.cn/Article/details/gtawovznmh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.feifeiyinyue.top/Article/details/gtpyeqzoxj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xylfe.cn/Article/details/gtoqfgfsub.html

[Q13] 忽略重复插入
来源：http://dali.cheryme.top/Article/details/gteknaiuwt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtaliuqtup.html

[Q14] 存在则更新（upsert）
来源：http://dali.gotoacloud.top/Article/details/gtywbssupr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gogol.net.cn/Article/details/gtkoiiqngu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gtftnzeysb.html

[Q15] 查询全部
来源：http://dali.cheryme.top/Article/details/gtmbnqxxov.html

SELECT * FROM users;
来源：http://dali.fzhhl.top/Article/details/gttgyeucvn.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gtykvudrur.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gtxzokipbg.html

[Q17] 条件查询
来源：http://dali.sxryk.cn/Article/details/gtsxolgouz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daxiang520.top/Article/details/gtbhhrvpix.html

[Q18] 模糊匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtqinxghoy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ybcxt.top/Article/details/gtkatlbjux.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gtnmapadoe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sufxvd.cn/Article/details/gtnahskrag.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gtoivyvyml.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtwnvpemqw.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhgppigp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gtiytvaowp.html

[Q22] 排序
来源：http://dali.tanke756.top/Article/details/gtjuxgwxqq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtnejeljzk.html

[Q23] 分页
来源：http://dali.wangshuangyany.cn/Article/details/gtxkybeczu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gtaxwofzco.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gtumnsavny.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtygdysyiz.html

[Q25] 只取前 N 条
来源：http://dali.yj20258.top/Article/details/gtqysvsgmd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gthrieybuj.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gtmhgcjtqf.html

SELECT COUNT(*) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtprkixubq.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtzvxryvbf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtanghkiir.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gtgdddvpcl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtmqzcnvjh.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gtttgrxzmr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtlpgfeqai.html

[Q30] 分组统计
来源：http://dali.cqqwz.cn/Article/details/gtlhmigfgr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtidqcigjh.html

[Q31] 分组后过滤
来源：http://dali.vqdsnc.cn/Article/details/gtiwnpwvmw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangdashe.top/Article/details/gtseuzceue.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtuoiqjqlz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtuggedpjx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gtjptfhegh.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gtljkkipyy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.kuanghao11.cn/Article/details/gtechkhclc.html

[Q34] 每组取第一条
来源：http://dali.sysykeji.top/Article/details/gtwjbiqlzt.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gttulnfrqf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tanke756.top/Article/details/gtrwtwcbxe.html

) t WHERE rn = 1;
来源：http://dali.tianlin.xyz/Article/details/gtvmdusvky.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gtrlrirzaj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtrplfzkfw.html

[Q36] 左连接
来源：http://dali.aizwys.cn/Article/details/gtqpkvrrjq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtooltecej.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gthtnurxct.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gtbsktpudk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dashuyun.cn/Article/details/gtpkbexvhp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gtobhrmnap.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gttjnlywht.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gtjguyoder.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.meibo888.top/Article/details/gtqaqkehuc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.meibo888.top/Article/details/gtzpotniqs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gtynebzdfz.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gtiimluxqi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgufenzy.top/Article/details/gthfmtwrco.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cheryme.top/Article/details/gthnsauyoc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gtzzobdxds.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxuanxn.top/Article/details/gtjfzsscnj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ydzc1.top/Article/details/gthjidearm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtwyhgtklh.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gtngrkupzj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenzaomai.com/Article/details/gtbapczyvx.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvpitcxs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuanzx.com/Article/details/gtyzblikrq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gtrljbcphr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtinrhcizv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnxiangtu.top/Article/details/gthgmxlcfo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtkcydkacg.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gtklrzicle.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gtggpkmhoc.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gtampuvpvk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ppjwa.cn/Article/details/gtgyjwrdal.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gtquqnrgnr.html

[Q49] 更新单行
来源：http://dali.sxryk.cn/Article/details/gtqyiaijpw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gtivsgbpdj.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gtpcdqzrjj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtfkanuaff.html

[Q51] 用子查询更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotpjbaki.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtbcfefcss.html

[Q52] 删除指定行
来源：http://dali.ivvv.top/Article/details/gtrpnuvzdy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtluvxeaap.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gtvzfhcgqq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gtsxhcufxh.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gtrodklklo.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gttdvdmlhd.html

[Q55] 排名（并列占位）
来源：http://dali.zhixingplan.top/Article/details/gtbvpqxgkb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvharjzyz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cqqwz.cn/Article/details/gtutxgtoes.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtkgncqqfz.html

[Q57] 行号
来源：http://dali.sweek.top/Article/details/gtkzojflhj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj202588.top/Article/details/gtkgtxnpik.html

[Q58] 累计求和
来源：http://dali.0kj1m.cn/Article/details/gtpisfypar.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gtotjqhmpj.html

[Q59] 分组内累计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxygmguhh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtvkgfzlvr.html

[Q60] 取上一行 / 下一行
来源：http://dali.pycfn.com/Article/details/gtovstedbs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gtxpqqdovc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtjcfamglg.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gtzjuchsgy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtbfdfyrse.html

[Q62] 分组占比
来源：http://dali.mhx1999.top/Article/details/gtvrjkqcxf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gthqbmptzx.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gtzcvkkiab.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yangfankeji.com/Article/details/gtqmpmuwfq.html

[Q64] 提交事务
来源：http://dali.ivvv.top/Article/details/gtdnnmjdyy.html

COMMIT;
来源：http://dali.tanke756.top/Article/details/gtmzjddiqb.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gticbfgxrm.html

ROLLBACK;
来源：http://dali.gaohongyu789.top/Article/details/gtzxgudqyc.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gtsbhfduif.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gtvhqcpanr.html

[Q67] 设置隔离级别
来源：http://dali.andypj.xyz/Article/details/gtxppusthe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnqzz.top/Article/details/gtmhqhykou.html

[Q68] 保存点
来源：http://dali.xuetiantiany.cn/Article/details/gtvugxxnhh.html

SAVEPOINT sp1;
来源：http://dali.tian-w.cn/Article/details/gtlbusrisk.html

ROLLBACK TO sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpphmzrg.html

[Q69] 查看执行计划
来源：http://dali.yj202588.top/Article/details/gtujewwfyp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jianghu66.top/Article/details/gtbmdaydch.html

[Q70] 更新统计信息
来源：http://dali.chenjidiqi.icu/Article/details/gtjzkuhaxy.html

ANALYZE TABLE users;
来源：http://dali.yonumen.top/Article/details/gtvevtavqc.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gtngsvcclg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gtwmgbknoo.html

[Q72] 查看索引
来源：http://dali.wangshuangyany.cn/Article/details/gtxnhjnimp.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtumesiwob.html

[Q73] 查看表状态
来源：http://dali.ivvv.top/Article/details/gtdzigqxhl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gthzfolujp.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtkurvkaej.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuxming.cn/Article/details/gtzeqloxok.html

[Q75] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtezndbvmx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ydzc1.top/Article/details/gteawxqisl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tanke756.top/Article/details/gtpkxbefub.html

[Q76] 按天统计
来源：http://dali.dianchejie.cn/Article/details/gtquipxerp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cucudq.cn/Article/details/gtsqdthwrb.html

[Q77] 时间加减
来源：http://dali.wangdashe.top/Article/details/gtsohvcujs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gtaxggppca.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gtsfthlxio.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dianchejie.cn/Article/details/gtejdbnnsb.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtbcsgyxpe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gtghueqqla.html

[Q80] 字符串截取
来源：http://dali.yj20258888.top/Article/details/gtxjihqfza.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtzcscbffg.html

[Q81] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gtagthajjo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fzhhl.top/Article/details/gtmftcjfwb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhengqikj.top/Article/details/gtkdszrhrb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtprfqdcdy.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtmkdtjksi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtoykczysd.html

[Q84] 去除首尾空格
来源：http://dali.jqgfzy.top/Article/details/gtuzzasdlj.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtcrnviynl.html

[Q85] 数值取整
来源：http://dali.jinqigufen.top/Article/details/gtcfulyinc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangdashe.top/Article/details/gtuvfkzcks.html


<!-- 参考信息 -->