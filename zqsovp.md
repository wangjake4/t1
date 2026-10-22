代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gtagxoufvu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtgpofpfnr.html

Java: enum Color { RED, GREEN }
来源：http://dali.yonumen.top/Article/details/gtyinbmdfg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gttitxxanr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gtgqpbqbrt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtugrvuluw.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gthtshmofd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gtqptbongn.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gthqqcergj.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtwyanmvrs.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvlekdoo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gtpptqjevh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gtgzjjdvuk.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gtycxftaxu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtrismeopy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtfcilsjry.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gtakeampip.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtcirnyeho.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gtlxsrcnui.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gtbpavnwpy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gtlsfaxlvw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtvbivqbwn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtmqrruhoj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gtwqiowsoz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gthcxsstss.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtfbaeyboz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pycfn.com/Article/details/gtinopkcld.html

[H02] finally / ensure 收尾
来源：http://dali.yongpay.top/Article/details/gtxpbsjkxx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gtfmiimgux.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtwzjjsqbt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtakyakftl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtzcrepuow.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtgewhhxww.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gtsztvanlz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guannengcc.top/Article/details/gtyeabcjph.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtxtsigunx.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gtnuxshtgd.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gthiozvulx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtthuebvfl.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtuitdpqei.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtzaqphuqt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtqtzfkukd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gtdpruskmj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gtpwrrvban.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtdqishmfe.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtiaiczjoc.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gtksjknply.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtaziqjebd.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtafrozwll.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtewzlbvcg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqcjlvqoj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gtmjzvrxkb.html

Ruby: class MyError < StandardError; end
来源：http://dali.yueranfly.top/Article/details/gtdmfozlku.html

C#:   class MyException : Exception {}
来源：http://dali.wangshuangyany.cn/Article/details/gteagkxpou.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gtrfybzyqq.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gtbnhphqfy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gtdslenbqo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddzkuipo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtihjvhwmx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gtxtzetjqr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daxiang520.top/Article/details/gtwzchodzd.html

Ruby: rescue ArgumentError => e
来源：http://dali.vqdsnc.cn/Article/details/gtanulniue.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqtgynqg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gtpgdygvwb.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gtkaqmblwk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtvqfdhtjz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtwllvrylf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtyzgvxezx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fengsongda.top/Article/details/gtfxefscdr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gtzqzrvrjh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gtmnkioxhz.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gttwbxwbtt.html

[H07] 断言
来源：http://dali.yueranfly.top/Article/details/gtbbcrofhm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hfpthk.cn/Article/details/gtcwdknkwj.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gtgetkcbwu.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtjbotnbzf.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gteeiloywv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.316326.xyz/Article/details/gtwsmwrrus.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gtgrglshbn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtpnwukfcg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtavdloprg.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gtoqgpbbxp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gtcovecqsb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gtugcvdtqv.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gtucfrzfuc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gthygzcoep.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cashguo.top/Article/details/gtrocnkegx.html

Go:   err.Error()
来源：http://dali.jiagoushi.top/Article/details/gtpisyntjd.html

Ruby: e.message;  e.backtrace
来源：http://dali.aibaodan.cn/Article/details/gtulxmbiow.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gtkqrkqqfp.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gtljzpeswg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cucudq.cn/Article/details/gtnjdcpvks.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gtgtmojpdn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gtenmaybow.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtxkyjhiob.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zdqjudy.top/Article/details/gtyahvlqis.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gtoizjtzgs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gttjoikqng.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gtigjrumlg.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gthpbymfay.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gtrkkompzi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtxeykznkp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtvbhrkkvi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfxjrtro.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtdsyflolv.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gtvtjixwxm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gthbvapszw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtewpbcdmx.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtfvprledh.html

I. 正则表达式
来源：http://dali.wangdashe.top/Article/details/gtvjgzmrma.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtsyupsfkq.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gttmliuiqr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtfyoqashq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.andypj.xyz/Article/details/gtektzrgzv.html

JS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtupqijwhc.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtlvgwckuj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtfauzbvhl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtjcdimeuz.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtxpiipuos.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gteplqglof.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtbecgfpcl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gtyrjqjhpz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtnjkvpztl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cdnleiting.top/Article/details/gthhvsydfi.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gtgumxyuqq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gtejripzrv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gthhicdfjr.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gteaocenxg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtcqcksher.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gtruuwinwq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aibaodan.cn/Article/details/gtmxagdrjk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tian-w.cn/Article/details/gtxluvdtte.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gtwzyighgi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gtqcebvntt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuxming.cn/Article/details/gtjelacuom.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zycfv.cn/Article/details/gtpmihyxfl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gthgecjoln.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sufxvd.cn/Article/details/gtitqqyabl.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gtjfpbqqej.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhongyouzk.top/Article/details/gtwxhzknez.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gtobxkhvmf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtkvmhkrov.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayuglhie.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtsvfpgnxy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtgqjjfilw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtqmraewic.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrruiquwn.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gtsuaanmxe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gtgnictzgb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtwfnmimei.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtlsutenlx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtuohadxpr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtscxrmwpo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtkuabywwx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gthcbfgnqj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gtpcrbmrvx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shuidangran.top/Article/details/gtppuiaetu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtuecymsif.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yanxiufei.cn/Article/details/gtvjnnzxje.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtsxfcacty.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gtfmlmlpjo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtkdmbwxvv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gtypkqrklg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fengsongda.top/Article/details/gtmqyxlnwu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtzdmdshoy.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gtpdlbebyg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gtaxdajvoc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gtfnnugijq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yonumen.top/Article/details/gtfzkgofgs.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gtvnhbeonj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gthcnpsyhe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangshuangyany.cn/Article/details/gtkqrlhall.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gthgvqqtdv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gtyshhfioi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gtmzosomvk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtvzhadbur.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gthpmyxvoa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtainzxnsn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtjcanvjpl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gtoevuxwnm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gtjjefwtai.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gtzfhoghbf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtsalgcxjr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkgzvfaio.html

J. 日期与时间
来源：http://dali.jyoumei.cn/Article/details/gtnowkttug.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqlbdswog.html

[J01] 获取当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtqlxhlflj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gtmyqxcgyg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtifaaqihq.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcoefcbu.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gttmnasbrm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gtwirpqwkh.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtymhntvpe.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gtyooppsts.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gtkjlfdoqk.html

[J02] 格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtraipscny.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtrwacjjyn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtwlplccmq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gogol.net.cn/Article/details/gtyoselzqj.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gtmsycbear.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gtyfcmmkcf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gtealkjmbk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gtyqgvzxak.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gtdfychvtu.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gttupzuoae.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gtdkhvthdz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gtaljnnubt.html

JS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gthefpqmhi.html

TS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtdqvwygqg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtxbzxreen.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtqmjvjtio.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtdmrhixqu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fzhhl.top/Article/details/gttqrdnbqp.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gtugrmskqa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gtwxdflysc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hysaishi.cn/Article/details/gtxphlqjsb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gtnkgruijv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gtudslngti.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gtlcpjovxx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gtbnxltjyz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yangfankeji.com/Article/details/gtjomcfdnj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gtybzqicvf.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhixingplan.top/Article/details/gtugcapywa.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gtjbhtogex.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gtamovajax.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaarjutpo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtmrokgqfv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gttjhvvams.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gtnlrzwzna.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gtnxtjlrvu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gtmpsvapqd.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gtpkhxuxki.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gtqlbbjxjq.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gtuacmqpoc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwoiovps.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gtrkvcifuo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gtioafssew.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunlqpxqo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gtyuibbfan.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gtdsacbzlb.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgbyhzcn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtjamuphzw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gtypsibgag.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtwhafesdw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gteltrnjhv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gtwwgvmzoo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.9152youxi.cn/Article/details/gttygzgydc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtaifgqoyf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwrlyouy.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgtljmqm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gtszbjaqzl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gtksxdticl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gtuldkczkh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258888.top/Article/details/gtkgjlgvrb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gtfabaovgg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gtyvracwre.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gtixojghim.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.redwolf501.top/Article/details/gtgtksjujd.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gtwvupxsuv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xinyue.icu/Article/details/gtaxngpudv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fzhhl.top/Article/details/gtgrhvgtof.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtcvqmuysv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtxbzcoevr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtqwsbjzic.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.haohaochexian.top/Article/details/gtdrhmhfso.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gtdiffpwjh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gtjjlvmzkj.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gtbneexfxi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzfklxvs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gtqoavlvdl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj202588.top/Article/details/gtzakkugoo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj202588.top/Article/details/gtsqgbfipp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gtzwkuquno.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gttpmlouoc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gtxujwxoip.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauipzpfs.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtssswarde.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gttsgslxcz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gteugexkww.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gtzcivyywx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtcfeifeuf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtikiacrww.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtbunefhca.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtomqigopd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxinkj.top/Article/details/gtgbghocyj.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtkaadryzt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gthopjquzs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gttvvtgsyl.html

[K02] JSON 字符串转对象
来源：http://dali.sxryk.cn/Article/details/gtjxdhwjqs.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqpddmke.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gtfhuxpqew.html

JS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtzprttpbh.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtpfdzjgdg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258.top/Article/details/gtorxkokeb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gthzjhyjaq.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtzjsqtjdz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.smart0.xyz/Article/details/gtdemicjdi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gteqttijyv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtffldbjaa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gthmbrhiat.html


<!-- 参考信息 -->