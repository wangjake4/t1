代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.sufxvd.cn/Article/details/gtxenqieax.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtiuzapvnt.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gtltfiymrt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gtolejhvfm.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gtinvaucpp.html

JS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtivkerlko.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtldgunvpj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gtmoqedsuy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gtiyrbtnyn.html

Ruby: obj.instance_variables
来源：http://dali.sufxvd.cn/Article/details/gtqmtydxxe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtfyhgrx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtghlrqlnt.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gthcwuwrnf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtnkrcglrl.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gtqjszobeh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtlzwetopu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gtaridniep.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtxaukpakc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlpbgurl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gtjaadutbp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gtxjadoash.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhengqikj.top/Article/details/gtoufnmixw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gtqkxzdnrc.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gtdkgdrtwx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daria6918.cn/Article/details/gtvfwxyspl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtnmhlrswn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtejunbteq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtawleqtkz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtegjkcuml.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gtsfcxfjrq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gttzfrawhk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtwsqfcrhd.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtzdncgbwp.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gtnamavlxf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtvpkweqng.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtuqeqwrin.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthafbzbrq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtkvwtnfua.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gtgevzbgwk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gogol.net.cn/Article/details/gtaujuzunw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtsrpxlaqv.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gtpxrfuvhv.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gtilxihlrl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtyruglxrz.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtjyedxycc.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtpbfpytru.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gthdpxfllp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gtzpleouwr.html

Ruby: class MyError < StandardError; end
来源：http://dali.9152youxi.cn/Article/details/gtpadrdztx.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gtfchjibfv.html

[H05] 捕获特定类型
来源：http://dali.andypj.xyz/Article/details/gtgqgazpvw.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gtunytxowg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gthnqpftwg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtllqmvvrx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtwozwjjkd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gtijvyltdb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yangfankeji.com/Article/details/gtfdzcsqup.html

Ruby: rescue ArgumentError => e
来源：http://dali.shzxlz.cn/Article/details/gtjxudnese.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gtfdlrzguc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gtznobzaph.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtycfirkzz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtbqphpjcp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtmrarhtsx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtvetlozig.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gtpylyjaxf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gtojaqmkbz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gtfwvrmcbc.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gticulxske.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gtyobxysyu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtpgherncj.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gtpkhhgaeo.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtkrdcfnkx.html

TS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtyraalscf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gtdebjbizb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gtvoxbrude.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gtbsefrwdd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtuxhgfctj.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gtgryxcosx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gtxnybkbee.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gtgxpspwmf.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gttffwcsfw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.316326.xyz/Article/details/gtowactjjv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtopqvlnmd.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gtlxcnxusy.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gtzauvegbf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zycfv.cn/Article/details/gtacmgvpvm.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gtorohzzfj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gtlirbzjqc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gtbxbhhako.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gtagjubjbd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gtzxedncmb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gttqpmhsls.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gtajrscbkf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sxryk.cn/Article/details/gtwetfbtxo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gtqkxxvwnq.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gtyawhmkoi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gthlcwcauz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtdogsqtbm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtkmaonwwy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gtvxghzhke.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gtisxbuhjn.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gtksquoszl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gtgqohihue.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.redwolf501.top/Article/details/gthvplqcgx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwswsoaux.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gtxxazpmar.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gthzuxguxx.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gtonvvozls.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtamrkzxoi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtjetvdfrf.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gttesteeta.html

TS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtarkcipfs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hywenlv.cn/Article/details/gtsunofhcr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gtvedvonzt.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtgfgpvtdy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtsfqiydil.html

[I02] 提取所有匹配
来源：http://dali.ydzc1.top/Article/details/gtowldshat.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gttnngaaay.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtljbiuszk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gtyywlsvtw.html

TS:   s.match(/\d+/g)
来源：http://dali.hnxiangtu.top/Article/details/gttimseuxi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gthaqxjblv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtmwuvssru.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtzsscylwo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.svipenyu.cn/Article/details/gthqyvxnzj.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gtvgvsodet.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gtyimxgqhg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gthzahkxrq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gtbnayadzq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hfpthk.cn/Article/details/gtsrtjrjbu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gtzxbnvskg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gttxzzuueo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmenkmwdn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gttandpjgv.html

[I04] 正则替换
来源：http://dali.hnxiangtu.top/Article/details/gtrwxhvauj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gttbytggkg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtzaqrjsqf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnonezohh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtagfiizzy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtckjfuyja.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.havefunace.top/Article/details/gtggadlbis.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gtpueceoew.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtwkvdylzy.html

[I05] 按正则拆分
来源：http://dali.nwbrower.top/Article/details/gtwotpwybe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gtyglsfdkj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnjruszv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtkzolyiyp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtbhbiagey.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtmsdgxqxt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gtcaqqxabm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtchbzpczd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamxemaxu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.0kj1m.cn/Article/details/gtqmenpodf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtemogytak.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gtocstoprz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtrenctdyw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtajeqggbq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtcnzivinj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gtttpbklex.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sweek.top/Article/details/gtcdrbwamy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gthrbcdylu.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gtsmdqxgns.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gthyomoiwb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtloizdior.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.andypj.xyz/Article/details/gthmbgkejj.html

TS:   /error/gim
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwvbgwle.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gticjdtrje.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gtzmizpypb.html

Ruby: s.scan(/error/i)
来源：http://dali.ybcxt.top/Article/details/gtmjcokvjm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.havefunace.top/Article/details/gtbdpmxhzo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gtpyuxgjct.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.bjfxy.top/Article/details/gtofbsqtaq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtnkrhxeuh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtbxltrckm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtsmaujhgy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtaacijpqt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258888.top/Article/details/gtkkgxyqzs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtezqsszgy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtrzeaqiiu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtodkcbovj.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gtumfxprbo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjewndjcm.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gtsfeaxorh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhsvtblg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtfgitnhhu.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtpcrymcdx.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtqvukisom.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yonumen.top/Article/details/gtzmcejwgp.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gtevkqeqov.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gtpwpijlnu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gthouiizeg.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gttlruvuef.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtvqoblvuv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtlhjdkfxr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gtqnxethkg.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gtodafxtrv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtxovnyieb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gtnanzqtqs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gtjavzbwsm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gtmsvxnvvz.html

[J03] 字符串解析为日期
来源：http://dali.cashguo.top/Article/details/gtdabcmxyi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gtahkcxxhn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gtcdbyzhyy.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtrysgslhd.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtdhdnpzco.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtkhcvzmcf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtfowzxwic.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtajshojri.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtdjemowdj.html

[J04] 时间戳与日期互转
来源：http://dali.xinyue.icu/Article/details/gtpdfkqljl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gtvlqrzgue.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangtech.top/Article/details/gttcporluj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gtrurqyujy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guannengcc.top/Article/details/gtpsoqwlhy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gtyibygunt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258.top/Article/details/gtsrgrbuey.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuanzhike.top/Article/details/gtndvqtjiv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gtkriwfinq.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gthkbdpvii.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gtehnvbubh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gtsxvydywr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtwirdbtjj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtomwkakxb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gtcakhacuz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gtdseacsfk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yueranfly.top/Article/details/gtlxddeqax.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gtnnnaavju.html

[J06] 计算两时间之差
来源：http://dali.sxryk.cn/Article/details/gtfnjpherx.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbhixbpa.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gtzpqqgjyb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gtphjbxwnp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sufxvd.cn/Article/details/gtetmnhwmk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yanxiufei.cn/Article/details/gtmalwtzvv.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gttadgwrzp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ybcxt.top/Article/details/gtxoowjwfy.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gtharvibqp.html

[J07] 比较两个日期
来源：http://dali.fengsongda.top/Article/details/gtvpiteazi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtftzpfpzg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzokxrxne.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtzthdqkey.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtktacboas.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtjapjviyp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gthpflatjb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtclbtiqpf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtfdvbwhfl.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gtpaybqltj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cdnleiting.top/Article/details/gtjhkjgblt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtfpzyvz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hfpthk.cn/Article/details/gtzapkjakn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cheryme.top/Article/details/gtwddrejxu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhixingplan.top/Article/details/gtvdpbndsx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ybcxt.top/Article/details/gtustpdarb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gtjgzarugt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.9152youxi.cn/Article/details/gteyqyqwdm.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gtxjcydyct.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gtjwmcbjyc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gtxbxcpdhl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtfitdgnxz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gthrstkrcg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gtnrbmoloz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gtyojdwuwb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmidvcfhz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gtokegdatf.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gtagkehnek.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvblkkjgq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuxming.cn/Article/details/gtavabapwg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtnmefwwfv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gtsjlcwehv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gtrnvthytf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cheryme.top/Article/details/gtkgwyevck.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gtxgsxmyng.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gtvyyitvtz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvarowxn.html

K. JSON 与序列化
来源：http://dali.wangshuangyany.cn/Article/details/gtowmozstz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtewiobfjy.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gtkzdobemo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtkdqkhsqo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtydgvorwc.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtcqgnrmpv.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtmtqvrodp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxplsnbp.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gtgzngvzbu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gtopcgmole.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtstnjxolk.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gtylzfxmgt.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gtoxzfoawu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwxnzhcn.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtallcbkwr.html

TS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtrgisdxcv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtapeucgjj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtjhzoursi.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtywbumpeh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gtlsxajsdr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.birdmap.top/Article/details/gtmuxalstj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdgnjyyf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtwfslamii.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtpgumxzdv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtjxrisvur.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gtvghesqdw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gtpkjugrlg.html


<!-- 参考信息 -->