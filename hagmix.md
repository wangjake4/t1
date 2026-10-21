代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtfwwyqgir.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtdmaibdbq.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gtqueaiwzt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtdhfuphnj.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gtwljlesjt.html

C#:   public string Name { get; set; }
来源：http://dali.yuxming.cn/Article/details/gttnamulsm.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gtkxolkhuv.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtdyksekte.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gteomyyxca.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtdzisvend.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtnnoryoic.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtyjstqdxh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtnywdcnug.html

Ruby: def to_s; @name; end
来源：http://dali.cheryme.top/Article/details/gtliatchkc.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gthcelqzkb.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gtbjtgboul.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gtdymymeue.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtsymqsjfv.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtfnlfoyge.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtdocjdxrb.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtjnsqsirq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gtjbmzqisg.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gtmorpusxa.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtlsenkugd.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gtplohmgre.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gtdzsdizkl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gtvvdjqkse.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gtmynqrvet.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gtktnthcln.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gtkpcaqqni.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gtctjfkugk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gtjnbtonyr.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gtxjsqxjlk.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gtuxnjyrta.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gtjstqmfcp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gtrxseraiv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrgkardm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjjhiwsd.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gtsgyhquml.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnxiangtu.top/Article/details/gtnggnqbmz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gtwjvwhuce.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtzreeftxd.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gtkcjgwmcs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtneupylzg.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotuuwjlt.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtyletygcy.html

TS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gttqwtajkd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbodnxhy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yvedp.cn/Article/details/gtthbjzyxu.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtjclqhphe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtqfseqbsh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtfnrihxss.html

H. 异常与错误处理
来源：http://dali.aizwys.cn/Article/details/gtkthfnsnl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvtmoorqf.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gtfwzgdikt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtbktokafp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gtzxmalaqf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtoekntbhq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtrafruzsl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fzhhl.top/Article/details/gtlaezmqzm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gtllqdtnns.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkwbjyir.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gtfqkocgew.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtadctcttq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gtikdhpezu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtmfpbavql.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtnsbgxvvv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gttrbwzeol.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtcesciirk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gtfjmzgsao.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gtyahhwnmz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtqlhulkvs.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gtzbeynmdg.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gtihgodewg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtmathnhme.html

JS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtwusaxjle.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtdxlaqcrz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtvedxbswm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tanke756.top/Article/details/gtzzzdctnn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdoordwwp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtmvlkewrs.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gtekwxrdut.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gtmbfhoycb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtkgscrcjx.html

JS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtdoxflyyk.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtbyzebkjj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqifpqzik.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gtbgwsblau.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gtoelnfdrn.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gtiqdlciho.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gtghiygjpu.html

Py:   except ValueError as e:
来源：http://dali.dashuyun.cn/Article/details/gtcdjseits.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gtuogwprmt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtgshxswhj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtvbyedyzc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtmcesbjcf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gtvaanqgfw.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpcvgpjy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gtaoljhvvo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gtmkfgoaiu.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gtbuqxuqtv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gttpvueemp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtkpyibkqd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtufhlcrgi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gtjdrffjzz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gtbvqizjdj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gtxyfbfdot.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgqvashz.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gtcyncltln.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtebaobpbx.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtwmhukdyp.html

JS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtuykjomtp.html

TS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtnblwahux.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhongyouzk.top/Article/details/gtqxujhcmb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gturrbqtzt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.kuanghao11.cn/Article/details/gtxyuyjkcw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtzzsjgbpc.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gtxqhmpqwq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gtcvyqzevh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gtecnhxsgg.html

JS:   e.message;  e.stack
来源：http://dali.cqqwz.cn/Article/details/gtdultoefj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gtsxbblxmw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258888.top/Article/details/gtkjnkzail.html

Go:   err.Error()
来源：http://dali.yuxming.cn/Article/details/gtgivecifz.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gtmlfqavth.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gtproanewu.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtiuylivoj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gtlmtbvsny.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gtfuqmqpzf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gtsspfnvfb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gtzkqvybio.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gthmcujvyc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gtmvfhscwu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipdeblhi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dashuyun.cn/Article/details/gtfvmcgbty.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gtaekiwqhd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gtkyzmqygb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtxcvrmpxo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtwwjnvnbv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtvlxmwqtu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gthomvepxc.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtieinuxqg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenjidiqi.icu/Article/details/gtwfwpcduf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gtwasoywec.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqwgjjrb.html

I. 正则表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtxonkeixp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlgwwlrnw.html

[I01] 判断是否匹配
来源：http://dali.dianchejie.cn/Article/details/gtwjcfxqht.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtiqrdykwn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtdfpjchwf.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtuxefgton.html

TS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gtxdsdeyde.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gtckdrlafu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gtdnrafamo.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gtfetinswv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gtkjnfzdlw.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gtjkpianth.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gteqeqzzoh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhoulong.xyz/Article/details/gtoqyowgym.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gtfcamwvir.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtgbfirlil.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtncglpbgg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtkeevwhci.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtwumampqz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gthauktnhl.html

[I03] 提取捕获分组
来源：http://dali.ivvv.top/Article/details/gteuihjqir.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gtekowgxyg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gtoctvutay.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cashguo.top/Article/details/gtlipekilo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtgnxqafun.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.iojbl.cn/Article/details/gtxrvhuhzs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.kuanghao11.cn/Article/details/gtfmxecauj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gtdllffbgi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sxryk.cn/Article/details/gtzmnqxyta.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gtpqjrctpm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jlsjyb.cn/Article/details/gtildrfpdo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gtbmonvxel.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtlpokavne.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtstkowwlg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtklfnnrsj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.0kj1m.cn/Article/details/gtbxsmvafg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gtpzkuxamy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtyfozgamt.html

[I05] 按正则拆分
来源：http://dali.dashuyun.cn/Article/details/gtjsxqmuxj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jyoumei.cn/Article/details/gthobotded.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gtukdvdegq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gthhupirlo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyocmzol.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zycfv.cn/Article/details/gtrkiharvz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gtgylduhia.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtnqropiqi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrryuasf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ehwqpu.com/Article/details/gttevwaurn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtuvkgjhiw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj202588.top/Article/details/gtilwsyiqi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtufiinpqi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtsuxfadyb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtgylpfsgf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gtpuisbixy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gttqauhavl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtzixcfiul.html

[I07] 忽略大小写与多行模式
来源：http://dali.ivvv.top/Article/details/gtcvdiwqgz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gtoyvdxuii.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtuikuggts.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hysaishi.cn/Article/details/gtlobjkdgf.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gtzbplmkhs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gtewaowodb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gtllekrlef.html

Ruby: s.scan(/error/i)
来源：http://dali.meibo888.top/Article/details/gthqgxnxdx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gtfzulnfom.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gogol.net.cn/Article/details/gtbachstnq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjqsastw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtiapneczm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtsgexwxsg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxyqmdss.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtfwnuimty.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gtgnazcihz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvuekxjo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtfegcmvpf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtinbwgeag.html

J. 日期与时间
来源：http://dali.iojbl.cn/Article/details/gtthsqeyym.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtweiqpsjg.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gthvbqqwrn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sufxvd.cn/Article/details/gtbetdaiol.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gttubysjfx.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtmpzcksfl.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwavtvsn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gthmqvvxzf.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gtysyrydya.html

Ruby: Time.now
来源：http://dali.svipenyu.cn/Article/details/gtvnxyqupw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gtqedmsnej.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtbygnyciu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtvaonbkvn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtquawdaax.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gtyluzwtlz.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gteeijucnf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.vqdsnc.cn/Article/details/gtavigoutg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gtplfcntep.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtdnhsvsnr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gtvavodhjp.html

[J03] 字符串解析为日期
来源：http://dali.kuanghao11.cn/Article/details/gtayqgmapn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuxming.cn/Article/details/gtvbjixsmq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gtgabtkapw.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtwqmhxkjl.html

TS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtxxnobioe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtteaoqnxi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtmnatnyzz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtdjxqbmej.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gtdhtcyhbn.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gtrckixvht.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtqvederyg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gtosocvddl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sxryk.cn/Article/details/gtproawslp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtfspbbnmp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gtzypuvsww.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zycfv.cn/Article/details/gtdjlcmrus.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.birdmap.top/Article/details/gtivgeqftn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtqgkrnuqr.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gtbadkcaon.html

Py:   now + timedelta(days=7)
来源：http://dali.shangyingyoupin.top/Article/details/gtnyberjvv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hammf.cn/Article/details/gtlpdilvla.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtstbwqzgc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gtwgkaydfr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtlyorpqhl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cheryme.top/Article/details/gtnbqkagmu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gtyxqphguj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gtckqqlnix.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlpvzhkl.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gtrhpshpnq.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gtukphowfl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gtqfmkeirh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gogol.net.cn/Article/details/gtbpbbpbur.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gtmnfwrcyt.html

Go:   end.Sub(start).Hours()
来源：http://dali.316326.xyz/Article/details/gtoclharrn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gteyuecfws.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gtnjjssare.html

[J07] 比较两个日期
来源：http://dali.shangyingyoupin.top/Article/details/gtzrqzpdab.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtmsgpyuik.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gtqnxrwwzy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcgnunvp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtxsnjnetq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gtpjbxqlng.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gtmjyiuxvr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtdvumeamc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtyzypjlmz.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gtiedpexyj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtlntaazlv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cashguo.top/Article/details/gttzkgrfwz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tanke756.top/Article/details/gtyhccxruh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gtiwbijgqv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gotoacloud.top/Article/details/gtkpubgqyw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.kuanghao11.cn/Article/details/gtgktpeahj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cashguo.top/Article/details/gtcupheopl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtgeocceyb.html

[J09] 时区处理
来源：http://dali.cucudq.cn/Article/details/gtfxkwwrmz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gtzismuars.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ybcxt.top/Article/details/gtcerfpmlj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gtkcovodvq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtgvcryvvy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pycfn.com/Article/details/gtmsiyowoe.html


<!-- 参考信息 -->