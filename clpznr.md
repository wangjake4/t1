代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guannengcc.top/Article/details/gtzlitqkur.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtttdarjum.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuyscftu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gthycsbdmp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gtkdjncoqn.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gtuosvhiil.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gtdrznnqoy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gtejqzqprr.html

Py:   value = d.get("k") or default
来源：http://dali.gogol.net.cn/Article/details/gtbsfatgig.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtvehdivnc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtushplser.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtnipxnpsw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gtrpymyeeo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gtjlmgtfxd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gtgvtgxjws.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gtvblqrywe.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gtffumhdqd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gthdjpjper.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtoxixnxpt.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtgxcwfhbf.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gthxlfqzik.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gtjnukyhyw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gtjaeszord.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gtnyqviazt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtztnzlwho.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gtkqrkrckl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gtklpbjnfb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cashguo.top/Article/details/gtirgwpfxz.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gtmbmrrjdt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gtpodovoke.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.kuanghao11.cn/Article/details/gtzweeavdn.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gtthcqqudf.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtlmqtgiqn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gtvoehexzk.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gtomkgohan.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtaulghory.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gtqouqqkob.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gtpksqpwps.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gtmzgkbqli.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gtpcgbbixl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtkykqfomj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yongpay.top/Article/details/gtpdjqknxo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gtgylwoisu.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtfsjqyauo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gthylitrqs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gtbmcxfafg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtvzznnjce.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtrtghsfqi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sweek.top/Article/details/gthqhzyusj.html

Go:   defer f.Close()
来源：http://dali.andypj.xyz/Article/details/gtaklbedgu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gttjwvwqed.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gteebosdvx.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtqskzkhzk.html

I. 正则表达式
来源：http://dali.aizwys.cn/Article/details/gtupighqsp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtznkerirg.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gtxtywydfq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtmdlsuxwe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gttjmyrgls.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gttzjnbjkb.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtofbpilub.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gthojtjbsy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gtpuulivda.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtpllxpkts.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtjdvztjhs.html

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gtutvwffwp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtrcxmtqoy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gtniadpmwd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gtpdsthiol.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gtgsmmsizd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gtpoiudzkp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtmkjjdovb.html

Ruby: s.scan(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gtydauepgf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtywtjrnms.html

[I03] 提取捕获分组
来源：http://dali.mhx1999.top/Article/details/gtinwpqibi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhixingplan.top/Article/details/gtrckmvgej.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuxming.cn/Article/details/gtgyvedylo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hammf.cn/Article/details/gtufgosacc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtpbuacsab.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtfefjdsgi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gtggqshonw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gtsuiyhdcc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.kuanghao11.cn/Article/details/gtjtcitkwt.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gtkjbzvmjg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sxryk.cn/Article/details/gtjhpgqevr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gtsjdmgixu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtygwcirlp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gthupaevpw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtkmlwidkg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jianghu66.top/Article/details/gtwrqhskzh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gtffiqunnc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtkqbaosvz.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtqdduyqng.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqoxuxvts.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtxbgdkjsq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtwnbhqlka.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtewxmcktd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gthqboutkr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtxdfpgtpd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtgqiavtnt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sxryk.cn/Article/details/gtyflfiyns.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gtyqkulyaq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvkawisf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnztzvdi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gtlrvemske.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtyjnoxmlv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtwsaejcpi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gtzycerrat.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangshuangyany.cn/Article/details/gtmmiebsbr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtkiznwzdp.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gthadzzywn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gtunlnguww.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtexbprlna.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gtybwnfqzh.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gtvtfdpqhl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gtqkiecglh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gtfabryvya.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuxncjpa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gtebcxhpar.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.haohaochexian.top/Article/details/gtcbljvryp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gteathpdml.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gttvnavdcn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtphinkicv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtpyserfcu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtnqythwtn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ehwqpu.com/Article/details/gtbuwswybo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daxiang520.top/Article/details/gtzdtsudwy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyeyijlf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtepdirfpf.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gttqupguvk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtinbhvdsl.html

[J01] 获取当前时间
来源：http://dali.xylfe.cn/Article/details/gtonqwzhzg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.0kj1m.cn/Article/details/gtgkznvcze.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyuwnkzy.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtkyesgryh.html

TS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gtqlinoxhy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gtscwxxfha.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gtmdpyvccu.html

Ruby: Time.now
来源：http://dali.havefunace.top/Article/details/gthvcpheji.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pycfn.com/Article/details/gtgsmbhxtx.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtxirgewsi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtaxceaifl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtxcnphcfa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gtjxuuyigm.html

TS:   d.toISOString()
来源：http://dali.zdqjudy.top/Article/details/gtcznaoeey.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gtlidiabgc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.feifeiyinyue.top/Article/details/gtxixufgfj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtzyglnmdb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gtfifqpsvc.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gthomzizfx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gtxqzvoyhk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gtlgihhfxn.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtoajstxse.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtjliuvpke.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtskteeuek.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gttukqrwfo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtbbteavyi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gtyzunbvaf.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gtvvgprxsc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tanke756.top/Article/details/gttevnhgcy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhengqikj.top/Article/details/gtjpyxidfr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtofkbabzk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtohhontql.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gtoulztpwe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtdhzelojy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gtlnmxzenm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gtxirmudnx.html

[J05] 时间加减（加 7 天）
来源：http://dali.cheryme.top/Article/details/gtdwpscmbd.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gtbqcxitgh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gtyebhdgxx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gthfgoseto.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtbyddgcrt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gttqhmokvx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gthpfzugmu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hywenlv.cn/Article/details/gtxuqfxpsf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gtgkudvhfs.html

[J06] 计算两时间之差
来源：http://dali.shzxlz.cn/Article/details/gtfwirrawf.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gteabvhygl.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gtzicqbghu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gthszvqamf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gtrfpcafeb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gtmocwrfsy.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gtetuqoakp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gtmmpfmkgr.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhiwuduotai.top/Article/details/gtkolsollj.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gtsmxxkpyw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtorvtyknc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtcjdqbamx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtkjijviut.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtewgkgxcd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.316326.xyz/Article/details/gtkxuhhdju.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gzhubu.top/Article/details/gttrddmddf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtvncvnurb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtwvwxovcn.html

[J08] 提取年月日与星期
来源：http://dali.quarkkingdee.top/Article/details/gtjviwjgln.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gtusdesgqy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoflnxugx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gtlfemuixu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gtwhkawbmj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gticaltrph.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gtcqigohqp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuanzx.com/Article/details/gtppxqgsnr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gtpnvpedeq.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gtmudfkzrl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgufenzy.top/Article/details/gtweejqwlb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gtkhdacwhm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtfiakrphh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtgvfxjfvz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sweek.top/Article/details/gtuatgmcsp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddgrmhxt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gtclfvhuxn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gtpwhdyspk.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwfzgith.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtfuzihzcl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gtzdlzydax.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtyebunpxt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtatiwwpdk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gtydgramlh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gtvkjxyofd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gtodqljyip.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtffnzqtof.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdaofkcqc.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gtjdxpdokr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtevcywmkq.html

[K01] 对象转 JSON 字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwlzmeec.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtaszfcomk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtkcuxxmwh.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtpblmmawi.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtrhtytfqd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gtipsfcopd.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gtlqmhsnhh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhixingplan.top/Article/details/gtrdikebls.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.havefunace.top/Article/details/gtirffdkei.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gtidmrkuuh.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gtzkgfdlyh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdtiylxf.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtjruvmyri.html

TS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtrscwdgqy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtskaxetzy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gttnkbkulw.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtvasxkroq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gtammkhxcx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.316326.xyz/Article/details/gtxdjkltog.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtdclywhtj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtyfdwikml.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtgzcnljgj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtwbpacujv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cdnleiting.top/Article/details/gthuxavyni.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gtwglxmjel.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtcwosgqlv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yvedp.cn/Article/details/gtamwbhghb.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gtokinsztn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xziqi.cn/Article/details/gtmgihmsyf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gtvarlhugd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtnappodoh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtgepajczh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.meibo888.top/Article/details/gtylybqsev.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtkrqsqdbg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj202588.top/Article/details/gtnsuexqeg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtlkybzgap.html

[K05] 深拷贝对象
来源：http://dali.xuetiantiany.cn/Article/details/gtsxbjuivy.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvmnyayf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gtriudnsro.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtskujxfss.html

TS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtkqapzcob.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yueranfly.top/Article/details/gtdjyzhgiq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gtcnyerofg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gtlseyuyrc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gtrxfghiht.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gtvhneursi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gtpmoplkhl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gtwhwzvpzr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtpsbewohr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtssxxyrum.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpekwjqif.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtqvqpvaxt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtvtwtufeb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtmyawvhqs.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gtlxzzzcvj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtvattsods.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj202588.top/Article/details/gtttczzzaj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtmmpdlfrn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtufutvghj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtrbffysru.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hammf.cn/Article/details/gtanjnhrcm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxhiysgp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtkrandjbs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xziqi.cn/Article/details/gtriczgarh.html

Py:   pickle.dumps(obj)
来源：http://dali.daria6918.cn/Article/details/gtmmiqiast.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gtimlxvwqp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gttgbmojgz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtorkcgwao.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gtescavbde.html

Go:   encoding/gob
来源：http://dali.jqgfzy.top/Article/details/gtvwcyaeon.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtgekrzdrw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtthtlitog.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtiiurdypn.html

L. 网络请求
来源：http://dali.yongpay.top/Article/details/gtlipkypyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtlxtlvptt.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gtkcikidxd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gtzqarjcrt.html


<!-- 参考信息 -->