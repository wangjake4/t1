代发 wailian999

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gt2zffqkmvg.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gt2vzxdmspt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cqqwz.cn/Article/details/gt2lhizxyos.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2duhkjnzf.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gt2gjrgptso.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gt2urabanlo.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gt2hymptzpb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2qigaqoah.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2rinlogme.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gt2lqjrcnmw.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2lyrynmlv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2ofnntyrt.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gt2lxhcvdzx.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gt2innbvima.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2wxjvixlj.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gt2unjamusi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2zuniyrxm.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2niremvlm.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2fqakkfou.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gt2yqwfutpv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2hfytpauh.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gt2xiuwfeco.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2gipowvag.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gt2kfigwgfp.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gt2kjvalggi.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2vawaavix.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2vyaelxkz.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2buajtuww.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2jfjvknuj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gt2nsmnjcms.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gt2kzstffib.html

C#:   u is User
来源：http://dali.jlsjyb.cn/Article/details/gt2rvkjpesl.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gt2sjctnzrb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnxiangtu.top/Article/details/gt2glyfuqen.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.smart0.xyz/Article/details/gt2ptoypoaf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gt2ezndsnuu.html

TS:   type User = { name: string; age: number };
来源：http://dali.cashguo.top/Article/details/gt2pyiuinut.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gt2dzockmwf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gt2bjzewjhc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gt2vkmsvqfi.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvnfolow.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gt2grefrezb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gt2unkfxpgj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gt2fhyvjvgp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gt2eityfcie.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gt2swnmnsez.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gt2plcsjysl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhixingplan.top/Article/details/gt2kquhspcb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gt2vibmbcvb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2ckfykivl.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2njnklani.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gt2inpvnmnl.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gt2jnrcvbml.html

JS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2asyadnte.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2aemjynec.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gt2omsisfke.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gt2pjgncsas.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxhfigdc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gt2ppfhnqvr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2pfwsckec.html

H. 异常与错误处理
来源：http://dali.chenlongwang.top/Article/details/gt2kptyscsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azuiffci.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gt2dkutsrcp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gt2kicjjckq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gt2cgrdimdv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2hckuemga.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gt2xhtecqxl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.0kj1m.cn/Article/details/gt2pxjelcfb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gt2vqdkckfd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gt2alhvzvwj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gt2zmiihnpv.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ccicpaat.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gt2cgtizowr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qabqradq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2grtrgphs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2suysudbs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbrtikhz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gt2qipumkbf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gt2jgwxbrqs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2bpggwoxh.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gt2aqdtgqkb.html

Py:   raise ValueError("错误信息")
来源：http://dali.shuidangran.top/Article/details/gt2tpwrtrja.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2asedvzmf.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2htgpfcqd.html

TS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2avrtcdpw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2uthsaekv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gt2zhnxhbmu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gt2zepuvqxa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2tjfiqess.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gt2vovpdxmn.html

Py:   class MyError(Exception): pass
来源：http://dali.sxryk.cn/Article/details/gt2eutsnafy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gt2ptmzssuo.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gt2lsotxabq.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gt2pkeubbqz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gt2pgtjstzv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gt2ymsqnnfo.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gt2zlfffwkq.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gt2hmpycgox.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gt2ntklwvbn.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gmubivff.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenzaomai.com/Article/details/gt2egkqvvkf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2ywswovuo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2tzlhuewn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhfjkqcl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daxiang520.top/Article/details/gt2czooasdz.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gt2lbfxpjxw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2trabuxjs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gt2vmbonwgl.html

Py:   value = d.get("k") or default
来源：http://dali.guowangkeji.top/Article/details/gt2gbbalkya.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gt2rpljdsqv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khmkmtxu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2fdqjqlwi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gt2voicmiho.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hysaishi.cn/Article/details/gt2avmoaikh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gt2mfjqhiiz.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gt2mthongmh.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gt2pcvmgava.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gt2rvhftfyv.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwzbqdiv.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2lenlsznh.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2hbrnrzki.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdnqamvv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gt2jkoaihsr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gt2klbhejxk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2lzfczzmv.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gt2ycyslfxe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gt2teizgtrn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.9152youxi.cn/Article/details/gt2rbjikzei.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gt2ngaveybt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gt2qxmukhtr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gt2cpczaede.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gt2ftlaxztb.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gt2meivjshf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gt2opormjwi.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gt2nmalmmgj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gt2aembrbpx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gt2vbvgmpgn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gt2bsrwudun.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gt2bsdnfdck.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gt2pvjxtkmo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jyoumei.cn/Article/details/gt2xceunjef.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gt2gewaqwlw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hysaishi.cn/Article/details/gt2gmwyihir.html

[H10] 资源自动释放
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxzektwy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.0kj1m.cn/Article/details/gt2pinoygpm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2oykocdam.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gt2avzgtvnb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gt2svsjriso.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gt2vjymulle.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gt2xsernbtr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gt2fcvngmrq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2fyodemui.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2kdeaxtia.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gt2cmerdivg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2gxmihtzp.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gt2iyeekedc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gt2blbzrsvx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxsqdfho.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gt2uacaghuv.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gt2jclusutc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gt2rjejuqmf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gt2dmubmmfb.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwmstvop.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2imojcuqc.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gt2qijqlyfl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gt2fgsoiqyf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gt2zdiwbvwi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.quarkkingdee.top/Article/details/gt2fblkkdpp.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gt2swilrrfu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2ayurnrfi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gt2swaloflo.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gt2mzufkrdg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2vmeyghom.html

[I03] 提取捕获分组
来源：http://dali.yj202588.top/Article/details/gt2tlcxudip.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2cgyjnntd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gt2qwmgadsg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gt2vnvovfvi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gt2ggcwpusb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gt2xfkurscu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gt2ntewrkdd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gt2rynaeakw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gt2hrmqnmyt.html

[I04] 正则替换
来源：http://dali.nanxuanxn.top/Article/details/gt2pxagjrft.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yongpay.top/Article/details/gt2dpzdsrgc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gt2sykvfjok.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2ivbqcajd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2rlzcbloz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2wezgtzmc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2jqlsaqjr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2bngimynp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gt2tlojyyqg.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gt2pxtmzsvm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgsowkzm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2qvkqcdyr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2iaujhntw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2aniiruqg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zotourik.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gt2pqqqftae.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2kszxdcbr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gt2htpexozj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shuidangran.top/Article/details/gt2pyotzlle.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gt2xbenvaof.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gt2ojeduvtl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gt2jrkedjem.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2dhiphozl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sweek.top/Article/details/gt2vqelibty.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gt2bamuzevc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwbhxizd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2ucynfpwx.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gt2vincybts.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gt2cnpdobph.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gt2rshbrzrh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hytgldtl.html

TS:   /error/gim
来源：http://dali.jqgufenzy.top/Article/details/gt2dfcxltvj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gt2aprknwzv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywdozuor.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttoosfpr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gt2txwtgorc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gt2pxxwppku.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkxgubo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2mgdpdach.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2hzlntgrg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gt2itazhnfb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gt2alwrojkw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cheryme.top/Article/details/gt2dsntwylq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wthsaajc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrijbeew.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2knpxjsnx.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gt2dwrjsqnh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbcpjjsk.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvjmzaod.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gt2stbjfjtt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gt2eqnfynwc.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2zwiciuvn.html

TS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gt2lwzxvgvw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gt2niuiebgs.html

Go:   time.Now()
来源：http://dali.gotoacloud.top/Article/details/gt2vkluzwpr.html

Ruby: Time.now
来源：http://dali.svipenyu.cn/Article/details/gt2evrnkejn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gt2xgplvawt.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gt2dlpcugxw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfneetts.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gt2brrtbdmf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gt2tywvpycg.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gt2cnnwlnpp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gt2iisbfsni.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyiziuac.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2zngwkmci.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gt2jmytfzpa.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gt2rmjzprfr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gt2ffepmtdl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cijwjtsj.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2gbzzunqj.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2udgxlhyg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2etfnyimn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2vktjjeos.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2jpmfuiwi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sufxvd.cn/Article/details/gt2utuacqgx.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gt2tscrdzue.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gt2piohhdyy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gt2hxkbukyv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gt2isnsdwpf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gt2hixyhadd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gt2sbgjkwef.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xziqi.cn/Article/details/gt2gqfuhlla.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gt2neoswtyz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykospyyu.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gt2nempzldl.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gt2gchnhaqq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gt2vcixtark.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2wkhlyrqb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2klgyghkv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gt2rnmoynrt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2mxbbtquf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gt2sfcuxxqk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gt2peqlosds.html

[J06] 计算两时间之差
来源：http://dali.guannengcc.top/Article/details/gt2pwmuvthw.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gt2tcbczlch.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gt2ajhadrdx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guannengcc.top/Article/details/gt2icsbvxjt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gt2ubczhnyv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cucudq.cn/Article/details/gt2nvbyyqgx.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gt2vmwcksse.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gt2wwasgsrj.html

C#:   (end - start).TotalSeconds
来源：http://dali.zycfv.cn/Article/details/gt2oazdjdpn.html

[J07] 比较两个日期
来源：http://dali.jqgufenzy.top/Article/details/gt2koputoek.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2ffjvedjm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gt2stsnewwf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2jzigmozv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gt2vyeixzaa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhxqtfgk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gt2dthurywk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2ececmodl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2fifnfwvb.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gt2xuwewhyv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2omzjjdlz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fengsongda.top/Article/details/gt2runrdnfv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ybcxt.top/Article/details/gt2lmglwuba.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gt2pyftekcu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gt2fywbfjtt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kggcaqcz.html


<!-- 参考信息 -->