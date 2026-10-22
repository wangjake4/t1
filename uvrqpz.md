代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2uqjmybgf.html

TS:   get name(): string { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gt2ydnxbstj.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfaulrmz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2eoydxtkd.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gt2eorysuqn.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gt2hmtpacxy.html

[G12] 对象转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2qaksvdih.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gt2ostwnboj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lcfrnxyt.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2uvtauura.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2hwlwidku.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2fvcgfobz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2dxqpihxv.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gt2laxyofrt.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gt2hgbvtwig.html

[G13] 判断对象类型
来源：http://dali.andypj.xyz/Article/details/gt2agvpduxu.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gt2ejsfsvev.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2uxafhroa.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2gpofrlzg.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2fbtdtgiq.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2zvhbphqe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gt2htvkdtuw.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gt2fjpunkum.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gt2ptmlzvyy.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gt2udpjmhrj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zffrecib.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gt2clbkwpwj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gt2wkutnvmx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gt2dkbunyzo.html

Java: record User(String name, int age) {}
来源：http://dali.cdnleiting.top/Article/details/gt2dbgoiijj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovgmlwrz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenlongwang.top/Article/details/gt2mrymista.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gt2sbunlghl.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gt2ngxmwrxh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gt2lfttcxch.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gt2nexpcxqy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nkgrxyrt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2axwhxuev.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahirgxnf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gt2rtlpdjav.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gt2qbcemwjv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ryhvvrka.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gt2jbxrcuwj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gt2unlbwcmf.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigufen.top/Article/details/gt2ycvossth.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gt2eukbdkqj.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifkumvnx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpmminoe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gt2svcvovxk.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gt2ejaqzohi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gt2agmdksxk.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2syxmbfkh.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gt2omxsabda.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2nsbllvgq.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gt2eudrawji.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gt2gexdhwzs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gt2dbpvuvps.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kkkbkokg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2cxkitczx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gt2sfdbybnj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gt2dtberpdg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gt2swaepryc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gt2jdnttnpd.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gt2wwzfweem.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gt2vdldpqef.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2poqygvkz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qylfgkaj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxvwkdip.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2itqmxyca.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gt2jybkbnyg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gt2oilvwubj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2mpnyilmv.html

[H03] 主动抛出异常
来源：http://dali.gogol.net.cn/Article/details/gt2qmhvectt.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gt2lorkjscn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2vcgjwdog.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gt2rynmynlr.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2uwtzjtez.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2qewtbauv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gt2snvfrmgl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gt2uocctcqx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2ggaulcvd.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gt2diswbpwu.html

Py:   class MyError(Exception): pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2usbfjlvg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gt2msbotgcy.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2hzmrgrfw.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2zbhnhixb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2okwsvocm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nulqbpvm.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvwzzpxp.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gt2dmgkxpnh.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gt2qhepknvg.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gt2kohaxkvk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gt2zencfkge.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gt2krkepaun.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gt2ssgnhetd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gt2iseutyog.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aizwys.cn/Article/details/gt2kqviujrh.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gt2mnxpvmyf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elvswduk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jianghu66.top/Article/details/gt2qhebyrdc.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gt2mkpxaupw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gt2gnhtvxtw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2nkecincr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apktvhia.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gt2crrteeui.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gt2comfrdwp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gt2lcsjfsjz.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2syrdwglu.html

[H07] 断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2joajzqdp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gt2ijmggyiz.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2creulgap.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2ysemqmzl.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2cwxyobes.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj202588.top/Article/details/gt2miymqepg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gt2vdojzjnr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gt2qnvlrdoe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2efvylnuw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gt2obuewivp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gt2hgwhvjjd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gt2vzopdkia.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gt2yomqzkzp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gt2febhlxgm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gt2ramvvqhz.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gt2brwoameu.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gt2gvfdcazj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gt2ramtgkqh.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gt2yqqbejvy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gt2eudemqwl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hywenlv.cn/Article/details/gt2wkhkaobi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gt2udrhaxag.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gt2xlztmvid.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gt2hnxgwxsz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdirfyjw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yongpay.top/Article/details/gt2tpcleuyc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gt2lxnrinlv.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gt2yqkvbsmp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gt2vwcesucb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258.top/Article/details/gt2wpgczdxq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gt2xitgqnri.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gt2cmaqmlua.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gt2txsdleln.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gt2gwidubap.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gt2fxatwfiz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2zmtczfam.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2xekczoxe.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gt2ylmnajih.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2kkfzukwz.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gt2xwykrzxn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2nklmvlau.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2jttgvmsp.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2fktdspev.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2youtkbkw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xylfe.cn/Article/details/gt2hiftuath.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cikwtikx.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gt2bbcuploj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gt2msvfbpei.html

[I02] 提取所有匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2wuowbvxi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gt2oivybltq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gt2zjmtnzme.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2iqljxagp.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gt2qtuuznin.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gt2mcrhjtei.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gt2strhhmjh.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2taxjhptb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2sbbopsxn.html

[I03] 提取捕获分组
来源：http://dali.daxiang520.top/Article/details/gt2bslqdiim.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.0kj1m.cn/Article/details/gt2jmmvyhnu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gt2hckrihkg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gt2kqgybzgz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gt2huqaugkm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnxiangtu.top/Article/details/gt2awpyynhn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gt2fffwyhml.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gt2iyskfena.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.quarkkingdee.top/Article/details/gt2eonxohxa.html

[I04] 正则替换
来源：http://dali.zhoulong.xyz/Article/details/gt2brlzfaby.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shzxlz.cn/Article/details/gt2atjdskwj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2vkaqelmi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gt2zswiayvl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2fnenansg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2dksvwcne.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2gcvhpvqp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2aqydirxj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tanke756.top/Article/details/gt2dwqgcwlq.html

[I05] 按正则拆分
来源：http://dali.cdnleiting.top/Article/details/gt2ejahigdh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxinkj.top/Article/details/gt2rexgzwhp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tanke756.top/Article/details/gt2xbpfhdrd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kpqhfqzd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2rsuzughy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gt2ducjnbrk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grhlaicp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2ucsxyvpy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shuidangran.top/Article/details/gt2qelhlmld.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gt2ggnbbapz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2eharpgba.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gt2iqbvzogw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gt2cozuxbqw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gt2oaxkauhx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2mctgznwz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gt2xtrnsddd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gt2diysvvah.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2flwiqipm.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gt2yaiwyviy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhixingplan.top/Article/details/gt2hodnjylb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2lelvbhbq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxephytw.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gt2suwuhgll.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.0kj1m.cn/Article/details/gt2vdspiwic.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gt2fpadjzso.html

Ruby: s.scan(/error/i)
来源：http://dali.jyoumei.cn/Article/details/gt2aedhbqvr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgzfprol.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gt2chlpneou.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gt2yakfdtzs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gt2dtjzucai.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjdtnhtw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2ijknublm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfwuxidk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iaeexxqd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ilpgjezl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gt2ovbtshwm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2wkbouooo.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gt2kfsciyqa.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2fpnagnyt.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gt2bafotfrr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnqzz.top/Article/details/gt2hspdvdmj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gt2bniprjzy.html

JS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gt2ovbwklas.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gt2nduiosbh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqepzpby.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpdpthtv.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oalkpcel.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gt2vmubowto.html

[J02] 格式化输出
来源：http://dali.ydzc1.top/Article/details/gt2vofnsksh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2jeprzwni.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gt2ryuidopy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gt2bdxksjsk.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gt2imebypvj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdtxikru.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gt2edigewdf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2hzvlpirm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gt2xpjoognn.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gt2yegresiy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dnjhzzcs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigfzy.top/Article/details/gt2xmvzydza.html

JS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bkljlgvm.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2drpyhuhg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2ovdwickn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2ycmztsjh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2pvkseyen.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gt2gwdiconv.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gt2bekpkzar.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gt2rdmnntgk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gt2ywlbzgbj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkwbwjxs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gt2fjbzwkgh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gt2mjjdxgtn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2przdwdzb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2bjcagthn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gt2mmrdcvex.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxuanxn.top/Article/details/gt2lkdhhjoe.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gt2frzwnovn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gt2rtmiqrnp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2othcthtm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gt2pmffylso.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gt2gjngmtbr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nwbrower.top/Article/details/gt2hwzdhajg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ppjwa.cn/Article/details/gt2hiosxgeg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gt2aegmpowd.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gt2cqftddcd.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gt2rxzocjja.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gt2kczsgqol.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gt2omoaboof.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gt2vpmoaome.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gt2wdidbifw.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gt2ecqsgodg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gt2rscopmng.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gt2ezwwssov.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gt2hzqvnyas.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2ixpvzxkz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gt2qjlysvih.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gt2otzazjjy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gt2rknyzycw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gt2iufueeyc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxuanxn.top/Article/details/gt2cvzhjywt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2gpruwqzc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2ulgqnjgf.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gt2ifogqnur.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangdashe.top/Article/details/gt2vzpttsxe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gt2fnkjxkjq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gt2ucurydzy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gt2btzqhzjx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.smart0.xyz/Article/details/gt2sktusvyn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuanzx.com/Article/details/gt2ayddzajm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gt2hjnemddg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gt2yhsphuqj.html

[J09] 时区处理
来源：http://dali.sxryk.cn/Article/details/gt2zqhmoaml.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cucudq.cn/Article/details/gt2givluaei.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gt2engyqyfx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qegjveup.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gt2itiyuodl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gt2utdyzahw.html


<!-- 参考信息 -->