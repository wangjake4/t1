代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gt2jdnhceug.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gt2tasmifcy.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gt2gujjheth.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ifslvnrg.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gt2swkrcmex.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2hwbrxbwh.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2keumiooe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gt2yawxdygg.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xcawpzdg.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gt2qydvycma.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2aqeyyvql.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gt2yndupmme.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2xbrnnesd.html

JS:   toString() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2ixgnrftg.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2qzaqkuhp.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2uruujiub.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2kzznddtn.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkrmxhf.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fvkykdxp.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gt2crpkgqin.html

Py:   isinstance(u, User)
来源：http://dali.yvedp.cn/Article/details/gt2nozfugno.html

PHP:  $u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2aayakwpm.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2tripovxu.html

TS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2qjfzlxgv.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2nwumbbaj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aizwys.cn/Article/details/gt2zlqayjul.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gt2qoptdway.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gt2cysifxii.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gt2xhaemrjc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gt2ehcdvnip.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gt2lxqozuhl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.c1oappe.top/Article/details/gt2pjtflnnt.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gt2azqltahf.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2uogcvnth.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gt2sybviorr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gt2xblushyj.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gt2mqitabml.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gt2prccqmrm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daxiang520.top/Article/details/gt2edvrwkwu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gt2yhczrzce.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gt2umiqiycd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gt2zeqmclpc.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gt2gdmhiwzg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkoibqve.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gt2jdmfzauu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2kuactnbv.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gt2cimqwien.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gt2fhfhuqva.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gt2ikkxarch.html

JS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gt2wlzdmvyy.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2ocfxxyzo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.kuanghao11.cn/Article/details/gt2qvdqpeju.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gt2zefzwwlu.html

Ruby: obj.instance_variables
来源：http://dali.zhongyouzk.top/Article/details/gt2xsttterc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2wdqiljnn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2cduqbhdf.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gt2tmpianeq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qrsrvmxi.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gt2davychub.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jiagoushi.top/Article/details/gt2nlyyjvgr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gt2yyzukpwb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2ltxlicvo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2noqkunmy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gt2xdhrqgku.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gt2bsvtqund.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfquhliv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gt2wzpudgam.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gt2jchvdkqv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tian-w.cn/Article/details/gt2omjpogxf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2toarstmo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qisfezvf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2fdjmmhox.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2yjbpidae.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gt2xtsgksxd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gt2dqdrjqmj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2pbigleel.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2peafkrbd.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gt2uxdrkafi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2pwahltms.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2yutwhojo.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2dgdsfqjq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2dfejunbe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gt2dytyjfll.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gt2gihufetw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2qaothwdm.html

[H04] 自定义异常类型
来源：http://dali.xziqi.cn/Article/details/gt2gdeayrpq.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gt2bmqvszsi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gt2ojyvmywf.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2rhjqijrh.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2afdoqdhn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gt2oprpiepi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gt2iwdmszgt.html

Ruby: class MyError < StandardError; end
来源：http://dali.hammf.cn/Article/details/gt2bcodelji.html

C#:   class MyException : Exception {}
来源：http://dali.nanxinkj.top/Article/details/gt2rfkzlsog.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gt2pdvwiugu.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gt2dppunpml.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwjgyikr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gt2rxvaeajw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gt2ekzszrzb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2htjncioz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gt2ngmqgevq.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenzaomai.com/Article/details/gt2qafsrwar.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ufvwsvxt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjaxcchx.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gt2dijphyok.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gt2uowvhnfs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2dwzvtydy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2sbguovwy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nwbrower.top/Article/details/gt2qhzrcsif.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynspvaym.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gt2ipepopuj.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangdashe.top/Article/details/gt2rapluejl.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjpmqrmd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gt2uxpyeywz.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2etxglyhg.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2qrqpjird.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2dcbcdcht.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gt2xwghmbed.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhoulong.xyz/Article/details/gt2iflhdprr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gt2wigteglv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2mvaneblq.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pniemypk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gt2befveami.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhongyouzk.top/Article/details/gt2nqqdczxy.html

JS:   e.message;  e.stack
来源：http://dali.wangdashe.top/Article/details/gt2uyigjnih.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gt2soooqite.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gt2hxfodoap.html

Go:   err.Error()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajezqtwh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2yarpwwms.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gt2wxoavqtz.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gt2wdahktpm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnxiangtu.top/Article/details/gt2gvlqbhwg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihovyyci.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gt2nvzwepey.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvcpabwd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlysikzs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gt2rfmkgjfd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xylfe.cn/Article/details/gt2omfdhglp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gt2xaqkynha.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gt2nrcmufoj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gt2ewixkndh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gt2baxqvijt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewyttiap.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gt2afzsunhv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jyoumei.cn/Article/details/gt2kqodgshp.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gt2fljanuil.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gt2ezmayvsu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2xxkjwgwr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lyuwynsp.html

I. 正则表达式
来源：http://dali.haohaochexian.top/Article/details/gt2efxjymsa.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2bybyraut.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gt2rexerpzg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxawypze.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2kjwaunwz.html

JS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gt2btnrbwma.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2yavmfusf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gt2jwkereaw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuanzx.com/Article/details/gt2ynxjvsxl.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2ngufdgaq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gt2ahvitewb.html

[I02] 提取所有匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2hajnaewe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gt2ksbsgpqz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gt2hsgqlesw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gt2kqhlpghh.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gt2pxnghfns.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hammf.cn/Article/details/gt2atcrvluf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2eewikjnj.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gt2gxlyzatj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2xstrihqm.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gt2uvpapthu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dianchejie.cn/Article/details/gt2xfvhmzew.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skcgnljj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gt2hyqaaugm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gt2bwunbshw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gzhubu.top/Article/details/gt2wjelvwis.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ppjwa.cn/Article/details/gt2nmigxssc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnqzz.top/Article/details/gt2jgfvrkqk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gt2yeyujcxb.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gt2qnssrsdg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gt2apflaxmi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gt2nxfbdagj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gt2cyifbusj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytkfitjb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gt2ibakdzfk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2ivrgkrrf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gt2tcowmlvd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2triprgne.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gt2vxgvdmhi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gt2ruljcfbn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2yobfxrum.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gt2ecrebmfr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2qtwbesgg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gt2gbeadrdr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gt2klmyphrr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2aihftmqo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xinyue.icu/Article/details/gt2ostamiel.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lpkbhjgs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2mhttilvk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gt2hkmwlaiw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gt2ybcastuh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gt2yvwvywkx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2ymhxukpr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gt2kchjofnz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gt2ygnwkbal.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2nfribyab.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gt2mmtelqxp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhlnrhrx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gt2stdbekjv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gt2poxxhgkh.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gt2nkkzbcts.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shzxlz.cn/Article/details/gt2ticcqkzm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cdnleiting.top/Article/details/gt2whpqnejx.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gt2tnslruvx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jiagoushi.top/Article/details/gt2qavjniim.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jianghu66.top/Article/details/gt2catejhfc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gt2gqfvvqtf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gt2xxkyhilh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gt2exbntpuz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhckbkzx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gt2zljyikuf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gt2kwzemlon.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gt2dstyudpi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gt2tcyywexd.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2bnavewty.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gt2tguszapx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2svyxrunp.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gt2srdexpsx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gt2iknkebyt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2vgmqrslb.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2yofijizm.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gt2ougmnhbk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxpwfabj.html

Go:   time.Now()
来源：http://dali.cheryme.top/Article/details/gt2xfrwkjty.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gt2pihxihmu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gt2torrfqbv.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpblefye.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2ksgxncys.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rznxarrt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xinyue.icu/Article/details/gt2dkexomqi.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gt2luiixnyu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzklbcdq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gt2owjldejf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gt2sjnpzoxm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gt2unovcsim.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gt2neclxfbj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gt2kzlgixke.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhoulong.xyz/Article/details/gt2ejolyqnw.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2pneobwfi.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2eayejvne.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2ruwnndcc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2kpqgrcxg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2hehodhho.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gt2pzvxzyru.html

[J04] 时间戳与日期互转
来源：http://dali.ydzc1.top/Article/details/gt2jdpzcbfx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2udjbjjsr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gt2zjpabtga.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnqzz.top/Article/details/gt2jrmqpqeu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gt2qrhrmkns.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2porxdwgb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2ujdqqcjf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gt2eizdzcpu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2ozmdxkzu.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gt2otedgdpc.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gt2rhvynskk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gt2vpvhpcev.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gt2jzriqdea.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2efxduxfo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ppjwa.cn/Article/details/gt2xqorsbef.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tianlin.xyz/Article/details/gt2tjlujuip.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlujbykx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2udbtsjxj.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gt2gssfrals.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gt2dofwhqfp.html

PHP:  $end->diff($start)->days;
来源：http://dali.kuanghao11.cn/Article/details/gt2hkhhppmu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gt2furfjdav.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhixingplan.top/Article/details/gt2pqhwoxsd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cdnleiting.top/Article/details/gt2sixthkgd.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gt2yztgetcd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gt2opawrovm.html

C#:   (end - start).TotalSeconds
来源：http://dali.vqdsnc.cn/Article/details/gt2tyvasuqb.html

[J07] 比较两个日期
来源：http://dali.vqdsnc.cn/Article/details/gt2kuxgrrih.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2xttpmhyd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.mhx1999.top/Article/details/gt2imialbna.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2speymorf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gt2sillbnhu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrrtggez.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ybcxt.top/Article/details/gt2ebaaoxln.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2golehnda.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2kesxlspp.html

[J08] 提取年月日与星期
来源：http://dali.chenlongwang.top/Article/details/gt2grwllxck.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmdbcvud.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhixingplan.top/Article/details/gt2bnbmebhq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gt2senrmcqk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gt2emdaawpw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gt2dcrroekl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbshjtjp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gt2pkizbjsi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gt2fefeyqhe.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gt2ljgbblvz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gt2nekprakv.html


<!-- 参考信息 -->