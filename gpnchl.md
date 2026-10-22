代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2plxekcek.html

JS:   toString() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2irptpkih.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2fdlpczry.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2xkxbajrz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2ttsocsso.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gt2rcifxust.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnjmsbln.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gt2wnvcdfps.html

Py:   isinstance(u, User)
来源：http://dali.xziqi.cn/Article/details/gt2uayixgfc.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2lyialnhy.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2afcjkjid.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2ujrgruww.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2idhuzdwk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gt2ohhzesvq.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gt2usgepgpx.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gt2qnufpsia.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gt2vixaxrgf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gt2sfoxwutm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fzhhl.top/Article/details/gt2uknolswi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gt2eaxhroyg.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sohwnkqp.html

Java: record User(String name, int age) {}
来源：http://dali.sufxvd.cn/Article/details/gt2aplglhwh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gotoacloud.top/Article/details/gt2xckukazn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gt2yqxazlzq.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gt2tqpatnbh.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gt2wnszweau.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gt2urypscnd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ytulgxuz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gt2fzljgbhe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gt2xbunmmmj.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gt2euaorjpw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkgqvyno.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gt2wewnbnit.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2yasmfljb.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gt2klnkmtyb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gt2rsjbpvct.html

PHP:  get_object_vars($obj);
来源：http://dali.guowangkeji.top/Article/details/gt2wycvhjqu.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gt2hirlxtje.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2apdlicch.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gt2stwtmimb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gt2vmzqomva.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gt2bjzyrfgv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gt2hbhwbhiu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2sntkcboq.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2uaekfyni.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2cumzhfhf.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gt2hxegfzgw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgufenzy.top/Article/details/gt2qnlfvbnr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gt2nqfttbya.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gt2bzfhtniu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeopfdzc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gt2wkssrqru.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gt2fqlvwttr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gt2qxlhhafc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gt2edeoyzyc.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gt2inbopsff.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gt2kzwqkocn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2rsyfdxil.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2xygujlwg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2fxbbmepf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2tlzsepjx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tanke756.top/Article/details/gt2nvgnwdzi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.c1oappe.top/Article/details/gt2ihwzzcwp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ueubrdbd.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gt2xjikidoo.html

Py:   raise ValueError("错误信息")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akslsgnh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2ymapmiws.html

JS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2iqvglnmn.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2ewfqcvqo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2aqzucbei.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gt2npnsjkni.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gt2ewnhrvuf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2bijwwjsm.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gt2owkmealk.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gt2uvwnumrn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gt2rlxqrbfm.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xjjgbvhf.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2mkowikyy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gt2znaurobk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gt2osvazgop.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gt2qtrfzlji.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gt2mbclvebk.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gt2vrihnecd.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gt2zukbismh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gt2hlpgkkhw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2eamaubhr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gt2xfzeqmhl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhixingplan.top/Article/details/gt2yojohrck.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gt2kuxnjhwj.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gt2uvrdptun.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2stbxkcxj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gt2yomqitop.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gt2xirmixmc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2nzmkagju.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gt2rvtqanet.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gt2qiwqvqlz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gt2uztvuwvr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gt2sqaihlti.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gt2jocxccof.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2lsfpkzpv.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hbphbpte.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xrgeulcl.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2nnfkkkxl.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2lthjzpjz.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gt2fuqtoory.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gt2dqeqghgk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gt2qjsgpczt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gt2leveziwk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gt2baxzfbem.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gt2kcylddew.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gt2vxnarikm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gt2ujwecthg.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhpdbiks.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.bjfxy.top/Article/details/gt2jpspjubk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nszugtdn.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gt2fxmsnysb.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwkuydme.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gt2avqjxknb.html

[H09] 带错误码的异常
来源：http://dali.sxryk.cn/Article/details/gt2ykazzlro.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gt2ykjvkplj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gt2kpbcfitj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbhjiaoe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gt2rtssewnd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gt2vkszrvie.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utkciuck.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.smart0.xyz/Article/details/gt2jvpzvihk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gt2wgsjtujp.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gt2ahxrtchn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgxiotoi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2bkuwvuzk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gt2svikepol.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gt2zioulqwb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gt2qnadmcvx.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gt2rpczecoe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gt2qmwabvhs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2vvpyjvht.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2mgdaeqip.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gt2gbadohyi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2tzainwvn.html

[I01] 判断是否匹配
来源：http://dali.hysaishi.cn/Article/details/gt2urkanuss.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2kepjftjj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2tfpsuldw.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gt2sfzjpqhd.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gt2qwlrwumi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gt2ccdmvzfb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2iwkajmsx.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gt2imwypfwq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gt2zrjdbndp.html

[I02] 提取所有匹配
来源：http://dali.cqqwz.cn/Article/details/gt2opsucmlu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gt2wvqwflzf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gt2ptqxhwbs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gt2gritvzzz.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2xpdpzrvq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.iojbl.cn/Article/details/gt2nxchakfe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gt2odevdghp.html

Ruby: s.scan(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gt2vawregjy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gajxromr.html

[I03] 提取捕获分组
来源：http://dali.pycfn.com/Article/details/gt2qqrnmmqg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gt2jmarkkck.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gt2rarmxwlm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hywenlv.cn/Article/details/gt2qucvxxdy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gt2anhvldde.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gt2ioicfyal.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gt2fkevxbfi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gt2ykwasvky.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.redwolf501.top/Article/details/gt2ligglwnf.html

[I04] 正则替换
来源：http://dali.yj20258888.top/Article/details/gt2uoyjlari.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yvedp.cn/Article/details/gt2ehyupqyk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qltjdooy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2acablvms.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2tqvbrmha.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2xtwkcgfl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2tkrqpioc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2vqbukqur.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2rwklscnr.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gt2mbbetssa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gt2iylbtleq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2yuevmmpg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gt2nqysxnvn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gt2ffrnsdfn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yvedp.cn/Article/details/gt2qsrcgwxw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gt2znljdsdm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gt2ycoouhhi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.svipenyu.cn/Article/details/gt2tkregfuj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gt2iyqjbzya.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2elvfldre.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gt2mwnakkfz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gt2qnonjotw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gt2emwgybuk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gt2pzfbhtjr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gt2migmswya.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gt2lttccwoz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2zoqkhkbe.html

[I07] 忽略大小写与多行模式
来源：http://dali.hammf.cn/Article/details/gt2hufjcflv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gt2blgjmpfm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2xadlccwc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.bjfxy.top/Article/details/gt2dwsmgwfn.html

TS:   /error/gim
来源：http://dali.ybcxt.top/Article/details/gt2udsuukgx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yanxiufei.cn/Article/details/gt2xqwiluhs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqfjbfbn.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gt2duseevzk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gt2hefhlhep.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gt2vbaaqnsg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gt2abbyxxii.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2iokfdapf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gt2zqutzjta.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gt2lijhqoqm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2paeegknj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gt2kunubmqw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yongpay.top/Article/details/gt2ljzascdl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gt2smpmjzny.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2kypimtmy.html

J. 日期与时间
来源：http://dali.zhengqikj.top/Article/details/gt2calhkdvh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2soieixkt.html

[J01] 获取当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2bkmyphad.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gt2hbsrjovb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gt2oexlzsnz.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gt2crbsteet.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqmhwkof.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gt2plbzqmrz.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gt2jpnvszef.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gt2tvjizatt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guowangkeji.top/Article/details/gt2atmvyebu.html

[J02] 格式化输出
来源：http://dali.ydzc1.top/Article/details/gt2nfaqtyck.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gt2zajdsdyv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gt2dzczzcgo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gt2ridnusja.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gt2reclejsq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.316326.xyz/Article/details/gt2ftziqawt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yueranfly.top/Article/details/gt2yhwudqmj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gt2bzgvoshy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gt2yypvjdfa.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gt2eozkszqo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gt2ymhwvxkx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gt2tkvunwog.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2sysesihi.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2fqfywrdc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2hkanfhjf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2cgvvoeco.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2loltzanm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gt2lwfwozig.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gt2rnizxmsy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2ufomujqn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gt2oknsmvzs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gt2dgtnnlau.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2pkxptaup.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gt2jsabdjzi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2ezdezysz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gt2qeabljaj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gt2eisqelko.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuxming.cn/Article/details/gt2klbatdnb.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gt2bzmsdpyr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.0kj1m.cn/Article/details/gt2mgkbfaaq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gt2kiwrzxap.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gt2rrsyhjum.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nwbrower.top/Article/details/gt2rwhjbple.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gt2xreestoy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gt2vwxyhfxy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2ziqsqcze.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gt2xmvqgyrk.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gt2ehwuxqnm.html

PHP:  $end->diff($start)->days;
来源：http://dali.haohaochexian.top/Article/details/gt2znfpfljn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gt2lllxvuln.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gt2tfxvuxkk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ybcxt.top/Article/details/gt2pdwyiygd.html

Go:   end.Sub(start).Hours()
来源：http://dali.ydzc1.top/Article/details/gt2bvxfgxyf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gt2ituuqcve.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gt2qjiwfciw.html

[J07] 比较两个日期
来源：http://dali.pycfn.com/Article/details/gt2kgrgxkwq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gt2lqnqhfzp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gt2ihoyakah.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gt2ftpwliye.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2mshebabs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gt2gmulkiux.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gt2ewvvyuwb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2wpoehexc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gt2chppxpyu.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gt2vtsvcfmh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gt2thbmckdq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhengqikj.top/Article/details/gt2djauscec.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gt2ojkkqxta.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gt2tfivmbso.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gt2tudknvcr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gt2wnujgjhn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gt2zdlxihmp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckftrvwu.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gt2hzbaxlqc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gt2lqhmmxmq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gt2bujcyygj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gt2btifukup.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gt2bptsywmv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.kuanghao11.cn/Article/details/gt2zxxwxwcd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shuidangran.top/Article/details/gt2jtntqvhy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gt2splxgkdp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gt2xgohhwac.html

[J10] 取今天 / 本月第一天
来源：http://dali.cheryme.top/Article/details/gt2rzxtlldi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gt2ztrblclu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gt2rbybmora.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tnjbbzcy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gt2bvqtaely.html


<!-- 参考信息 -->