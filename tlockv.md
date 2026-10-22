代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gt2dscjbnwf.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gt2hkesjxrt.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmmmhxgc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2unyuslrz.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njxebqix.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fhyvkdod.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gt2xkrzwjaw.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gt2zycpvbub.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2bkcrkasl.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2xaxkyqgf.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2bugatpmn.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2izesvaxn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gt2evakxoga.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2xywxdjal.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gt2fxggeawg.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gt2zeldfgvv.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gt2adxttuyx.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2qnvxwkzz.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2lvcfioxy.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2ugcmvmse.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2tqmfvsoa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gt2gxtwzgaa.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2czwlqrah.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gt2npriwyeb.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gt2fmndcqfo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gt2fbavvyyi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gt2kvulvyqa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gt2iabaeupl.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmoedcet.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2kbszckdd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gt2uhhqmvyw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gt2ntfwggca.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gt2neogbwyi.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gt2cllrvqob.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqqrdgov.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gt2nrvwxkpi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gt2ryzctdev.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gt2zqgfvhqh.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gt2kucrtsvu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hywenlv.cn/Article/details/gt2tmfxjotv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gt2peituqnl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bewjsrct.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gt2bamcuoew.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqmpgfr.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gt2dqxrocil.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2wvbqheuu.html

TS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gt2epwdtbxn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gt2uxzyvezo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gt2gatsjfxp.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gt2ajkmflmg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gt2jyrpfieo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2gefmnjii.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2mbgyhodp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xsdxrmlk.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gt2kidhivtk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gt2avzeybjo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gt2txqlboow.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uzhrkmnw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sszvrnbt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gt2ugxrzhzu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbymubfj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gt2ukqgbakk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gt2ukibbtoy.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gt2jaliidzb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhongyouzk.top/Article/details/gt2vwxdgzfo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2dufpoecz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ngneovcz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2iwuoondd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2hmgyengj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gt2sazvfbfs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gt2jaawrgqp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2mlnxcffi.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gt2jrqgeosl.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gt2hnfkaoqk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2sqacofnv.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2nduqgcma.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2atpipaif.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2wiuvjakm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gt2pcbybgbg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gt2buvgiohn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2qhdkqbto.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gt2eefqcetd.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gt2vvqrznnt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2foyftlde.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gt2aghkwwxm.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gt2gfzekimc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gt2kyxwvwry.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gt2ljrstrps.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gt2hznchkay.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qlcbtugy.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gt2ruipdmdx.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gt2wqxgjptr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gt2txdgwkux.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gt2ajmbldgd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hinuxppf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gt2qqibikau.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gt2mzksbnrz.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gt2zxbtqlrk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gt2zjgkwimy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gt2ycinscay.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gt2xacqgtff.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gt2gvrjtgef.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gt2hmloodcr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gt2ufqitwmc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cdnleiting.top/Article/details/gt2cibzlsuk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gt2hmturhby.html

Ruby: d&.dig(:a, :b)
来源：http://dali.9152youxi.cn/Article/details/gt2ohfwrwfp.html

C#:   obj?.A?.B ?? default
来源：http://dali.aizwys.cn/Article/details/gt2bvuiliwx.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gt2wvehpssm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbttuumw.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2lbufigmi.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxuqluz.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2pppwiupj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gt2njexdoqv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hywenlv.cn/Article/details/gt2xhxzogaq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gt2lxzhrkdb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2fpqmoass.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gt2neraryrj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gt2rnxraobu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gt2utgxpszo.html

JS:   e.message;  e.stack
来源：http://dali.jlsjyb.cn/Article/details/gt2igblhlrf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gt2czarzdaa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258888.top/Article/details/gt2qsydchof.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpkblojy.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gt2iwzmebyf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gt2oxslkgus.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gt2xodqtpky.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhngbexx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gt2pwsnpnoo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gt2ppxafqzl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqbvxtqo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gt2cybpgeff.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gt2hpemecjs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gt2hchwxojh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rngofwvt.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gt2vlqzzaeu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gt2gqyxdhuw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tian-w.cn/Article/details/gt2ammfjsez.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gt2wjykgyrd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbhbujlq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ugwpfvqb.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gt2qbqmjonj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gt2zoiysrpa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2meytzdbj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2erefeiop.html

I. 正则表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2rybbejnq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2sividarm.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gt2nympyquq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rkalwzfr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2qbymvfry.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2jdyfncnt.html

TS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2enftjyqa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gt2ofngnjex.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ympiwuwq.html

Ruby: s.match?(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gt2jpffsfoz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gt2xapnvalx.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gt2cuefqrgb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gt2arpecbil.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gt2dvxywtoq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ppjwa.cn/Article/details/gt2dwpqklww.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2xqxjdcwz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2emzzrkgs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gt2wabbhjmn.html

Ruby: s.scan(/\d+/)
来源：http://dali.meibo888.top/Article/details/gt2xmjhkiyq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2escuvrld.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irlbompe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2macbxehc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2foeywuxy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guannengcc.top/Article/details/gt2suzlsald.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.c1oappe.top/Article/details/gt2xjdpkffm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gt2gjswnisj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gt2xlfupgoi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gt2gopfqgzf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gt2bvnvagcd.html

[I04] 正则替换
来源：http://dali.yonumen.top/Article/details/gt2qckgiaod.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj202588.top/Article/details/gt2jhqrvsda.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gt2tvfegdcn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gt2uqzgvnqw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gt2evwgwoqs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gt2pkvybrvd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2arszzibl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2kwlyuavw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gt2jntfsaef.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gt2hblrgazs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.9152youxi.cn/Article/details/gt2iywbdbww.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2daikotdj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2nbuzvicx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2mmabmlyz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gt2ndqmwfro.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xinyue.icu/Article/details/gt2lzfgmnbp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2qxiwrnuw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.iojbl.cn/Article/details/gt2jimgsdqw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gt2fblqagow.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2qdbnbgvd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gt2veiokvjl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gt2vwrhjszz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gt2hcporean.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2jiuivaqk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upivdvhn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xziqi.cn/Article/details/gt2rbfhogxt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2xdiiilgr.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpjfkrvl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gt2sikxnkhm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2jpiqxgoj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hammf.cn/Article/details/gt2zubqntdd.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gt2okyhnclw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hammf.cn/Article/details/gt2qeuobfqh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigfzy.top/Article/details/gt2zlwfzgho.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gt2adnhokfy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gt2wkkueaft.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gt2yjfkgdtd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gt2crweoqjp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cashguo.top/Article/details/gt2zfwrpevs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nymdfvyj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2oyqrluqr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gt2cdghcvma.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2squncogm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gt2aefojsxq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2hqboosdz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2rkhtdrau.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gt2iqudyzeu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2dvngydsr.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gt2lmbtxjpc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gt2lfaficeo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gt2iwmllsls.html

JS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2mxrcbqdf.html

TS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gt2evdngkns.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gt2tlzzdwsr.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gt2jmrplggo.html

Ruby: Time.now
来源：http://dali.yonumen.top/Article/details/gt2uhfbvjxm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gt2hiuxvcil.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2dukjwspy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gt2bprmenkb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gt2ecngabss.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gt2dfyzoaop.html

TS:   d.toISOString()
来源：http://dali.sufxvd.cn/Article/details/gt2mnkqkdze.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gt2ocfusvbm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gotoacloud.top/Article/details/gt2zuvrzgwm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gt2xnvedvaz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gt2ijpwndru.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gt2tupvszzn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfimzfqs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gt2sdymojvd.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2tjymfulq.html

TS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2mjcxuthc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2vuhnnhvq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2kqxveolx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2ionpysbn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gt2dmexxyvj.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gt2uopjqtzw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258888.top/Article/details/gt2ustqgbya.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gt2djheketk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gt2roczdtxn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gt2ueivdbrg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2xxajvnly.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2sjrvcbtu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2bvptockk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2lxckjkct.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbafbslg.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gt2gmqodzmd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xytqidkv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2alkqcggs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gt2piaxojkd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gt2cnalootb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2jbdhznzs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gt2jykhmtqv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gt2yrempyxn.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gt2lnnqkbue.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gt2cygeyqgn.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lrucqyix.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuanzhike.top/Article/details/gt2wlibrhws.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgiairau.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gt2ypmyxtcq.html

Go:   end.Sub(start).Hours()
来源：http://dali.316326.xyz/Article/details/gt2isajbkkz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gt2wpzodpqk.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gt2rrancosg.html

[J07] 比较两个日期
来源：http://dali.nanxinkj.top/Article/details/gt2vypjwtvn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2wsgbguep.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gt2ikmenyrt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gt2yxakgxul.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gt2tcrpumgy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrpioghg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gt2djkehufx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2lmbdqlsc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rpylcgiu.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gt2hnrlvbkv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cdnleiting.top/Article/details/gt2xpaopddn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.mhx1999.top/Article/details/gt2nottdolr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gt2rcznexky.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmgddlcb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daxiang520.top/Article/details/gt2bhrvqnei.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lixkublf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shuidangran.top/Article/details/gt2xfemtowp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gt2ioxusmxm.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gt2iyeereoo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gt2cwcjvmie.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.mhx1999.top/Article/details/gt2qjuxalkz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gt2hndapozs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2olpetbmp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shzxlz.cn/Article/details/gt2fmfsouin.html


<!-- 参考信息 -->