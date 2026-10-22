代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gt2rcxyeteu.html

TS:   get name(): string { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2geooacet.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2onpticeu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2oaxfwmfn.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gt2vvqkoxny.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gt2vqxxqfgb.html

[G12] 对象转字符串
来源：http://dali.yj20258888.top/Article/details/gt2tvnbjatx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wmujaaps.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gt2yoxkyyhp.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2ozldpvll.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2xsjubuzm.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2dpehluzi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2psgkqcip.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gt2ttvyyeak.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gt2xktjiiwd.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gt2dmybxvbe.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gt2qxivxmeu.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2arotngdx.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihjytbnj.html

TS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2yxyzfmwl.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfkwkmdy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akueqzax.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gt2baolszke.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gt2rocfdhbt.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gt2wnygahzx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gt2lsjiwbie.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxwluigq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bgbpurza.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gt2xewdxiht.html

Java: record User(String name, int age) {}
来源：http://dali.andypj.xyz/Article/details/gt2sgrhoerp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gt2jcepnnjf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shzxlz.cn/Article/details/gt2ddollzit.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gt2wmdrgywp.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gt2voyqdzmw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmdswltz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gt2pbphliix.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gt2buqhuodg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2erygxliy.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gt2vzmrkkzd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gt2agbxkiev.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehxujbwp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2quaqxpsy.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gt2oyazlhtf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gt2xicwlifs.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ukhxtute.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2lutbtmqu.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2krpwznbn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cheryme.top/Article/details/gt2hsdtksxw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gt2dunqcrsc.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gt2ccitxung.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2ggntykwp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2xqkvqtqb.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gt2lxuiwfmx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2jcrabfdz.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgtschcj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gt2vpcmwrnb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gt2jsxcxnkz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gt2iibcqwmw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmroheob.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gt2kcfxhxow.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gt2wvfzohjv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gt2kmhwvhve.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.snrcjt.cn/Article/details/gt2fvunnctn.html

[H02] finally / ensure 收尾
来源：http://dali.chenzaomai.com/Article/details/gt2ntpdnlnn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gt2xulensat.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2guvldzty.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2ppweygni.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2nwgclhrc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2ztiugptf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjvmdtqi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.c1oappe.top/Article/details/gt2acngiejq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbobobn.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gt2uvizkzms.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gt2kvhoagsd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2qbegzzwr.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2mmpftiih.html

TS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2ofcvcosa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2kbxavfkz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gt2dcweefoh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gt2frppmajg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2affmfjyu.html

[H04] 自定义异常类型
来源：http://dali.yj20258.top/Article/details/gt2yheadsok.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gt2mtkjwzlh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gt2bihtxkwb.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gt2cyiapmjh.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2inynfjkk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gt2fapbprkb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gt2tldjxong.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gt2xeeoyzwd.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gt2aaouacbn.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2kxgubkaf.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gt2pftclfft.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.c1oappe.top/Article/details/gt2fxxzdehy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gt2setqujbo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htuecrnk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gt2ggisnsop.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxivpbta.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmwplhvp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gt2ldhzwslp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gt2wvhrsxoc.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gt2firqgnvj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2ryhzslou.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gt2jhaigpse.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gt2igprgwbi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gt2furvhemu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fpxvjtgq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnvomtim.html

C#:   obj?.A?.B ?? default
来源：http://dali.sysykeji.top/Article/details/gt2nncxdmau.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gt2fkqnwanw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gt2diptevjp.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2biwlayme.html

JS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2sgwewomq.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2orhdyzvz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gt2jxofyfdc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xinyue.icu/Article/details/gt2nnopzokg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gt2cglmbmdg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2murdgktt.html

[H08] 获取错误信息与堆栈
来源：http://dali.9152youxi.cn/Article/details/gt2ibzkhpdr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gt2kftvazix.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shzxlz.cn/Article/details/gt2smqohzhy.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkqkoeob.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gt2ziycfmal.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqkwnamw.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fifkihqe.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gt2pjldkcuw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gt2mbniicnx.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gt2onbmlszi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gt2ctcrnybl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gt2uvquxfso.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gt2tsihmwmw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gt2erdrlrey.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gt2szahefgu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2rawykmna.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gt2ymmtcbzo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2leluyuhk.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gt2ymxgpxkx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvfmeihv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenzaomai.com/Article/details/gt2tahykzeq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gt2ayczwkzx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gt2wquhrrbg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gt2chisnfwv.html

Go:   defer f.Close()
来源：http://dali.andypj.xyz/Article/details/gt2gbjfwlom.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gt2duknmzzc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2rdiobmup.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2epbwfykd.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gt2lyysbgfn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2rebtcuxo.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2toxqucnf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gt2reccyqki.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2zqafmcot.html

JS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gt2qiqdpjyc.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gt2exydkoiu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daria6918.cn/Article/details/gt2gfoeyxsl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2fppnvpxg.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gt2aycipdbn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gt2rzloaknk.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gt2kizxkoaz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gt2szplyopk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gt2dqykrjwz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ehwqpu.com/Article/details/gt2gfhnrell.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vlzogajk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.0kj1m.cn/Article/details/gt2movyfzlc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gt2fbqiyrns.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2dmaqtobp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gt2fggamqhf.html

[I03] 提取捕获分组
来源：http://dali.zycfv.cn/Article/details/gt2lsmxebwn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gt2mriifpgb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqdnxjmq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gt2osgmitve.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pycfn.com/Article/details/gt2vlwanygs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gt2kgpgzkrx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gt2wafolsug.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.iojbl.cn/Article/details/gt2jdndjjwi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gt2lwvtpakf.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tttnzigd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gt2itnddwan.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gt2dakqkoxz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gt2bvspjcxq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2bvlrvgjl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gt2byqayvpg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gt2hbrnlblb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gt2jyfdmbci.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gt2cnmhlqlj.html

[I05] 按正则拆分
来源：http://dali.cqqwz.cn/Article/details/gt2xszjuuto.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2dyqeyzzg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gt2iffjqizn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2glsbnftn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2gnrgfjhz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gt2uuxhudfh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2jplqfxnm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmazobrw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgfzy.top/Article/details/gt2nepjtcwf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gt2jofwkmqq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2heyujbiz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gt2smntunew.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gt2imfcfemb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gt2accixjuf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2qgzcuqyj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gt2qzuvdqpl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gt2pxlrqoct.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2skosmymy.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gt2hcyktcqt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djpswlmd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gt2hefetvff.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daxiang520.top/Article/details/gt2tqulslde.html

TS:   /error/gim
来源：http://dali.jiagoushi.top/Article/details/gt2djmmhitu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.feifeiyinyue.top/Article/details/gt2glmefnsl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gt2rqnqnfwk.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gt2qzwurgsr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gt2xdbxxrvo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tianlin.xyz/Article/details/gt2sigbmbpp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gt2utprslug.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fszcmumc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2oowwyfjz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gt2brvnspbd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2xkmhmnby.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gt2qczvvupd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gt2dypywymn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gt2vjjujudc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2kqqrdjoa.html

J. 日期与时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ufjxclel.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2cdssydjq.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gt2kvqwohsm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gt2rydfuzwt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gt2nrxggozo.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gt2rwrjdjpl.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gt2rvqldusq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sysykeji.top/Article/details/gt2uszxicjd.html

Go:   time.Now()
来源：http://dali.sxryk.cn/Article/details/gt2eslffnhq.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gt2chkubhio.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gt2xmrzztzy.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gt2tvfijwwo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gt2ouaxvmln.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gt2ufgnsuah.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jtjpwmki.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gt2fylhkvis.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hammf.cn/Article/details/gt2fcdhgxdl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gt2qonzyzgg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2pyitddfi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gt2dcpimyma.html

[J03] 字符串解析为日期
来源：http://dali.shuidangran.top/Article/details/gt2dpfywjcq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gt2owvzegym.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gt2kivtzwmt.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2byfsvkil.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbzkdpkq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2sjyhmava.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2xruteowi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2dwcgfmhb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gt2zzyznkby.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gt2bbxigijh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2anazkzee.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aizwys.cn/Article/details/gt2lzlibrgq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gt2tvjlntbt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fengsongda.top/Article/details/gt2ehqblzvr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gt2swtbnurs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gt2ojkfotza.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2smsubczc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2dsupkkqd.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gt2hbjedldi.html

Py:   now + timedelta(days=7)
来源：http://dali.redwolf501.top/Article/details/gt2udhpxcfs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gt2bipdsxkv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccxaeycj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gt2svtjtrda.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gt2ehlsrpho.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.9152youxi.cn/Article/details/gt2olrghkox.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gt2pyozwfim.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gt2gseufjsy.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gt2pnzonrdh.html

Py:   (end - start).total_seconds()
来源：http://dali.daxiang520.top/Article/details/gt2agzzqqnk.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gt2cjttzlzc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gt2yifheqtl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gt2rojwawou.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ergragaz.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gt2jeovdate.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gt2mtfcxsvo.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gt2wbnnbedx.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gt2rwpwlcar.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gt2aoshyfsh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daria6918.cn/Article/details/gt2isgiyvft.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gt2pkjomtre.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gt2ikvfrakq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txqjcejo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daxiang520.top/Article/details/gt2todqbmag.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2mqvddcsk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2yeopybiy.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gt2aygfcija.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gt2qmynzsor.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gt2hdpblnzf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aibaodan.cn/Article/details/gt2nkphkvdc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gt2ytqmtuvf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gt2vpvnfuko.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gt2wotyrtsd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gt2famumgwq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gt2iugejjmr.html

[J09] 时区处理
来源：http://dali.aibaodan.cn/Article/details/gt2xeedheik.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gt2djtrtgdi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gt2gkwnicgo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gt2egyyqykz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otmirldj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnxiangtu.top/Article/details/gt2cjifijxr.html


<!-- 参考信息 -->