代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gt2arqqpmll.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gt2qljgvijw.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2bxoggune.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2ounmlobe.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gt2ybfifzxe.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gt2llrtxrfk.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gt2pdtbybbe.html

Py:   def __str__(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2yqaigtng.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gt2nrfmoimm.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wapzttmu.html

TS:   toString(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2rgxilmtp.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2qgnnvsgs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2hubbvvmw.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gt2hvhjlbgu.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gt2xxdrejdw.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhmnbewz.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gt2hzhifkyw.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2xzchafkv.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2bkdprlho.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2gqbccrwz.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2dylzsrkt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gt2eucsvnrk.html

Ruby: u.is_a?(User)
来源：http://dali.sxryk.cn/Article/details/gt2hyogpaya.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gt2axfdfpuw.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gt2bxkkoiqx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gt2evbrzyth.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gt2ouserrzv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gt2qzzggoeo.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gt2qcslyjva.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lypwpbqu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gt2qxyeleqs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gt2qjupzxsb.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gt2zwarvykz.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gt2pogchnch.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gt2xphtkwrm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxktyull.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gt2loveeeoo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gt2xvlrxcfq.html

Java: enum Color { RED, GREEN }
来源：http://dali.tanke756.top/Article/details/gt2cxmjeggs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gt2gaweawow.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jiagoushi.top/Article/details/gt2ppqvxenj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gt2ckjcclcn.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gt2fxowehfm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnghcrev.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gt2eqkjhwan.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2yuborlcj.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2lsjbfzou.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gt2mbgqtjbw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2nexfexkd.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gt2iaiwutls.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2rfelxyad.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2xwfsseud.html

H. 异常与错误处理
来源：http://dali.zhoulong.xyz/Article/details/gt2xcmcbnau.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2fiiwzsia.html

[H01] try / catch 基础
来源：http://dali.jiagoushi.top/Article/details/gt2qnillklc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gt2fdjztgay.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gt2hlzhkfud.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwvvakzv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdeabxqb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.redwolf501.top/Article/details/gt2efmobyxx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gt2oibecmts.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gt2kmvgsghh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gt2nyhczvdn.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gt2ditpvdpl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gt2vhnajjuq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2asuxrtke.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2icmzztcc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2hvwaqvwo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2jrjtalqf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gt2rckrqkbh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gt2kgxukrld.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2rhwqjutc.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gt2essuecxd.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gt2awlkgsuo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2kbpbunig.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjfwlyya.html

TS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2cebqeprq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2boonpgvz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gt2xrfsgecr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gt2dsqirpkr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2xckaifis.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gt2ovcwjkqy.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gt2pvhjazsk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gt2tbuxyurw.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gt2kzuwbztq.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gt2mnpffxld.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gt2dzdyywqa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gt2mbamppjg.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gt2camwjycv.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gt2izppxvyq.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gt2vgyrrrpe.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gt2dcgnjazc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gt2fphfaitq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kitlrqro.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gt2rfjkrlez.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gt2fqpsfhzw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gt2wpkoxpuw.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gt2knkaivnq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jianghu66.top/Article/details/gt2mnabjzop.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gt2hsufrdld.html

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndnunnam.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gt2xnqhxzwr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gt2euzfuler.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gt2pcujjzbe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2varpfucf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gt2scvgfjai.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jiagoushi.top/Article/details/gt2xrtbnsov.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangdashe.top/Article/details/gt2bymykeqb.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gt2oxuwrmcy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gt2mclfaytt.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gt2efnvbwan.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2kxfwzxpd.html

TS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2errlvzqa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xinyue.icu/Article/details/gt2lwlnobgm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dcraqucs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gt2sxhsgvlo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2dxcgqagh.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gt2cnebihid.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gt2rsyfjzey.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gt2hsiwfcwj.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gt2nxbbpixb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bsqobswm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.c1oappe.top/Article/details/gt2uyzekfma.html

Go:   err.Error()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jwfdythi.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gt2chojfwzj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gt2kvulrykp.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gt2xlhwnbxe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqiiqmbo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gt2sjkwmjkd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iinevpnc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gt2genqvcop.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2izscqanv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.iojbl.cn/Article/details/gt2cikwccsj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gt2nhgocbez.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uwakhpea.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gt2isdjucyb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gt2twrmrjpg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gt2gcdezpej.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gt2ikmlyncz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmrmmyqu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gt2uklkngqn.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gt2fzqfejur.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gt2cdusvkpt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czdgrqqk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2npstfgxp.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gt2lhephaos.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2fsveppgs.html

[I01] 判断是否匹配
来源：http://dali.aibaodan.cn/Article/details/gt2ghzkyaum.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gt2qzdndrby.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2cledmcfj.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gt2uevmfctw.html

TS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gt2ktywguxa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gt2tpdgulja.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gt2ajrckveu.html

Ruby: s.match?(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gt2oubseerk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gt2oacwlqgu.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gt2rhsqsabp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2chwcerat.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njdopkcp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hysaishi.cn/Article/details/gt2bryfkisc.html

TS:   s.match(/\d+/g)
来源：http://dali.redwolf501.top/Article/details/gt2iiveqsai.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gt2dechpnuf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gt2idktwkgb.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gt2oycgfkbb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2ongzssrq.html

[I03] 提取捕获分组
来源：http://dali.cheryme.top/Article/details/gt2delwvogl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gogol.net.cn/Article/details/gt2yaeukaxs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.birdmap.top/Article/details/gt2qvvjgrbf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2enhbtyzc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gt2sxntmjna.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gt2mjdsrmom.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gt2ltknfkot.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzxfygot.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gt2zhevmzhi.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tegdtbxi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gt2kctqnfza.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2onshgvsn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2fmweyiqy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2bnwevxjt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gt2embonhmj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2lpxsndmx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2dgvkigox.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gt2rcvrrbva.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gt2plngacct.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jyoumei.cn/Article/details/gt2qvnqbcri.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrtxhvvk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2upypbpmm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2gqccsnzz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gt2dazjdvco.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gt2mehmcpul.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2gbzwcsvc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gzhubu.top/Article/details/gt2dwitsoto.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdbdgaop.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gt2eecciash.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gt2rxsbzntx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gt2ilsxtjec.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gt2lozjjdlb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2hvujmone.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gt2grhwgoiv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gt2gtrcguaq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlbafzwz.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2iimodwsn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gt2oewsvpwk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gt2gzojmmaq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gt2vgciogdy.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gt2vvofztbf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gt2vbwgaexq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hysaishi.cn/Article/details/gt2ylidpiqk.html

Ruby: s.scan(/error/i)
来源：http://dali.ydzc1.top/Article/details/gt2rdvlkvvt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tianlin.xyz/Article/details/gt2ganmoqdv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gt2yalyektq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gt2fagtltnj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gt2siskujuo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2humylpkv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gt2ifbezhec.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gt2dzokgkxf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gt2wibwkvzo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gaohongyu789.top/Article/details/gt2jwbdljpp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytufhtcr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2vnombzeo.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gt2cfmjexhv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2wyqtmzmi.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gt2rdknzths.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gt2lfajuczr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gt2ghyffjma.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2ziamzfqi.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gt2lqyqaswu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gt2vsxshljv.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmptqwnq.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gt2svubkmlv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shuidangran.top/Article/details/gt2ivjjidut.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gt2voztidbd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gt2zvjputsq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gt2suhwdofr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gt2qjoodpwi.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gt2ndsbybsi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wftijwzt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gt2lnumfsql.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gt2gzkzayrk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xylfe.cn/Article/details/gt2krdhvvxa.html

[J03] 字符串解析为日期
来源：http://dali.havefunace.top/Article/details/gt2hzndcjqd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gt2zlrncbog.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gt2migtuxce.html

JS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2svisnbgg.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vuyvnlrc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2fczsgkdx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vuqenqey.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2spnabcos.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gt2roilevko.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gt2kwtqtvhl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gt2emhpvaeb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gt2jzkbnpfm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gt2cuyttysg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iynpigow.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gt2oesdvpsm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2bjbwtpqe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2sdddtnxu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gt2yoqikazn.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gt2llubsosq.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gt2wpbeojhz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tbzbdrjh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gt2fmovolzt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gt2wlepstvq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gt2iimepgji.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uptngxvl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gxovpxqi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ydzc1.top/Article/details/gt2mrrtyxcm.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhpeumpv.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmlqxiwi.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gt2yzuoldbu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guannengcc.top/Article/details/gt2rizvyvft.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2felysuxx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gt2tptrcbld.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gt2wqrbrkkt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gt2agtumqit.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gt2cnnzprzx.html

[J07] 比较两个日期
来源：http://dali.hammf.cn/Article/details/gt2vdvpwgzm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2zwbzxojx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gt2pbxqmqyw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gt2yuhnkzms.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gt2wxluylkz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigfzy.top/Article/details/gt2qjtuebsr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dianchejie.cn/Article/details/gt2pdmelnxl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gt2iwprqjor.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2eximdmpd.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gt2bgzogach.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhcngxfq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxbztgar.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gt2dnzvigly.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gt2qqzpbxvj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gt2wkuosrud.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gt2lqrypmhq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gt2bhqfbpdu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhoulong.xyz/Article/details/gt2fuwzpwnp.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gt2lolouhfb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gt2xonxqbxc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gt2tleemwwl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gt2qwvlosly.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gt2vlctpajn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gt2lhqzxjwm.html


<!-- 参考信息 -->