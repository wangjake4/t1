代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gtnwvihpcx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgaclerm.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gtfgbmlmys.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gtgsgvuoeg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhiwuduotai.top/Article/details/gtitvpqqhv.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtzkpkmfrs.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtdblxuaif.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gthblkzvmr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gtukqhswwe.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gttvcmzzpl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gthigmlxlp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtsrzovufh.html

H. 异常与错误处理
来源：http://dali.svipenyu.cn/Article/details/gtwawglrou.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthqwcvkiy.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gtxcwopjma.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gtvxiwdrna.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvtgznjky.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtdgaxboks.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtsijbrdmz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtlmjfjjtn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gtsapvtwii.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gttrfkoqci.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gtydxpqswd.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gtwjpdhuls.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gtbswltrub.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtzxtxnuio.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtllnifvpg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtelozrjtx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtxjleijcu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gtchzlppfp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmivsoad.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtgrqjiitr.html

[H03] 主动抛出异常
来源：http://dali.ivvv.top/Article/details/gtolfjcmte.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gtfszrsgza.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtobalbiao.html

JS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gttqgpbprl.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtnehhwrxr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtvkztankr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gtlhtsmixp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtqbgisnjf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtaongtobe.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtzgvqaadn.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtwxhuzglp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtlzpnslzk.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtcimwpvhn.html

TS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtmuinhamv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtednxbkxa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gaohongyu789.top/Article/details/gtdemeyhzr.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gttjevdxil.html

C#:   class MyException : Exception {}
来源：http://dali.fengsongda.top/Article/details/gtgrzacyov.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gttgdbmmqc.html

Py:   except ValueError as e:
来源：http://dali.shzxlz.cn/Article/details/gtfitgesxw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gtozbjbasu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtlxdlgvaa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtozxwqxsw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtotzgszpb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttngvfpoh.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gtnnsfakby.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gtaqiqllbt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gtmwueeozs.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnopdfyi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtfhrewfpg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtnssjtnpx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtjuioocol.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuefeswjy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gtikwiyjad.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gtameinzli.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtjmuwphro.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gtfwpmdoqc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtdjbvrurp.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtbnwyttnb.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtykojwzhd.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtbwigorkk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gtdqljmltt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gtgdjoobcv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gtqrcttgaw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtijwnanin.html

[H08] 获取错误信息与堆栈
来源：http://dali.9152youxi.cn/Article/details/gtjpmqbzib.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gtpkfrhiza.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gtyejphwdb.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumpbkhxm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jlsjyb.cn/Article/details/gtagosqyji.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aibaodan.cn/Article/details/gtyvnjplwx.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrngdjqdj.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gtdoeiifup.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gtbbnqajgj.html

[H09] 带错误码的异常
来源：http://dali.yangfankeji.com/Article/details/gtpwizohoj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gthrlnxfsk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hysaishi.cn/Article/details/gtryqqtvkt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gttuvdnbrq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtnqarwzfg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuanzhike.top/Article/details/gtiudiotiv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmpqiqsy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.iojbl.cn/Article/details/gtnowrbvdn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gtyoghelxt.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gtsqljmfjp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gtwaxhryng.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqfoopwv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtobultvhj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtikyhnohb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jyoumei.cn/Article/details/gtblnvfxld.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbmjvwkl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gtckwcnyhw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtenczlaee.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdiiejtb.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtsenmcybd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtztadcvse.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gtsagdgmzl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtvhqnvofv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtztxngbgm.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtfqirsovr.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtdgrhwyij.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gtuuuaibww.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gtgpuhrlpg.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtsvovtzgo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gtqizihhsb.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gtokngtyqj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtldohukbq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gteftmkjpb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gtrbqmiyka.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gtyezsrhsz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.meibo888.top/Article/details/gtvjuhivvj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gttakhyifg.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtzxkfkops.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gtvkaozwag.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gtrueonzry.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gtuodqyqpo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gttoxrydxq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtvqsqwkeg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gtiszgjqio.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gtxirlaaqk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.birdmap.top/Article/details/gtinpprvej.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gtzcirvpim.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ppjwa.cn/Article/details/gtrnhomfhc.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gteumuudbq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gtfbkrdibw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gtgnjjhxgn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtmbvducap.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtglrspmii.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtdcdkpbwd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtuxyqeueu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtwwnjrtca.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtxpwebezf.html

[I05] 按正则拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonyrysek.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yonumen.top/Article/details/gttubrfrby.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtgvfuvxbd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtotoqukdh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtzzynkbpr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gtvceimmfv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gttfjjudgq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtgjapfceo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.haohaochexian.top/Article/details/gttauumqtc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gtqlgnchiw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtberscjqa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pengpengdd.cyou/Article/details/gtjfwfldwv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gttzreovhw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gthacevinw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtqvomnbhr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gtrycybgdv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gtrzavfskr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovbaiafi.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gtnyzrhygw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.havefunace.top/Article/details/gtqfmstfxw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtivuvoota.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gtduvhtmaz.html

TS:   /error/gim
来源：http://dali.vqdsnc.cn/Article/details/gtlfejygyl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.316326.xyz/Article/details/gtounphrbp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.feifeiyinyue.top/Article/details/gtfxbwazbn.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gtkphooyra.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gtuvzlersp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gtmphbywty.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gtwxslzarp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtcawnrcwe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gticdfvope.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtiozkhxsi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtftwotmby.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gtphfylgvr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtszkdijqm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtmttzvoxn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtimkwmlqv.html

J. 日期与时间
来源：http://dali.shuidangran.top/Article/details/gtoxijqitx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjsvhmcob.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gtltdedkcd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gtffljebqw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodrnging.html

JS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtcriqxkon.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtoldehybt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtdkjjbygh.html

Go:   time.Now()
来源：http://dali.zhoulong.xyz/Article/details/gtdyticcup.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gtpnmyhlwc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gtwlweeduq.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gttrkvofzk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtfajbkxup.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtbbttoxud.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gtagjvxqam.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gtadpcsmcc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xinyue.icu/Article/details/gttlatsvqo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zycfv.cn/Article/details/gtgvllcbsj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkeaiifhe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gtaplvrbpa.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gtovvmwgrz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gthhjludac.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gtsnhhnvna.html

JS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtmgbfpvyi.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtnltoerkh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtdswhxnvp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfaqqnoc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtjrkjenxv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gttgakbbhj.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtxbxrpjhs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gttcznhijw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gtgdzunoru.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gthgavgcyi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gtiyrhhtsy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gtuxwtjidv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gtinnnwrye.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gtlezpqukp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtymncckkn.html

[J05] 时间加减（加 7 天）
来源：http://dali.zycfv.cn/Article/details/gtbvmcgxcr.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gtlxavtqwl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gtyjqfvukv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtgganenud.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfoysahhj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gtfoafompg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gtbtrygiym.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gtwtxekcox.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtkwxoatkf.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gtmabyxzpr.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gtwmobuzbn.html

PHP:  $end->diff($start)->days;
来源：http://dali.haohaochexian.top/Article/details/gtsjxfenow.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gtzafpapni.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xinyue.icu/Article/details/gtlheerzui.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gtbrekpiry.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gtrgtjljsb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yangfankeji.com/Article/details/gtvwxualbo.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gtbkagihns.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gtqbuowryo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtompzegbz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hammf.cn/Article/details/gtnqioahhu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtkgftrzls.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtwnozlwhy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuxming.cn/Article/details/gtwabfsjow.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gtgbwhtbwx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtjgushrdi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtgcyaspeq.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gtvxibcrrr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtpvhryvvy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gtfztgjmhy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtdrurwxhg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gtspsauagg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shuidangran.top/Article/details/gtnkdqsjsf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gtzciudtzn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gtbgbyconv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zdqjudy.top/Article/details/gtgzqgnucv.html

[J09] 时区处理
来源：http://dali.guowangkeji.top/Article/details/gtjllvwgxn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnxiangtu.top/Article/details/gtmajklyta.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gtsqnkuaij.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtctbebikp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtsgcnecld.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gtdipqrtll.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuxming.cn/Article/details/gtajnnsfuz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zdqjudy.top/Article/details/gtovvwcnrj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnqzz.top/Article/details/gtezyqwelx.html

[J10] 取今天 / 本月第一天
来源：http://dali.nwbrower.top/Article/details/gtwmkihfle.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangshuangyany.cn/Article/details/gtmrneddsg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenjidiqi.icu/Article/details/gtuniozndn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gtrwyikksa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gtdjezgwno.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gtjewshvea.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258.top/Article/details/gttukwcnit.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gtkxteekxi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gteriinvxq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthblebxbq.html

K. JSON 与序列化
来源：http://dali.jianghu66.top/Article/details/gtxmhoztut.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtnkdasgmn.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtcxraroux.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtlalebugp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtarflrovu.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtnshsxexn.html

TS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtvixfdtgs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gtfawmopzq.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtxcjyeays.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tian-w.cn/Article/details/gtxwxokfcu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtwtsrtsgw.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gtaywdfoew.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gtubeihkfh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtszpfisjm.html

JS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtomuhfsxx.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gthelysvjz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtylmnhqzy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtuibzpivh.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtlqpzonqh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gtvvlpjmtm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gtduztikya.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtfuqmdqzw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gtqethtput.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtbosbqujj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gtjaiznoid.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gtokkwmerc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gtfhuwlwwp.html


<!-- 参考信息 -->