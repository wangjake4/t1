代发 wailian999

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gtjxvggggh.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gthtvagkob.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjngmaxlh.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhrglycn.html

TS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtmmtuhwhl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtmfvbafkn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gtvaeuwcon.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gtuivrulyr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtoypcuqgm.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gtskftwezn.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gtzuikzbpx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfikqxnhc.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gthdgdztvu.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtihilillt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtsjvapxqk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gtlvphkpeu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtlikobolw.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gtpqkevnkn.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtlqupzerf.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gtwvmnkrae.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gtbjmtpylh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtnvimpilc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohiudugf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtulopawjw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gtvenmsswq.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gtzxvaiudb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gtvwavlfvd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gtgspjfmke.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gtfidkzxxj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtnileivmo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtsehjjfmv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtxibkevhl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gtbxrlhshm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gtiegzzemc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gttjxnptoq.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gtthckmfer.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gtrjmudass.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gtwiliupuy.html

PHP:  assert($x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtdfufquzh.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gthiepdeqw.html

TS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtkbvvqjaf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtqgccujqi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxuanxn.top/Article/details/gtcurfhwey.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gtnfypslpa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtwyjtcuqc.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjwpjalw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gtlcvmqplw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gtidfbtoaw.html

JS:   e.message;  e.stack
来源：http://dali.gaohongyu789.top/Article/details/gtrbzipono.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gtbamdpbzc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aizwys.cn/Article/details/gtwwpvnrkf.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gtypeqlsnt.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gtlrhxknuf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtnidoifih.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gtjnesytua.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yonumen.top/Article/details/gtpzkenvsg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gtxfrpqxjj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gtvuesyjzv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gtvyszfpwk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtlimqyacm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gtixachxql.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gtcjzvamhj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtszpppkni.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gtjottcshj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gtjuozlozt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gtdajhlpjz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtpnlzcuwd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtoyruargd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdusdfvis.html

Go:   defer f.Close()
来源：http://dali.aibaodan.cn/Article/details/gtgglpvrvn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gtmmvnxmre.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtxymlhjkf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyynekyty.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gtzyoishch.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gttpuvmbsm.html

[I01] 判断是否匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtelwrgrom.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtxdwxkqjj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gttxtvhlif.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtbgutpmzp.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtbckcpvjs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daria6918.cn/Article/details/gtxoietzxq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yvedp.cn/Article/details/gtkqhgewjx.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtvkbzuadn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtuzfxadav.html

[I02] 提取所有匹配
来源：http://dali.zhoulong.xyz/Article/details/gtrhiwkqzn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtcaweuxcw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gtziioxsmi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gtjjcisxkq.html

TS:   s.match(/\d+/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtedvjeykr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aibaodan.cn/Article/details/gtoylouzyi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtcjshwojh.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtzutlxcds.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.havefunace.top/Article/details/gtbkisecfh.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gtyizzfvzo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fengsongda.top/Article/details/gtofsbagbb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gthysytkfo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gtdgrtgxts.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gtglhuipec.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gtfrawdntz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gtvdbipmox.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxinkj.top/Article/details/gtswnxkavj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gtiggxdwjk.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gtanbbsytb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gtcmejyfku.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gtuxojgjmy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtrgqkdypp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtxovptmfl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtzyrfcdol.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gtmjemsuqv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuxming.cn/Article/details/gtzjmmcjgh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtjkkjdcwl.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gtqwuagjag.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gtyctkxbvq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdlbwlex.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtkkteiipq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtbtvvajhy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jyoumei.cn/Article/details/gtzhrravjx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtfqccggty.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtothksxce.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gtwenlqmmo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gtwoufaver.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtjapuobep.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gtfquqsese.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtpbzpyftb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtfmgzgiwz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzkhedaj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shangyingyoupin.top/Article/details/gtztdrewun.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gtgdwiabty.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gttrtctwkp.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gtlpwmzwrw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jlsjyb.cn/Article/details/gtgidjoihp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtklnufaqy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhiwuduotai.top/Article/details/gtkbijirbe.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtznwzqlxb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.andypj.xyz/Article/details/gtvsgyqant.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gtnkivtejw.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gttvrbmukc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gtphiicjby.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtgthznkgp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gtcmdakcex.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gterhfxgfq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnpkamuj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtljhllbnu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtkfuaemnv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aizwys.cn/Article/details/gtxokeyvdw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gthjtuvkkx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gttlhzwofl.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvkmjbyds.html

J. 日期与时间
来源：http://dali.aizwys.cn/Article/details/gtoafxakku.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtwagtxzkz.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gttmfdrjxy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gtzrbmjvbv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtreqncwie.html

JS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtxlafliqp.html

TS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtxcdgknak.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhongyouzk.top/Article/details/gtznzhxuig.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gtnumbqslq.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gtlsrltvar.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gtpgzsprqi.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtznhjawoa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtxehkizlr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtohqbfzgi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gtyjvcsdeg.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gtnriyhwyy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gtauyjungt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gtsdvblxom.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gtmxrprjxo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gtyvnlgxir.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtldvsmcuj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gtftcomtrv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dianchejie.cn/Article/details/gtojngopiv.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtqpzbbzwy.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtahijkpqk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtuttunsyw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtuqyrubni.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtokkccyei.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gtgbibwdun.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gtdpgnsjkg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtlvnspvnx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtuwxsjfyi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ivvv.top/Article/details/gtcrsslfbr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtwzjcajmj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gteccwjtbs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gtkiitiyyx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gthpdzougb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hywenlv.cn/Article/details/gtdmnbotbg.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gtvaoyziwb.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gtemlzhfwx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cheryme.top/Article/details/gtjmxppqih.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfavwsnrr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtrcvmuxjr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gtdqhqatrx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gtaqtwpyuo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daxiang520.top/Article/details/gteejaxffe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtnpnmctwj.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxgltpju.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gtsqmtqzgr.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gtdzyyhciz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gtryqgiavp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gtpsrdozrr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cashguo.top/Article/details/gtsxornhll.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gtmkjrpejx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gtyocekpqj.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gtdpxchofd.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gtgmlmtane.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtiapfblln.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gtzwirbsji.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtacxztojm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtxauyunwb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gtdycdpwgf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.c1oappe.top/Article/details/gtoduapkil.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gttaqvdbmt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtrcnfmals.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gtqphzvthi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcanakvdt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gtpkvlfsav.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gtujwgnbta.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ppjwa.cn/Article/details/gtildibswh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.c1oappe.top/Article/details/gtkrtghdqb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gtnkviabur.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sysykeji.top/Article/details/gtqxwjwwox.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gtepqhtavd.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gttbavlvza.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gthzrecpts.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yangfankeji.com/Article/details/gtpbuewrmw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtvizkswpf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtqtlrozss.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gtyurbmgww.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gthcqrrulg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gtxhwravjt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cqqwz.cn/Article/details/gtzaynaaae.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gtaywknmjh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gtunnywoiu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtuivcyltt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtiopcybes.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xylfe.cn/Article/details/gttcrklswa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gtyiaqdvmc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gtxcldexge.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gtrjtihfxv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gteyqrdgxn.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtisugwymx.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gtvysbyjee.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtbixelypp.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhongyouzk.top/Article/details/gtzrwoxlak.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtuvpdkkya.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtwymzmtyi.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtknskbeml.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtkaaoahrx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zycfv.cn/Article/details/gtaacnezql.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gtuejsejeo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gtfjpbzoif.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gtuapauwjo.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gttdjypfys.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gtfndzaupn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gtgyeqnrtr.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtvcigblcv.html

TS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtulyxfzly.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtetqjvfvl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtyhxlawok.html

Ruby: JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtojopeptj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gtgfmamucy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gtmxnakkol.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtzylryoql.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtgprrduty.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtqbiowylp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtkszpzxqi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gthcklikej.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.andypj.xyz/Article/details/gtamechybb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuanzx.com/Article/details/gtqyzntupr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gthiwssrab.html

[K04] 读取 JSON 文件
来源：http://dali.0kj1m.cn/Article/details/gtnissfzqb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gtquztyyjc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gttgfxpkat.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtiynatues.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gthueisoha.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtropfdtbu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtilklnfdn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtmxtnajzw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gtvmeaqqmk.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gtbpdsywcv.html

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gtgamzfzax.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sysykeji.top/Article/details/gtnwsrefnz.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gttydbmafw.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtxsmxaaly.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljdfygwe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gtenecdzhd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuanzhike.top/Article/details/gtoghjwtlg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gtrgggdhhd.html

[K06] 解析 URL 查询串
来源：http://dali.yvedp.cn/Article/details/gtwzmhgfkj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtyryhmpsa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gtcyffjyjm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtitiwdwqr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtwqxgkggt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtjvnczlld.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtaufkqwvf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtpjclhgdd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtlwjfgpqv.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gtubkjpjcv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtgvpjwzgy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.andypj.xyz/Article/details/gtsxyeoyiq.html


<!-- 参考信息 -->