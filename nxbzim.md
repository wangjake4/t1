代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gtsuuapeyr.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gtbhgpuuvl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.andypj.xyz/Article/details/gtpiejeimb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sufxvd.cn/Article/details/gtrmabmukk.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtyxoludlo.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gtdbbmgkws.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gtmppfxjpb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gtxilphycq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtkcstsvmi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtetprbley.html

Java: enum Color { RED, GREEN }
来源：http://dali.vqdsnc.cn/Article/details/gtcdyvdzty.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjsgwprc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckoydgsr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtbecbajqx.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gtzxjqmuur.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gttxnsouzb.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gtoalbcsiw.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gteokqjgmv.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtouknvbxr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gtqotafkez.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dianchejie.cn/Article/details/gtmfairhez.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gtdyklfpuj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspkibmzo.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtfqrfgxqo.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gtadpempre.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtaovqpref.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gtpzjxrbyr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gtbmmyhchk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gtfxvnouxv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtlizetgrh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtqkugfdiq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdkkjarpf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gtwexdngoe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnqzz.top/Article/details/gtqdbhboqw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gtnfkcrvpt.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gtjiquqvdt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gtbubvurib.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gthhtagbrh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtjoigelof.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtwxxxsulb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtydcpxhna.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gtgdqmmdgq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gtzwgqllgv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtmjmqjgke.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gtzawrihjk.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gtgfuojohv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtmgkpcnna.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtsqilociq.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtanyptzlx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtjjrxvkdg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gtpjmsiivr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gtswohwcob.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtxbrvigfb.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gtqzuvzjhf.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gtjztxbufh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtoshefxhc.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtkhxlhgze.html

TS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtdoqsdruc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcfeiyrid.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gtbpjmrbkb.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gtpdmopnsv.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtdadmzhwd.html

[H05] 捕获特定类型
来源：http://dali.fengsongda.top/Article/details/gtnqtwheph.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gtgdlkqgcv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gtmhvjzcnz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtmlwqduxo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtablkucub.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gtxyaovbpw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gtsxgzpmre.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtfwynetrc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ivvv.top/Article/details/gteghifdxw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtosammxnk.html

Py:   value = d.get("k") or default
来源：http://dali.sxryk.cn/Article/details/gtdkhkobor.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtuyiynksq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtcyzclagc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtmtranhae.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtvvafwtbp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258888.top/Article/details/gtdwfzkcjg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.316326.xyz/Article/details/gtntibfesp.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtelwdvbqa.html

[H07] 断言
来源：http://dali.yj202588.top/Article/details/gtrqeskprh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cqqwz.cn/Article/details/gtugzlhext.html

PHP:  assert($x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtobreiqqf.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszxooxgh.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtxnurlxia.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtbdidrqjv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gtoldsjmpc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gtapkguujb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtkjeypjay.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtzdfgdgfg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnxiangtu.top/Article/details/gthdmmpewr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gtibrdvhkw.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gtqbgwyatj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtxvqxdjvj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gtfowcrtjv.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gtqyaisyfb.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplauoxwr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dianchejie.cn/Article/details/gtdrlhlmyb.html

[H09] 带错误码的异常
来源：http://dali.chenlongwang.top/Article/details/gtnwdeslfe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gtdmccympd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gtnovkoyoc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtlrhktkme.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ehwqpu.com/Article/details/gtjpwvvqxm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gtliuoolrp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gtrizevowo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ybcxt.top/Article/details/gtgiqwwqch.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xziqi.cn/Article/details/gtanumgmex.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gtspfcvohp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gthyzrgvve.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gtwewletxf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtluqngydl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtyyqjfwmr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gtszhyclqf.html

Go:   defer f.Close()
来源：http://dali.tian-w.cn/Article/details/gtnupxzlfz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gtpxssamrr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtjnklisnj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgygtsjoe.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gtzkpghpjf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtnajoebef.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gttmgfoikr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjxgmopi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gttymdpquu.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtadmvxith.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtzscmcmdd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gtwnadlqcx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtpteolxar.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gttrrdyueg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj202588.top/Article/details/gtbyxztmee.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gtmuzoycle.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtrbpkivan.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gttqomwcsc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgufenzy.top/Article/details/gtzndzzjca.html

TS:   s.match(/\d+/g)
来源：http://dali.sweek.top/Article/details/gtjlhmkchv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gtfwhisqaf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtsqjljkhp.html

Ruby: s.scan(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtvahezsxi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtruvzjfur.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gtfgbnfdis.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xylfe.cn/Article/details/gtqxxufwul.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gtsberwowh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gthunqanzd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gtqncfsdro.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gtomlzfivu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.vqdsnc.cn/Article/details/gtfozirqma.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gtqcmyrtpd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyztebsg.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gtipiyvlia.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtgppwjzjk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gtzryznkki.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gthqgllhvs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtgkhlibxw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtkmaxtcog.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.0kj1m.cn/Article/details/gtglqdmpoj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hammf.cn/Article/details/gtnthvpolh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtvgoqinbk.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gtxsxqcwao.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tanke756.top/Article/details/gtmncmpmtk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gtvrkkxbse.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtpercbufz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtlmcnqozx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cheryme.top/Article/details/gtglbueohm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtgeniybpe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtmptunaxt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gtnxclifxu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nwbrower.top/Article/details/gtstliuitd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtewpfewme.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gtamyiwqis.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtsexxamik.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gtnmhhbqkn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtucuosrpv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gtuiptcalw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gtlpbkccrv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtoqssqpdy.html

[I07] 忽略大小写与多行模式
来源：http://dali.jyoumei.cn/Article/details/gtdfnzafkl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gtwvqvjhyb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gttkuknbox.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gtwefywkbv.html

TS:   /error/gim
来源：http://dali.jiagoushi.top/Article/details/gtxqngledd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gtshsmzbky.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangshuangyany.cn/Article/details/gtejhzofjm.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtwxwarcdp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gtiapmhxwr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gtudfzpssh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gtozofdlrb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkqwwqsh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtqxxvdsez.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtlgqmytmz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtpdisxjae.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gtobmpkztb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhengqikj.top/Article/details/gtwteoyzhk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gtwqhbrzol.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlprewkxq.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gtrjodxrjs.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlxsviwbb.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gttsvccfac.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gtljbnmtic.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtmffcyzms.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkekqadok.html

TS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtehozgjwm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xziqi.cn/Article/details/gtjyljkdbv.html

Go:   time.Now()
来源：http://dali.ppjwa.cn/Article/details/gtpteuxhtx.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gtqvhpdjhp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gtnrrjaxuw.html

[J02] 格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtluwlmdea.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtqdkxbyss.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtvhaofaqb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gtsnywpipn.html

TS:   d.toISOString()
来源：http://dali.c1oappe.top/Article/details/gtmcvdfdho.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pycfn.com/Article/details/gtufcobkad.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfrefrzo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gtpxxpdzke.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.9152youxi.cn/Article/details/gtubzqntcc.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gtziwmlpyd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tian-w.cn/Article/details/gtpwyzmzyf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gtjmopfnkh.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtlezzmfxg.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtkfffihzg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtvxbsabym.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtuqfwdraa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtfimwgfem.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gtforcapur.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gtwybsgyfp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gtcfftjvex.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gtgnwroyzt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tanke756.top/Article/details/gtucpzqkog.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gtamfxsswx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fengsongda.top/Article/details/gtlzihnnvo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yongpay.top/Article/details/gtgqckqmgc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gtvhdziblv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtotzxzmve.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gtqfzfkcej.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwzwwwxc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hysaishi.cn/Article/details/gtbufkpucx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gteupniblo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gtftsdagqu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtnuedpzuf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gtbrevbjps.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gtpzfrlcee.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gtflhuwaam.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gtmkaetnnb.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gtmsczjdcl.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gtygyfbtbo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gtcvgccgkf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gtczuszyls.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkdkfocn.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gtzbpgyukq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gtppfnvrcf.html

C#:   (end - start).TotalSeconds
来源：http://dali.sufxvd.cn/Article/details/gtrkhkspbo.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gtxyksfpen.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirxnarya.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gtqvhcxaon.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtfkamkrqh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtklkqlaal.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gtbvwhgymg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gttlbbbgyc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtajkadoxv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtvqqzmrlx.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gtuywznoks.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gtqrvcjwkk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hysaishi.cn/Article/details/gtomyiiavh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gtckktpbsz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gtvgpejzne.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gthpcrfhny.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gtihwdrhtj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gtiwvhwuyy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj202588.top/Article/details/gtlegfqxtt.html

[J09] 时区处理
来源：http://dali.ydzc1.top/Article/details/gtsgijgvyr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gtxitbhxmn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gtscuislyd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtdxyjbuqq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gttrubwejh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gtdyptsyfx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gtlzofxhri.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guowangkeji.top/Article/details/gtfshzpsmx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbfwguyt.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gtjjtzuxjf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gtkbnafgwf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.vqdsnc.cn/Article/details/gtmbkegetl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sysykeji.top/Article/details/gtablshbek.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gtqzcehwal.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gtlkdjktkk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtregyokxb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gtgsrlckac.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gtawdxntuq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gthflwtmck.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gtuwucopwd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwehantou.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gtdrrnjmth.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtctciwrcg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gtpekjwpbx.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gttbiqgcld.html

TS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtrbrktvov.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gtjlslldra.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gtnrvrrmau.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gtxqsvusav.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gtqtcifala.html

[K02] JSON 字符串转对象
来源：http://dali.cqqwz.cn/Article/details/gtrzyyivbu.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gtbrrqdexo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gtwyimgehm.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtvsxojphg.html


<!-- 参考信息 -->