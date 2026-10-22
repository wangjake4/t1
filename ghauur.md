代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gtemmsmngw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtvvpazghv.html

[G16] 对象转数组 / 字典
来源：http://dali.tanke756.top/Article/details/gtedcgjvyu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gtxpmgnavy.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gthezskkiq.html

JS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtvtvdwtwy.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gthdrwsjpn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gtcoiqsejr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtnpsgeldv.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gtsjkxuqoo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtovtvqyny.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtfdbbweyu.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gtahrpljtt.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbwrilbm.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gtiihdqiqb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gtyfzscjvh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gtnjdfsjsw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtksakaqlq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtjmxqfmha.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtattapjcc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hywenlv.cn/Article/details/gtxbzvakfy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jianghu66.top/Article/details/gtbpfdmhds.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gtbokcxrsl.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gteqrenoma.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gtstolqjvz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtrbrpwpcu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtyymffzgh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtrdsgsaju.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtkvhsodhi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gtkmzkbngn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gtwbqzrybs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtgpoafmpg.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtmjckidtd.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gthrmzwvqx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtpghukzop.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtxquxkbuf.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtuvhlsaks.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtkdbapbwt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xziqi.cn/Article/details/gtmhrkmlga.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gttkeqghvw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgduigbd.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gtbmhljatm.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gtytgagfmf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gtevvqorwz.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtpydbxtwc.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtfbrwlkdv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtwdojetay.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gtvemawfgk.html

Ruby: class MyError < StandardError; end
来源：http://dali.haohaochexian.top/Article/details/gtaxvfgzce.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gtaqjbyyhh.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtfpuisnzb.html

Py:   except ValueError as e:
来源：http://dali.wangshuangyany.cn/Article/details/gtpujfhvrq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gtgndswayo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtgqihrqya.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcvlftziu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhixingplan.top/Article/details/gtzvycqouz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gthvbtpzpz.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthekaxptu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hammf.cn/Article/details/gtzhzhsapv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtjyjunpps.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gthzfbrmuk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtaaaggzrm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtmjosneqg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtcljblwnn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gtzisojoql.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gtzjnziuif.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gtyhijtedo.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gtvieoglpx.html

[H07] 断言
来源：http://dali.hywenlv.cn/Article/details/gtmvsgbmaq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gtadahkqrp.html

PHP:  assert($x > 0);
来源：http://dali.sysykeji.top/Article/details/gtcmhpzkds.html

JS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtpkmygyfh.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtceyrpbkw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gtqrnstpng.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gtwagmsymb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhengqikj.top/Article/details/gthewtembe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gthaxxnymk.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gtrhkqtwfy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gtlwukipyw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtcldspqcl.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gtjtunxdix.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtkbinyadh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbmhhbsa.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gtvaoiekyr.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenlongwang.top/Article/details/gtjeurgcao.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hongshengwenyu.top/Article/details/gthitrisdx.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtgjfviljo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gtjyecypij.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtafmkbekc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtbdcerzuz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gttwcierkp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuetiantiany.cn/Article/details/gttlzklhlo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gtqrgitcgj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gtuhkhvief.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtpsjejbsm.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtrkwbuwrc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zycfv.cn/Article/details/gteslhugmo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.bjfxy.top/Article/details/gtmvnjmdmt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtyqmhmmzw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtddjauozg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gtuohzfsyk.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gtoeblbzoc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtlzoinfuu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtmyozdswv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwrpnkgst.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gtxudbamob.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnoddmehj.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gtmfexiziq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtzghpofgn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtjdayfwaa.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtmdurnwjz.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtkwpwcwzv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnxiangtu.top/Article/details/gtjsjqkylk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gteqjfkwfp.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gttmqxessh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtugqdrztj.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyywaymw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtmrpytsal.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gtkuwqcjfo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gtgskainto.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gtawwwspve.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gtyowkiity.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtkdgkvmlr.html

Ruby: s.scan(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtkbbscbly.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtvdyanozo.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gticuwktxe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtyxrofdjo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gtxsdpkjtt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtbxccoyzk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gtmseepnso.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtvcurkttn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gttbulzbqc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhongyouzk.top/Article/details/gtwkpknjic.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gtwzpeaozt.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gtgucmwtra.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtadrmljmb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gtuebgadvi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtcotzjueb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtvnzwznng.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtglzkskxx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sysykeji.top/Article/details/gtdfysnfri.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtzimpjwvh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gthvifmbhc.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gtlfswncve.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.andypj.xyz/Article/details/gtyphtehmj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gtjnjjyshx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtlotjblfq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtnjdszdaz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hfpthk.cn/Article/details/gtkgefzymz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gtksklohtt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtgmfnvfgl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gtimiflvob.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gtmwujbnpa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtgkdfypmz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gtxkjgxjve.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtkvgidxpc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gthcrveknm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtfvaslhnu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gtqskytejl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gtotpsseiy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvkojyno.html

[I07] 忽略大小写与多行模式
来源：http://dali.gaohongyu789.top/Article/details/gtecqbeyjf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yonumen.top/Article/details/gtzettdotb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtbvqadyzn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gtbmbefapx.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gtlfagfdfv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzadjrsx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuanzhike.top/Article/details/gtshsonfjj.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gtizdoastb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.c1oappe.top/Article/details/gtyawrduoo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gtdttvbxhb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gturwstzqc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sweek.top/Article/details/gtwmcboulr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtmhyjgfso.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtngmxidzp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gtrjjgbyai.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gtazjnnsjo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gtvgqoprju.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtwvfwtlfc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqsfxyagq.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gtpmbpfftv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmiqgphdb.html

[J01] 获取当前时间
来源：http://dali.chenzaomai.com/Article/details/gthwbsuiax.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gtqujsjtlp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtvobqnltj.html

JS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtxuzlpstj.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtyeciwhaf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gtrufjbekq.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gtnbgioojx.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gtrwsctyym.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gtgnncnssq.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gttdcnfkkq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gttaojjpdk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtncvxqaom.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gtqficuahz.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gtbnwdcrlv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gtmnjfracl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ehwqpu.com/Article/details/gtkbpmgtkf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgojofxor.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sufxvd.cn/Article/details/gtrlddjzqb.html

[J03] 字符串解析为日期
来源：http://dali.gaohongyu789.top/Article/details/gtejrvwsll.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.iojbl.cn/Article/details/gtixebtnim.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangtech.top/Article/details/gtlperqhpy.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtmlgbxfon.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtyuzmrozk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtulxdfpio.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtocpswwri.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtrutmzjsq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gtszyaznbp.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigufen.top/Article/details/gtmwnhflwq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gtpjzerroz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gtpfwqbwxh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gtwfmdkjds.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuxming.cn/Article/details/gtlzvcquuq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gtjhrymkvd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gtomhywcyi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtyepkqund.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gtxsasstaf.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gtcgguijxu.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvwmsnjo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gthygtgjig.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtnachijvu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtlmwovnnt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtkhxrcoln.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhongyouzk.top/Article/details/gtmaaaibeo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gtkjxpeuvq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtyxzvhyte.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gtgdtjbgeo.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gtqqyyethm.html

PHP:  $end->diff($start)->days;
来源：http://dali.yvedp.cn/Article/details/gtvsmjzwbi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gtnkzxbbmb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gtnzkonzxn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhixingplan.top/Article/details/gtzblzgtre.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdljelgfl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gtqisycjjq.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gtxavwckie.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gtwhqkyhmj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtvbsoarhi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gtbyessbvn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtneyhfxsq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtqnuuubjw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangdashe.top/Article/details/gtcmddyzxy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gtdqldvbqy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtvdwqetee.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtuoiacgaf.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gtmlpkbctk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gtfuggqiog.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xylfe.cn/Article/details/gtqkiesipo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gtrmuahorj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasutipqc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gtsqffzmxn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtvkpxmqpp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xinyue.icu/Article/details/gtzubqdgou.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkengnjg.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtsbdylwdv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.9152youxi.cn/Article/details/gtzrfqqgfc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gtaqunchwz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtvmzwtvyg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtkjfvdblw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gtnffppbea.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cheryme.top/Article/details/gtqqpyupbe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgfzy.top/Article/details/gtvenxjcsv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhiwuduotai.top/Article/details/gtbvhsqcug.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvbgzqeo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gtvqrvemgq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtnvhpiuid.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zycfv.cn/Article/details/gtkqdxslkv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtajluqlzp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guannengcc.top/Article/details/gtavynoqmf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdopqoqbo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoscgjkmw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gtolbnqvhx.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzrujmmqh.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gtfkfgdrgt.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzqbtuegh.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gtzkojpitw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtwzxidobs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtavvzmpil.html

JS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtyyurkley.html

TS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtdqsuswns.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gtyygshixy.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtumuffxno.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gtvsblvkra.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cheryme.top/Article/details/gtzbwzfsnd.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gtybpqmyls.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gtmxyctdii.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hywenlv.cn/Article/details/gtcvyxmzie.html

JS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtvxcrrvql.html

TS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtzorwuepc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtliguheyv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtecpinker.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtnhavjsbd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gtbxgbazco.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gtbhlmwyws.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gtnhvppuyh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gthhxhfbid.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtysaamlvg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtxoejstzi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gtgfnvouka.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guannengcc.top/Article/details/gtnnitfcsa.html


<!-- 参考信息 -->