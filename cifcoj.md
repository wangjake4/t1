代发 wailian999

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtvtcapznl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtohdcsmnv.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gtgtwyaqgt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gtbhraxyvi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwtpxott.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtejpflezo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtxtkbwdns.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gthcpxoldy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtmjjqmvci.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gtiiyzccxj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gteogpdvva.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gtqlkivljo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnqzz.top/Article/details/gtqqzhwrqa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtdtvoqmbe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtjvcijxzy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtwqricdzr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtmunfpooe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gthkghsjmj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gtslpokxqs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtfkmaqcbi.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gtxgyzjxqo.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gtzxbbqfqq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtblchsnen.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtwkjjqagh.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtoujqhvel.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtonrivxqn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gtljqukjym.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gttwwkdqen.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtckqexzza.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gtksjuxdrt.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gtbnedgykl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtvmfffuti.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtwaalasix.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtllitrrbd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtknhtsstn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhiwuduotai.top/Article/details/gtyykwrfnb.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gtecscgnko.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtqcbsmomq.html

[H05] 捕获特定类型
来源：http://dali.fengsongda.top/Article/details/gtljrsmflw.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gtoquuqasr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gtwwtxwvwo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gtuerutwur.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gteoxqymyj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtdspzykgk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gttgrzgtjv.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gtjuxykgio.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptsqewxh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zdqjudy.top/Article/details/gtgpdnajrs.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gtrdpmmzin.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtxhbhhoke.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtrwkllgbm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsreyuunx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gtuklpqume.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gtlhvigswb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gtjkscvkls.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtouqhkolc.html

[H07] 断言
来源：http://dali.dashuyun.cn/Article/details/gtobfuatfj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gtesihvdsp.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gteblimkcq.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtdoqknote.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtpemdyvwc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gtvcebzqxu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuanzx.com/Article/details/gtxeaihyut.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gtyzzysyax.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtzpahghsd.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gteenoydcz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gttyezvywg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.9152youxi.cn/Article/details/gthfockfqn.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotrowsvc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gtaioaawix.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gtyyvnelrl.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gttzkblvsz.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenlongwang.top/Article/details/gtfjqoprif.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gtlfczttco.html

[H09] 带错误码的异常
来源：http://dali.9152youxi.cn/Article/details/gtdgdjfjaa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gtubsmpine.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gtmprpgdyn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbygsayaz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gtfmsfrsgp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gtseurmyza.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sysykeji.top/Article/details/gtdlcnwjhe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gtmzbmhblr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtimdjdsmn.html

[H10] 资源自动释放
来源：http://dali.cqqwz.cn/Article/details/gtpypekmhk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gtwekanrcm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gtqdesacdn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtocsorsbx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtybkzwest.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gtmmiwkfnc.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gtoqxfipce.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gttrylffpc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtlvdfmbdp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtftffbqox.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gtqywffdiz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtfwdjbrtf.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsugdzae.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gttjlkggow.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtdwvtvruh.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtyrkhkezd.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtwmjzfogv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.iojbl.cn/Article/details/gtvolodgga.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gtnlirozyl.html

Ruby: s.match?(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtgonfxvog.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gtyugpuqml.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gtyktrause.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtmmabdceh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gtjdqsrnyq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gttivqvjgf.html

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gtvyoxdfmp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtzkmsddfx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtemxvuexy.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrasrcbyu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtyhnyuvkq.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gtdeandwap.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gttrteurbc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtlthyzyae.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gtiooovodq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gtyldjrjph.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gtartxzxjt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gtuazlldiq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gtglirpgsa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gthplcddkt.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcmhkeqq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xziqi.cn/Article/details/gtlmjdxfnj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoykbpzud.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtcfmhsszp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtmaxdbqnm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtylohjgnn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.316326.xyz/Article/details/gtfzttjlmz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nwbrower.top/Article/details/gtdfoxwtdz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtoyctlrxq.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gthbmvrmbi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gtacsxqbcg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.birdmap.top/Article/details/gtqjrwvsfu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtezfnsapl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtiotxtqtg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gteevpzrsp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtxltgrkxx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtlrxlfavr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gtxkbbsvje.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gtdtpgaist.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtxhcbjxkb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jianghu66.top/Article/details/gtyljrxdsa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtfwmhritx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtfpqqxdko.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtuqkhcnwb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gtzudtslqk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gtijswkmhr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtaorlqrui.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gtpijhdvza.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zycfv.cn/Article/details/gtwuxrpoft.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtomdvkszp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cheryme.top/Article/details/gtgkdnhthh.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gtagtkpfmu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjiidwzz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tian-w.cn/Article/details/gtcloagtqe.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtvzqfkpan.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gtliibwdqz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gtkdiugeyc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sysykeji.top/Article/details/gtrgyqujth.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtovukkwwq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtbpdrjoik.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtemusyzqn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtuqbxoxrn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aizwys.cn/Article/details/gtlpggrirb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gtbmuokxqn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtrqcualxs.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtygaemlfm.html

J. 日期与时间
来源：http://dali.zhixingplan.top/Article/details/gtzmxpkriz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtskfgemvl.html

[J01] 获取当前时间
来源：http://dali.wangdashe.top/Article/details/gtntrkxbmj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tian-w.cn/Article/details/gtxrdwrylh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtujyyscnq.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtxbtgiuoz.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtfpnaefwu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gtcyrsvqdb.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gtkkvejgpj.html

Ruby: Time.now
来源：http://dali.zhiwuduotai.top/Article/details/gtkhmgehmm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gthkqdevpq.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtigrmnkhn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtmmutfrtw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtjkheaapu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gtjjzarndg.html

TS:   d.toISOString()
来源：http://dali.quarkkingdee.top/Article/details/gtgcloyphg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gtsjrmrggb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgufenzy.top/Article/details/gtzaihlnak.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtdoapiiss.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.316326.xyz/Article/details/gtirjqzyjg.html

[J03] 字符串解析为日期
来源：http://dali.xuanzx.com/Article/details/gtgeerdfes.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gtlhqujxgw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cucudq.cn/Article/details/gtjxolsccr.html

JS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtyvrkbzxi.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtsarczxef.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gttlizbjyz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtylbbgfiy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtqumjuick.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtbjxkyeap.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtbvokopif.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gttmvghrme.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gtdvshjqwh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gtuaalkxgd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cucudq.cn/Article/details/gtkshqgeqc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhengqikj.top/Article/details/gthjoosklt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtvjapiutd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gtiurkqmmt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj202588.top/Article/details/gtwslzsxwh.html

[J05] 时间加减（加 7 天）
来源：http://dali.sysykeji.top/Article/details/gteboiayxu.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gtcckcansx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gtgznxivnj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtaqrrykov.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtpilgtkiu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pycfn.com/Article/details/gtejjfbnuj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthccqgcim.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gtggyblzuz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtujysxjza.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gtipibfugd.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gtjwkpcyzb.html

PHP:  $end->diff($start)->days;
来源：http://dali.tanke756.top/Article/details/gtpmaupesp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gtepqtgnem.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gtbchpiohr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtjwyytvqz.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gtldsauktt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dashuyun.cn/Article/details/gtrioxpmdb.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gtzjbyqgfk.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gtkyspgvmb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtrmgvfuoo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zdqjudy.top/Article/details/gtwobvpuom.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtgpjcggbz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtogalltpk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gtmtdemuee.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gttxrkosid.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gttlajxzzd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtonuopkeu.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gtebqwgfjz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gtezbppawx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gtarjhdcxv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yongpay.top/Article/details/gtgbixwnjg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gtbusgumbp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hongshengwenyu.top/Article/details/gtrradxwsj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gtbhzeocim.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.meibo888.top/Article/details/gtuovkcbrt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gtreeblyvi.html

[J09] 时区处理
来源：http://dali.hywenlv.cn/Article/details/gtwxupriai.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.vqdsnc.cn/Article/details/gtqdrmxboh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gtpwsyljds.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtdgdfsedf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtgljfvqdh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gtkbiswbsd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aibaodan.cn/Article/details/gthjoefhaj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gtuajyfxbu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtensfryge.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtoxulqoxj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtafqkelxk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gtdjnjibiu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtekrppyqx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtvxivldct.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tianlin.xyz/Article/details/gtpxjcpozm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daxiang520.top/Article/details/gtmtjztwed.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jlsjyb.cn/Article/details/gtdijakldq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtfmlknbuu.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwsjkpssb.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gttjqusmon.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtekamctqq.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gtbonfnfjd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtminytdrj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gtyndaajlt.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtnbpwgdkf.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtnsowryzy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgfzy.top/Article/details/gtpkedxfar.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtwuybidhx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gtmendeogu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yonumen.top/Article/details/gtivitkhev.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gtihplmfdw.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gttvhmyuen.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xziqi.cn/Article/details/gtpengeuxs.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtyiyraehc.html

TS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphxcvfts.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gtsgmqnadc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtpsvrxtcr.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlhvdyqj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gtbwrjctct.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangtech.top/Article/details/gtidbodjqj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtsrdpqcje.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtvtjabtkg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtckegwldp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gtqpdqnepe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gtxqolnmsx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gthtsrgqsv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gthqydtfaa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gtzwvkwldw.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gtcsltkfbb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jlsjyb.cn/Article/details/gtzkbsgfql.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.birdmap.top/Article/details/gteidvfabm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtqomqelzs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtzkkjiunj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gtxngesdzq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtlxqtwzbn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gttavzmjxm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtjowxwzed.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gtgtbsrtzr.html


<!-- 参考信息 -->