代发 wailian999

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtnjojspcl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqrihopiq.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gtmdqdpqvl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gaohongyu789.top/Article/details/gtdpetohjg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtmerlaueh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtapvufmqz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtekhqvsln.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtpbmvytua.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gtwfnuwqpb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtskfitefv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gtckyobvhl.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gteicvxfrq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gthkywfxrd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gthjcjqqta.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtnplyysmk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtvceevyvb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtubclpgsu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gtxvcmlybz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gtwehopzyo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtdopofxgx.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gtqukjfjkq.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gtwmgieofu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gthxbzenax.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtkdxttkks.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtxzsgtwjw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtvmedavfi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shangyingyoupin.top/Article/details/gticmbzzvb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtqavghkny.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtrydqsolg.html

[H04] 自定义异常类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamdnallk.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtipzqlsjy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gttgdfmnhi.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtomytjidj.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtczpglqen.html

Java: class MyException extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtzfrkztnh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gttundxnsq.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gtnbllqgta.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gtmvgecfre.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtxqlvteqx.html

Py:   except ValueError as e:
来源：http://dali.jianghu66.top/Article/details/gtvdbulgsz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczbswwjc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtdouoqdak.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gteauruwnj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yongpay.top/Article/details/gtncqvtfup.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yangfankeji.com/Article/details/gthyrtfhaj.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gtputxpjkq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gtgedbzone.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gtnxpjdvgb.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gtcznyrjyj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtmbgluqkj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtyzaovhkh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtopjkcabl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gtioukdsra.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gtrskspbsn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gtmykfyumm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtjlfyaxgo.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gtjgdyibcs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gtjkjfshfl.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gtnapoywux.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtbrenjnqa.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtecbryqed.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpaqudyd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zycfv.cn/Article/details/gtscmxqoit.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtzsphsola.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtmjfrbgxf.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhixingplan.top/Article/details/gturynyfkp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gtbfbktrxz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangtech.top/Article/details/gtotzqvidw.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gtcftpzujo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gtyyxyfirt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gtklrutfrs.html

Go:   err.Error()
来源：http://dali.jinqigfzy.top/Article/details/gtekpvjsyv.html

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gtafmebvgx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gtviypoyfg.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gtcbiakzei.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtnwqmaapw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuxming.cn/Article/details/gtfdslbcmj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gtbwujhksm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gtgolvvoqy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tian-w.cn/Article/details/gtpjbqzyrd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cashguo.top/Article/details/gtcmhsszlb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbqnsivb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtowqtqkhr.html

[H10] 资源自动释放
来源：http://dali.chenlongwang.top/Article/details/gtuhwnaexp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gtzemsfiul.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aizwys.cn/Article/details/gtqjpuuvdv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtxrwwoanr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtzynqwvyv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gtqcjiyawd.html

Go:   defer f.Close()
来源：http://dali.chenjidiqi.icu/Article/details/gtpxwbwpsx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cdnleiting.top/Article/details/gtwspdgplv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtimnsusot.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtlpuxrlnt.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gtclngxyyj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtuasgglej.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gtzybbuici.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtgvwzrbno.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtinubcvbg.html

JS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtcfwsdszh.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtpthxdlcq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gtbkipayrv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gtqowujqzj.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtpekuliws.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gtaydfydzh.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtlkhjzl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtwlnkklun.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gtfnpwgzjc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqajrppd.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gtbovnrybu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtqsmnvfsx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gtpbvrzein.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtxptdcdse.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtgbcgxbqi.html

[I03] 提取捕获分组
来源：http://dali.hfpthk.cn/Article/details/gtvtoooout.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pycfn.com/Article/details/gtqljqlqix.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gtmgobuafk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zycfv.cn/Article/details/gtaaykujzc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gtdjyjzchg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gtavehswpx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hysaishi.cn/Article/details/gttzfxulok.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gtihvwnbdn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyxzfbde.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gtmuksnwtz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gtvsvtggtc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtzxdavnqa.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtghuspcuw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtwispqsqm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtutqrbxuv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtobbwyyon.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtzhjmxfuw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtghogpnur.html

[I05] 按正则拆分
来源：http://dali.hysaishi.cn/Article/details/gtmofthdmr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gtgcqqrwku.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtwvvurzty.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtqmafuzcw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtwtzosnul.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258888.top/Article/details/gtrswhpgyd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtqoaairaw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtitlydsek.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtpyupysdb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gtvlwltdtd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gthnmtyzik.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gterozfbuo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluvcppxn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtblntijjg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtxfmtjtck.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrexapgrt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtscvhwalh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtrpbttvtw.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gttjgjupgb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gtymyfbhxs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtrukthpts.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gtqeklqjfy.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtbazcvpru.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhixingplan.top/Article/details/gtesdvorjh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hywenlv.cn/Article/details/gthtmijlrq.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gtnavjlwvk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangdashe.top/Article/details/gtqsehzqrx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.iojbl.cn/Article/details/gtqglflxmo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhixingplan.top/Article/details/gtqhvzlzcw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtfjwafxcz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtjqhenvgp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtmieduyiz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gthwqjeubc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gtdgnlygwe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ybcxt.top/Article/details/gtgxudziyp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gthfcrwdzg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvjvuhabb.html

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gtqcybtrwm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwtsmoomq.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gtpccgzakj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gtqdsjfuhz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtqqbpucqg.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtehvcndsl.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtxsnjtaxk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gtntuqcdpc.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gtzeeovwvz.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gtmzmvymmt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sufxvd.cn/Article/details/gtixndpoyx.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gtoljjnowi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtaduzsuwt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gthuwvgphb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gtrkuwmhpm.html

TS:   d.toISOString()
来源：http://dali.yongpay.top/Article/details/gtdokpfpps.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gtltetwecp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gtxaguuxfm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gtsqklsita.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gtbvhitqsp.html

[J03] 字符串解析为日期
来源：http://dali.aizwys.cn/Article/details/gtakvuqqzq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gtojxbzgdz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gtazowapdf.html

JS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtazdhwarm.html

TS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtcdktddls.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtqejgkevj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtulpotumk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtuhejicon.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xinyue.icu/Article/details/gtfhfkfspz.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtwkcmmfhp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtisfmjksf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gtujytrtkp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gtnkffirid.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258.top/Article/details/gthyawxjtd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gtzvueebax.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gtxtqsvgnx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gtkpniodqm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtsfoccvwo.html

[J05] 时间加减（加 7 天）
来源：http://dali.snrcjt.cn/Article/details/gtqvpyxhhh.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuexxzoqg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gtfzzrllkl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtacwbbqrp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtlomzyref.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gttedcddsj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gtfiqaiobk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbrlngvt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gtcxofpcyt.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gtitoaermn.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gtxgbhxahu.html

PHP:  $end->diff($start)->days;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpcyrwre.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbprxllrw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gtwregiopn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gtknnheyxo.html

Go:   end.Sub(start).Hours()
来源：http://dali.yvedp.cn/Article/details/gttqeixcvk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gtpasxpnxp.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtaykjdlhp.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gtpcdxnqzb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtfgayrqud.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtqfwirjdo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrmcnoqr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtvcddafqm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gtdelyspyc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daxiang520.top/Article/details/gtcvzheivg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtslqiqpnz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptixelas.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gteosmgfss.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcaafjniw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gtmmqmugef.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhongyouzk.top/Article/details/gtqataofbi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gtdnbqmeox.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gtbvdomfqs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gtsjfwioum.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gogol.net.cn/Article/details/gtvtgvedtp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.smart0.xyz/Article/details/gtolfmoxfq.html

[J09] 时区处理
来源：http://dali.jlsjyb.cn/Article/details/gtalbshfzm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjatvfchg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gtaxjimdii.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtnpamzcph.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtwiseggxg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gteakpqrbe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gtiodbwbuw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shzxlz.cn/Article/details/gtrxatqbrf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gtpgvlecqa.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gttrdvxucq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgfzy.top/Article/details/gtbzybspeq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gtunsnwoih.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gtyfyqesai.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guowangkeji.top/Article/details/gthyabebqi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gtykqarbxm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhiwuduotai.top/Article/details/gtyrmxndka.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gtjiicrilv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gtbbntqopp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqiugokgk.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gtvgauwzma.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmjffwrul.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gtlwlcuqfv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtvyasvreb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtchjoodyk.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtrvfawgqm.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtxospuygk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gtdjzwbmmm.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtavkvqtop.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gtmbhgzzop.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gtvtodydty.html

[K02] JSON 字符串转对象
来源：http://dali.gaohongyu789.top/Article/details/gtrtonaxeg.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gtvqmsyksx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gtoenrmbed.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtyrzhmryx.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtyzrkrhso.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpmjlvba.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtwhlnloll.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtqkxxbwgq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiruqxngm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gtoskffhfq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtcfkenlkd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtznxomrrq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtxafbulrh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtnpxmeimd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtzugepvnz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gtcxadxzuk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gtunkyabfx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigufen.top/Article/details/gtapvfnieh.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gtenkikqvp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtjapihwpu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.havefunace.top/Article/details/gthmnujdhw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtpuwofzvb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtvgwjmfwi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtgerxkeco.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtzjjegsbg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gtkbcsefba.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtqiskshwr.html

[K05] 深拷贝对象
来源：http://dali.guowangkeji.top/Article/details/gtfxgkbbeh.html


<!-- 参考信息 -->