代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gthaujzksw.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gtkaqbdnic.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gtqlczdfpi.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gtzmkhropl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gtuvovgteq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtouzocelj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyiavroan.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtixbvfshe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gtyvldxcry.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmwowwfd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtixlulqva.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gtscsvsfoy.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gtnmfabvql.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtkiviqpti.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtwrgadhqu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoiavhlbi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gtoazwuepc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gtvqqdajwr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gtqggejjwv.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gtlffylaus.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gthjmhtttu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gtdyuwcyvd.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtxmkptcri.html

JS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtyvbfncft.html

TS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtrahnhvsd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.haohaochexian.top/Article/details/gthhnlzrdb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gtzuvdbrrs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gtyqfrijek.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtwgdzqojm.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtxwbusywl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtkmftxdom.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gtmlfvhnhj.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gtyfeofkno.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gtxvezoqjp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gtseglyjyv.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gtywtyxlbq.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuanzhike.top/Article/details/gtdhkfsepl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtuefzxwft.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gtuqecwrlf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigfzy.top/Article/details/gtlxtdoirc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fengsongda.top/Article/details/gtqlonoqkt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gtvvzlknuy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gtzhbkbkce.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gtycxgqnpp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gtdwpqusti.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gtjmmxnnmx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.andypj.xyz/Article/details/gtugiyuiuq.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gtggliiqhq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.smart0.xyz/Article/details/gtyenmyazk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gtowhrjrty.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtdhgwbebz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtfyqitacz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gtuylttnex.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gtnwsnvfoj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gthvzhphze.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtccfeuuct.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtlybmvhih.html

I. 正则表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtmoawgjaq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtoesdhigj.html

[I01] 判断是否匹配
来源：http://dali.jlsjyb.cn/Article/details/gtvcrcyquy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtkipmvfit.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fengsongda.top/Article/details/gttwbjcdhk.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtkfrgncjw.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtfdtapaco.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.quarkkingdee.top/Article/details/gthphmtvhy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtdpgrthez.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtijnuszzz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gtnnryuhkt.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gtsrcppjqr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtwxqifdqm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gtxlomtjmr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gtqgwbajab.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gtwlebqlly.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gtfzanrjlh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gtczfvjwuy.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtwfjtfhob.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gtyzywyfru.html

[I03] 提取捕获分组
来源：http://dali.316326.xyz/Article/details/gtldbjhufc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtyqnofrsc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gtbxejnfzx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.smart0.xyz/Article/details/gtpjaehafj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.bjfxy.top/Article/details/gtqoujgunq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnxiangtu.top/Article/details/gtrkgalgmx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ivvv.top/Article/details/gtbxexfrjj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gtwaibgcun.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zdqjudy.top/Article/details/gtilkhpohd.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gtihvyxqoq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xziqi.cn/Article/details/gtizcwfays.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gtxsaxhhsd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtnwttevyd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtvgslmjhn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtjylnmaku.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtvotpastb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtgbicgkca.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gthaqtryfa.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gteelavbsj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gtjfosbcuq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gtfwfdtqco.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtgiddduvk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtxjbmllcb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtnnemnukg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gtdtboyril.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtqonudbtd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhdoakkc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcslfecl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtoesxittd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gtqcswiisu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gtnlgrrjry.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtpxqjxzgv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtxopxmgay.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgufenzy.top/Article/details/gtuvgzttab.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258888.top/Article/details/gtkdfnddyc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkdtdplx.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gtutoflxek.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zycfv.cn/Article/details/gtjjqbyccs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtpetvvjxz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gtjshwicgv.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gtlmqsguqm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gaohongyu789.top/Article/details/gtsdhmlnbw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aizwys.cn/Article/details/gtmgbafqkh.html

Ruby: s.scan(/error/i)
来源：http://dali.pycfn.com/Article/details/gtzcvcwqxl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gtlcxsrpyw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gtgwjbxtdq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gtijodhqwl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gthoxkibnj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqaabqwfo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtnpexjkzg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtdejyuqzn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gthbswdwtu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gtzsuegthe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtoguzwnhf.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtlwwjjsoe.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gtijruranm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtrfqedmwg.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gtlpqkbnpb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.meibo888.top/Article/details/gtuuschmas.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtlaxdckuq.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtwirayshf.html

TS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gtmqbrwgmz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gtgovakvwb.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gtslcbdzfu.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gtrvvucyys.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tian-w.cn/Article/details/gthxnemdzf.html

[J02] 格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtsanpfdrv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gthszqbtgx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtzcmscygy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gtzhxoowhs.html

TS:   d.toISOString()
来源：http://dali.gotoacloud.top/Article/details/gtcpiqnktn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtopsfgoqg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gtxfhvwflg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gtejqwokcy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gtnsruburk.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gtnizzdwtd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtemdqpikw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gtlajgsmnc.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtjtdvcubv.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtuyjqpsjq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtcautoxyq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gthvokcsiz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtehfhlnto.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.c1oappe.top/Article/details/gtktsfzfgl.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gtpiczbcty.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gticakeqsn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigufen.top/Article/details/gtlsatleew.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gtvcnlelap.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gtxtqweinu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ehwqpu.com/Article/details/gtatigevry.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gttpvrdxrd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gthctsiiat.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hywenlv.cn/Article/details/gtbmayffnp.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gtnhcznqaj.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtqdtxpzqj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gthmvacppj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gttbdpyges.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtyrkqsshm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjppgmgek.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gttcvsqsxc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gtcxnuiyro.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gtjfyihcjp.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gtvzasmkav.html

Py:   (end - start).total_seconds()
来源：http://dali.yanxiufei.cn/Article/details/gtqlpaazeo.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gtyatigygh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gtwogpzrgj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gtmdlussji.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gtcakdmvem.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gtssekfute.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gtsyjxemyy.html

C#:   (end - start).TotalSeconds
来源：http://dali.sufxvd.cn/Article/details/gtilweiahi.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gtzpwrrins.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtpocndfwu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gtbdieyech.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtfenzdqup.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtyiuoxmoi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtwhlulijh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gthvhjyhro.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtufawjskz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtcryotbjm.html

[J08] 提取年月日与星期
来源：http://dali.pengpengdd.cyou/Article/details/gtkgajfzxr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gtlyzfdtbx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gtixspnati.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtnctlzqyw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gtdlcafwjq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gtqtvnexch.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gtdxjiaofz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258888.top/Article/details/gtywoeazop.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gthhslxmjj.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gtkvpbqkyy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gttqnmzqqk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gtjbvajpka.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtoqrwysfv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtovrxludc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gtwmwgugxh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gtjonzpsju.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gtifdzogfr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gteonxiddb.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gtzenurpiw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangshuangyany.cn/Article/details/gtbrdgtjzp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gttagnthzt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gtgdyxusoc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guannengcc.top/Article/details/gtvjoybxcd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guannengcc.top/Article/details/gtmamtcoqg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gtphhmnzqf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtnpxshpwg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gtmmblmets.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjglqoxpp.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gtxpgeonhw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtaqdtzgzq.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gtnvexgcnd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtinqqincx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtyeikpvzg.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gthcecklwr.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtrvzvuyok.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gtynjxofbe.html

Go:   json.Marshal(obj)
来源：http://dali.yuanzhike.top/Article/details/gtugsbzogb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gtpawprpoy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.bjfxy.top/Article/details/gtupywlrgh.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigfzy.top/Article/details/gtxzvpaavp.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gtcoprciuw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ivvv.top/Article/details/gtilhllcrs.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtmeukxkfb.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtxvklgloe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gtqwopyewa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gtjzjqkfwu.html

Ruby: JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtwkakeanm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsaalqvn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj202588.top/Article/details/gtmymusmsf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtugwpxjvd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtqirtaapj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtdchgpqvq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtkvnetvbb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sweek.top/Article/details/gtuoggnify.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gtwfxncnvy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gtihtxvdft.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gtfwdeziaz.html

[K04] 读取 JSON 文件
来源：http://dali.sxryk.cn/Article/details/gttwvfhpqh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenlongwang.top/Article/details/gtftybfmov.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gtizoseqgb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtiisisdpm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtmpapqbov.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtivnsmmdt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtuifdqrbh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ivvv.top/Article/details/gthqarzemq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtbuwnicxn.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gtgtdczzxf.html

Py:   copy.deepcopy(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcdnolwu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daria6918.cn/Article/details/gtnqsgqkyp.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtaegcqlqi.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gthyzoovme.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtajvhatzv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxuanxn.top/Article/details/gtzxhzbock.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gtgggqmlbz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.0kj1m.cn/Article/details/gtsotqibce.html

[K06] 解析 URL 查询串
来源：http://dali.bjfxy.top/Article/details/gtqimfdzgn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gtwmuhkqfv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gtyxnlhjek.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtzirmmwot.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtxnyklcof.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gtzlxbroqa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtjsjoorcy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtcpsypnwb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtafvrtump.html

[K07] 进制转换
来源：http://dali.yanxiufei.cn/Article/details/gtqqgnrmtx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtuqmvmttv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gtzunmgnob.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtkuqjnrnc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtxrqtasnx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtcvjsurfb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigufen.top/Article/details/gtwcmkfgro.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gtthljwhze.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gttesdasco.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gtlhchwdhx.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gttbrouyrq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gtirujtmoh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtdgdjtggc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtqsbumglo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gtaypeaoqm.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gtpxffxodd.html

Ruby: Marshal.dump(obj)
来源：http://dali.zdqjudy.top/Article/details/gtajnbovma.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtrefvmpvg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtgjypnvib.html


<!-- 参考信息 -->