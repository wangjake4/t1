代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtfjwmjycz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gtphbodtlw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtjcjjtlbh.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gtonlyzywp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtowknoyuh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gthyteqdbg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtcqeqzjho.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdbxrttfh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtriqvzrhy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gtopineeye.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gteghnxdvr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtzvhfhfqb.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gtslfmwjjs.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gtqrrjtqxj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtcelzurit.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtsuvctsqa.html

TS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtgxgqjlrv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtnnvhrvej.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xinyue.icu/Article/details/gtekqcjryj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gtkewonurz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtozksycex.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gtqgfjjhzd.html

Py:   class MyError(Exception): pass
来源：http://dali.sweek.top/Article/details/gtyghixhay.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gthfrbglui.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtkzdwsnbs.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnleeafsl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gteboexyyw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtiemfhdht.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gtnbxlnhcb.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gtkdfcqnvc.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gtpnbzgaso.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gtonxffeha.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.mhx1999.top/Article/details/gtgocmlfhu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtbaimkgwv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtbtqvjzcg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gtmnlagxmr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gtlhqbdgqp.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gtkldnknem.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtgkrgdrbl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.birdmap.top/Article/details/gtwyyntckx.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gtnklsrdps.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtspappgmp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gtgicvkxab.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtojxhuceg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gtznfbuxst.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gtbgtdjvwy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gtienwumkv.html

C#:   obj?.A?.B ?? default
来源：http://dali.snrcjt.cn/Article/details/gtstvzrksf.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gtatkxsukc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtshutmazy.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gthslrukpj.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gttvavtfuk.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtgfdwkina.html

Java: assert x > 0 : "必须为正";
来源：http://dali.316326.xyz/Article/details/gtbgwdzkjw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daxiang520.top/Article/details/gtfjhkrewm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gtegcpmhha.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtwjxczops.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmpsyfno.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenjidiqi.icu/Article/details/gtwcwvytra.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenjidiqi.icu/Article/details/gtkclenhgc.html

JS:   e.message;  e.stack
来源：http://dali.redwolf501.top/Article/details/gtonnaikit.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtkaiagtnr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttpgetge.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gtxrtbfrrl.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gtffpyskra.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gtznnvgaty.html

[H09] 带错误码的异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyrbztom.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gtszxdsays.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.quarkkingdee.top/Article/details/gthrpiyeiy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shzxlz.cn/Article/details/gteyurhsuk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnxiangtu.top/Article/details/gteaqmztcy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvefpbhar.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gtjcntrtts.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlpxaypv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtorzwgvus.html

[H10] 资源自动释放
来源：http://dali.snrcjt.cn/Article/details/gtpumvllre.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ehwqpu.com/Article/details/gtwwgcjvdv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cqqwz.cn/Article/details/gtsejdhvtl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtkqbnxuuz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrltjvkac.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gtkviuuktr.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gtzocqsche.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzapxwhg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gtgrexbhne.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkkaxofrk.html

I. 正则表达式
来源：http://dali.redwolf501.top/Article/details/gtkezwclai.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtaeolmhul.html

[I01] 判断是否匹配
来源：http://dali.pycfn.com/Article/details/gtoomaujgc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtbgenvjri.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldmjciyg.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtqrikunuo.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtfejpfkpd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gogol.net.cn/Article/details/gtnpnwluru.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zycfv.cn/Article/details/gtbcdydfub.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtpfwhvigm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtjecptzjv.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gtzabbdxzn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtffzsmxsm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gtgibtrygs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gtlmkrelfl.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtuhcimvbu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gtkuelrwxx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gtqkrrkhye.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtiqljjgrd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cashguo.top/Article/details/gtiuelsluv.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gthdwnotnz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gtpmckysak.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gtseksfgwr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hywenlv.cn/Article/details/gtrycfgwax.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gtselebqom.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gtcixwiynm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangdashe.top/Article/details/gtpsiausqm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gtaridbezi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.316326.xyz/Article/details/gttydxxxdr.html

[I04] 正则替换
来源：http://dali.vqdsnc.cn/Article/details/gtvvepnctf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shuidangran.top/Article/details/gtptipeaed.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gtqwtbrbtd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtrbrpxkxl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gtwvgyotdo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtqezsngei.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtpnszabcz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sweek.top/Article/details/gtutefzwbh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtzcglaxpt.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gtqxtocgin.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxecjbxi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gtsudcrlvq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtqesvpuof.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtqlfezckq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gtoekkvapo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtymhcsguh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtzkrmytro.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gtzlncndqt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gtpehmhssa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtfaacfrxs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jyoumei.cn/Article/details/gtdvmuogzc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtgtjnkcyn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtnpukqnuf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwvyizeg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gtwzuruxdv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gtjziuppin.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gthohtaqes.html

[I07] 忽略大小写与多行模式
来源：http://dali.c1oappe.top/Article/details/gtljvqtbbg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhongyouzk.top/Article/details/gtkahckdnm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtttpedmti.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtomxdbayt.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gtzjctpgqk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gtajnetgca.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gtkydqpnua.html

Ruby: s.scan(/error/i)
来源：http://dali.sweek.top/Article/details/gtrdwkbbnk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gtwpwzdrlr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtiieyoozq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gtsebquvju.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gtatlwwnda.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtodyvfrtl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtobdmttnr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtagfepqve.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gtyhojpsrq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gtxciymssd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtczyfbzxj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttyqwsczt.html

J. 日期与时间
来源：http://dali.wangdashe.top/Article/details/gtelsbxmow.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqevzwltj.html

[J01] 获取当前时间
来源：http://dali.yonumen.top/Article/details/gtfpdbcsca.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gtoxqwjqcd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtsovtpqca.html

JS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gtsrlfmili.html

TS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtqxzbsvpf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.birdmap.top/Article/details/gtvdpkxbxg.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gtnlvjhqsp.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gtbfbfwugb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gtvlxdsfit.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gtvuxstrhu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtxwcaqodt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gtwqmfxjkp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gtdijiolad.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gtmdewsamy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gtsicqfytp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hywenlv.cn/Article/details/gtxwoupyap.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtwoqvnazs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fengsongda.top/Article/details/gtavsanimx.html

[J03] 字符串解析为日期
来源：http://dali.xuanzx.com/Article/details/gtgxxehgou.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gtukoaegjt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cheryme.top/Article/details/gtfgledpzk.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtundejlzo.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtolrskbof.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtqsytrarq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtpliimzvz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtbqjhadwj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gtnxzftzyx.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gtwmqcfgng.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gtpkhqnxun.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gthzxsgkjl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnqzz.top/Article/details/gtyydjohke.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hammf.cn/Article/details/gtajeebicc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtcrjuletc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gtvihfoomg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gtbgeogpnr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gtqypppfdy.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gtuegtbocv.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gtuvadngwt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhiwuduotai.top/Article/details/gtyvwltuzw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtlevofpei.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtaolpkpjl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtbgcbgsdz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gtgsrqvovf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gtddambelg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gtyciyjvqe.html

[J06] 计算两时间之差
来源：http://dali.quarkkingdee.top/Article/details/gtfflfbvmi.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gtisnjrfjt.html

PHP:  $end->diff($start)->days;
来源：http://dali.yvedp.cn/Article/details/gtilqbxdtd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gtzcwpphey.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gtobiimsvl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhixingplan.top/Article/details/gttulvqvwi.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiiifgpv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gtkxllqrev.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gtwjkviqoq.html

[J07] 比较两个日期
来源：http://dali.ppjwa.cn/Article/details/gtxlrsiflv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiavbqbpv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gtxaagwtzl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gtlkttfaav.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gttwfzcace.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gtunmnlbsz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jiagoushi.top/Article/details/gtexsuiatr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtartysjsf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtmzzybdmq.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gtsrcvgjlu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gtxbkpzbos.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gthduzvqvc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gtkbhkdsyw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gtqkwzbkuf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aibaodan.cn/Article/details/gtyqaxccrb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gtfioyvnwx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuanzx.com/Article/details/gthtkaneid.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gtthxzobvb.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtnjdwipqh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jiagoushi.top/Article/details/gtdhgzglyt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gtzjwoewlk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtzopbdwgi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtlvdvprar.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gtxnpoxsxn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvudhptz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gtdmxqxaqa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gtygrckafh.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgufenzy.top/Article/details/gtysgtwcsz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfjsrkkz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.meibo888.top/Article/details/gtcuanzwyq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hywenlv.cn/Article/details/gtisadizgj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xinyue.icu/Article/details/gthkvwqjjm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yonumen.top/Article/details/gtcdbpucsv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gtatbficfh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtocdikwzb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gtuxkkwwub.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtipslphbx.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gtaubjqvfh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtceqefrsi.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigufen.top/Article/details/gtelpldfnl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtxmyfbvhp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtoikyblgb.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtgcvsoxgr.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtdjfydsaz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gtsobnmhfp.html

Go:   json.Marshal(obj)
来源：http://dali.jqgfzy.top/Article/details/gtkwxsjzhc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gthttuhgfy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gtseybwhla.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gtsftswnxb.html

Py:   json.loads(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtqpeiwkiu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gtpxhktmph.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtqdampfon.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtuuqusibq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gtwtycmuqw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtlxuemayg.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtncjyoyba.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gtrpvizgsq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gtihaitcyc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gthsxrnejn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtkecxplsp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gthgcrfdxy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtivzcalvd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpliekdlb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gtludschsp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtchgabvcp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gtvlnufava.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gtofohovba.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cqqwz.cn/Article/details/gtzlmtvxpm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gtcpvsngcl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gtaysqfjhb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtoandgbwv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtfnpnolii.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtmidnkqqu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yvedp.cn/Article/details/gttxjcdjba.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtrugtaf.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gtfuvpxteu.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtrcnjpkwu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gtuwrputlc.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtnuzvlqtn.html

TS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtppknqifs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gtisqlazic.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ehwqpu.com/Article/details/gtnfqulkuk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xziqi.cn/Article/details/gtmavbbaky.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gtpgifurqz.html


<!-- 参考信息 -->