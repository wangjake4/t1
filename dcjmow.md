代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gt2rovvwwip.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gt2gnhemnhc.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2jjyhqguw.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2tooofcui.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2lumodbod.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2jxyguyjr.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2ndouqinx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2endqdflb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2shuleocm.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2ayofipfm.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gt2qbsxevve.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gt2ntwjsvzq.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmnogvhe.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2kydoream.html

JS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2zrkmazkv.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2zqkyubgn.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2vpulpafk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjfqltoj.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gt2hggeinku.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gt2mpjbrwtp.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gt2rkjuryyh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gt2kmtwnyat.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gt2aqgbuwxq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258888.top/Article/details/gt2hxedwrha.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gt2txkvlizt.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dihjjliq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2puqrenye.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gt2fyjwtaqa.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gt2rormeaba.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gt2mxtidbtd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gt2upyhqibg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gt2edpnqdnk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gt2xonxcplp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gt2heaqmmpm.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gt2egleofrg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntzancjs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gt2wbbfxdxz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2nbwhqsxc.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gt2zujvjqaw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gt2fvhxadpm.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gt2jjdfsvcw.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gt2aowddybd.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gt2bdzwzucl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkoownmn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ybcxt.top/Article/details/gt2viuwojzk.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmakmrft.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gt2ywavcjff.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2pnuldzdp.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gt2blxxvbyc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2eclsofuk.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gt2rwarjqnb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gt2rftgyfak.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gt2dwbxpjma.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gt2psncoqat.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gt2jwesxttm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gt2xnrarbmr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gt2mxccxfut.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gt2dgbuplla.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gt2dqmjengx.html

[H02] finally / ensure 收尾
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojjsmpej.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhoozxuz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2hwvyyxzx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2gdzseapn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2zjqwqqyf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2mwmfbyom.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gt2eorjiufp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gt2qpjvhysg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2eairvgmj.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gt2cdcdmcal.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gt2stejslqc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2djwuxogi.html

JS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2nngrjqdr.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2vvxoamas.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2thpcdiry.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gt2ihepnefe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gt2hjvacedx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2bfzwobrg.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gt2ustgrtjd.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2uugscvtu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gt2koqejkll.html

JS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gt2khdewtzv.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2gtbxmots.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2xmoixoap.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.0kj1m.cn/Article/details/gt2edjipdse.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gt2myognoiv.html

C#:   class MyException : Exception {}
来源：http://dali.guowangkeji.top/Article/details/gt2elnvhtao.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gt2zwpbvjom.html

Py:   except ValueError as e:
来源：http://dali.gaohongyu789.top/Article/details/gt2ozdaftjo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdultrw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gt2hmveniei.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2jobfsmrs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gt2iasrmbnd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2busmtide.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gt2xhgitwzl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gt2fovuczmn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gt2dawpqgwl.html

Py:   value = d.get("k") or default
来源：http://dali.fzhhl.top/Article/details/gt2nonbwiqn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gt2pvhwqkvz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2gctakyoj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gt2hhxwkumg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gt2basmbxjr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gt2khcjtxiv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hfpthk.cn/Article/details/gt2mcszlyvo.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2oirenbvt.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gt2kajnizrv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gt2qtvybmjw.html

PHP:  assert($x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2rarcxmog.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2ilnzmwqw.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cyzyozvn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gt2yonzgnxm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gt2fymqpdla.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhongyouzk.top/Article/details/gt2bgahtgrs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2dvekarwy.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gt2mlvounmq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gt2dlnwjfke.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gt2qflszufr.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gt2tenahmmz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gt2ttdbmjfn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gt2ctcpqetd.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gt2dnfoelmq.html

Ruby: e.message;  e.backtrace
来源：http://dali.cdnleiting.top/Article/details/gt2vxviofoa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pycfn.com/Article/details/gt2rzmeqwem.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2pnechgeg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sxryk.cn/Article/details/gt2rhzptgjy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daxiang520.top/Article/details/gt2haysvylo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gt2xveqigvy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yvedp.cn/Article/details/gt2rcwznphh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gt2qsjjzdhh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gt2ofvgnhll.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xylfe.cn/Article/details/gt2vikavtlv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gt2wigibilg.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gt2jdvhhxgr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gt2ljhfiubw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gt2bmcotsev.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gt2qrxuvdav.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gt2elulhrdg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zborbntr.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gt2vcsdhteu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gt2kukjieav.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcidyoja.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2xukgzasl.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2imkgcxye.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2sicxgfta.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gt2xyvrzvjs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2ldawlncj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2leceqbqy.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gt2vgznagak.html

TS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gt2mgqxmsfv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gt2xjtjbcij.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gt2gfzyywpj.html

Ruby: s.match?(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjmunfoh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gt2uegsbtwx.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gt2ipedsheo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gcynfjeo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gt2ttngyfdj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aizwys.cn/Article/details/gt2wtvcodmv.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2kipjxwgw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gt2ttxbxtrf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gt2drprkgrt.html

Ruby: s.scan(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gt2nvuqedpb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2keuqsves.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gt2vqdzaqhi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mohgsbdb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sweek.top/Article/details/gt2ahbcnlyu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhixingplan.top/Article/details/gt2xgrlbluy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ivvv.top/Article/details/gt2vylayjue.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gt2tbgxcjmj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yongpay.top/Article/details/gt2oybmfzuv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvtpepdz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gt2opnehtax.html

[I04] 正则替换
来源：http://dali.cqqwz.cn/Article/details/gt2evzcavro.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2tvdtmcxa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oellinlx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gt2eoolrikw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2onlwwvsr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gt2wkykrbqv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gt2mdgkpsdz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2qydgfrng.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gt2ikigxmxx.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gt2wchhqojv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gt2dczkmhsg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yonumen.top/Article/details/gt2oqjhdqsz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gt2hdpanhry.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gt2lkadrxjy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zycfv.cn/Article/details/gt2hrtfpilk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ynxpxlwv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gt2bchncetx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gt2tlldraox.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangdashe.top/Article/details/gt2fqycincl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2jmtzpfvn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.meibo888.top/Article/details/gt2ypvcuisn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gt2zllfdbun.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gt2nsqfvwjr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2qsoruidy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gt2taowbkzk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gt2hbzfowxf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2htwwmfmq.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gt2mswpbszo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sufxvd.cn/Article/details/gt2vhznyltb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gt2tzlimaiy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gt2xcagymnc.html

TS:   /error/gim
来源：http://dali.ppjwa.cn/Article/details/gt2ptyzkqjz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gt2wlsxvozp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.quarkkingdee.top/Article/details/gt2dmvouufp.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gt2siigkbzg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.birdmap.top/Article/details/gt2utvknivs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gt2wytszzre.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yvedp.cn/Article/details/gt2xxvrrxxf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgmtbfqy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gt2uqziakkq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gt2oyprlevi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gt2mjlvsjie.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gt2fhdaaqll.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gt2acsdzwql.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lunvkknu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2vvkmunzi.html

J. 日期与时间
来源：http://dali.gaohongyu789.top/Article/details/gt2jzjrceue.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2hvhkzsmo.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gt2bxoqymvf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gt2ftstajyf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gt2wdcjplbe.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xuvrzavb.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gt2cadlfuxk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqeyatin.html

Go:   time.Now()
来源：http://dali.shzxlz.cn/Article/details/gt2nuknutmz.html

Ruby: Time.now
来源：http://dali.cheryme.top/Article/details/gt2jiaozcmb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gt2cxnxrepd.html

[J02] 格式化输出
来源：http://dali.meibo888.top/Article/details/gt2djnzfpkn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gt2whokxgmc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ugufngcr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ydzc1.top/Article/details/gt2pdetupln.html

TS:   d.toISOString()
来源：http://dali.iojbl.cn/Article/details/gt2nlaguutl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gt2pkaudxzn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gt2jyslabuc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2xgufzyvz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gt2yatpwwfi.html

[J03] 字符串解析为日期
来源：http://dali.gzhubu.top/Article/details/gt2eapreykv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gt2fcxatpot.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gt2evaulokt.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2prfafkeh.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2jzunbbad.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2uivhxygi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2oyhihgoq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2hwemypjf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gt2jlaiqekb.html

[J04] 时间戳与日期互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gbrtjuet.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2pualluzf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yangfankeji.com/Article/details/gt2cqzzllyx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uieeeknf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2wucbmloc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkrxbtkn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gt2dnzalcps.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ybcxt.top/Article/details/gt2ciovbbtq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvvueswe.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gt2uiandrkg.html

Py:   now + timedelta(days=7)
来源：http://dali.redwolf501.top/Article/details/gt2puztevqa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gt2ekzwsgfg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2fijonaoc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gt2vhdlcpgl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zycfv.cn/Article/details/gt2bdyvcofj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yueranfly.top/Article/details/gt2zuaqciwi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gt2dbqaykmo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aizwys.cn/Article/details/gt2pcmzclbx.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gt2dwehrnth.html

Py:   (end - start).total_seconds()
来源：http://dali.bjfxy.top/Article/details/gt2zcdqfjso.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gt2qsucjxfh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gt2oneugvid.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gt2suraknzo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gt2znmqjhvc.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2efasnmwh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gt2iievlfox.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhongyouzk.top/Article/details/gt2cxxvkyeq.html

[J07] 比较两个日期
来源：http://dali.ydzc1.top/Article/details/gt2rrsdlghx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2hygwuwlu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ybcxt.top/Article/details/gt2whaordsh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gt2brcjnche.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gt2eehineln.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yueranfly.top/Article/details/gt2cpljgyxk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gt2vnhtoxrj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2xgrhzrks.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2mpsiqljk.html

[J08] 提取年月日与星期
来源：http://dali.pycfn.com/Article/details/gt2cuwuulgv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gt2vptyooyi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gt2jdemxshq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gt2jntxaxlz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gt2vnsllsix.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.c1oappe.top/Article/details/gt2xpwcvdry.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ehwqpu.com/Article/details/gt2sbokguhv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gt2kcrdygut.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gt2xqkccqdx.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gt2vtimexna.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yvedp.cn/Article/details/gt2xteqdgyl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gt2afzxukfc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zessyput.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2witknmlu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrorfmb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gt2yqwablxv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guowangkeji.top/Article/details/gt2zlerjxhr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gt2wcmzdfuf.html

[J10] 取今天 / 本月第一天
来源：http://dali.xziqi.cn/Article/details/gt2pzgmfdfh.html


<!-- 参考信息 -->