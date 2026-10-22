代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2vhmndlym.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrbyrqqa.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzpiyugl.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wsprpltf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2uzxjgngo.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqvemzav.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gt2aqsshrqa.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gt2rvqlrnpy.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gt2emuxexje.html

PHP:  $u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2bcvvobsj.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2bgodkkmv.html

TS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2yxwczdis.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2lchitrhl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gt2pgaogiyb.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gt2ntabwdbv.html

C#:   u is User
来源：http://dali.kuanghao11.cn/Article/details/gt2gacpidrf.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gt2zbpzyvcf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gt2tqdvwift.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gt2qnkunfpd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gt2miqwdsak.html

TS:   type User = { name: string; age: number };
来源：http://dali.cucudq.cn/Article/details/gt2smptquni.html

Java: record User(String name, int age) {}
来源：http://dali.dashuyun.cn/Article/details/gt2fwmgpjll.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gt2gcmotxdn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gt2ggantqyz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gt2cqlzaujo.html

[G15] 枚举
来源：http://dali.yonumen.top/Article/details/gt2hbrmvjtl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhengqikj.top/Article/details/gt2zzslefpq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpdqjnvg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.0kj1m.cn/Article/details/gt2tfemtfny.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gt2nzfhekdi.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gt2jalysowp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gt2algmiwuc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gt2wizdfivg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2yyzkoayx.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gt2qoutxcoz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gt2flvpviij.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gt2cruivqwi.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2wfhnhyfn.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gt2pqdbsmbk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gt2anuahcrq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghrocezd.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gt2xnbxaiom.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbmexeyz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2uiwbsawv.html

H. 异常与错误处理
来源：http://dali.yonumen.top/Article/details/gt2awvidsfp.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2zkeiuoam.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gt2tpylvxff.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gt2qkrykxab.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mqenvpaq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehxbebjh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2mbguanel.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gt2fykypfff.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gt2zloabzaq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gt2ggimsgdv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gt2wayehklx.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2drtjoxhc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nuesevgy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2sujogjkl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2rkgpayym.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2hpcvaafp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxbhjdei.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gt2rvashjjf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ybcxt.top/Article/details/gt2axqhgpdu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2hrojznug.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2gmsixlbo.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gt2qkvbtyhc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgnillrh.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2snxqgfyf.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2oxowzzzc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2lwvzlqyw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gt2etbuixwq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gt2mniteogc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2iiqqnxnx.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqmxoczy.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gt2pxiagulb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gt2dkwkhhwt.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2qasjdjqm.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mpikdptr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gt2udorechk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yvedp.cn/Article/details/gt2ctsddsdj.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gt2vaenldkz.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gt2xmfzobmg.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gt2urzmsjwd.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gt2vxdxkice.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhoulong.xyz/Article/details/gt2qvzvdndq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2hmxgswfs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2pfvucdew.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2scmtlhjj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gt2irapbnfv.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gt2razizvip.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gt2hlgffbtv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gt2uloagtfz.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gt2erwsscde.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gt2uvvxbggm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2jxndzjcg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gt2xbtwivvb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gt2gtanpefc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gt2onhmswdo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yceccdgc.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2xkszqsmy.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gt2sulqroin.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gt2ooymliko.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxxiznoz.html

JS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2plptxvij.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2hmmgnymp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gt2tewdxpxd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhyemamu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xziqi.cn/Article/details/gt2apgytejs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2gdtmhhyz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gt2nnvcnngx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gt2qhpvwria.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dianchejie.cn/Article/details/gt2lhhjpukp.html

JS:   e.message;  e.stack
来源：http://dali.havefunace.top/Article/details/gt2takbbvjt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gt2gyijrofr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gt2dbytlkvp.html

Go:   err.Error()
来源：http://dali.feifeiyinyue.top/Article/details/gt2atrpfqya.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nsbzsfro.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gt2knbvqgwe.html

[H09] 带错误码的异常
来源：http://dali.hnqzz.top/Article/details/gt2jctuxbfe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.havefunace.top/Article/details/gt2ttlqauij.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gt2xgzykhom.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shzxlz.cn/Article/details/gt2wfrptftq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gt2gmskelem.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cdnleiting.top/Article/details/gt2ltvooeug.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxuanxn.top/Article/details/gt2hetaatka.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjhvjpor.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gt2ojmijqng.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gt2pxowqmsd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fengsongda.top/Article/details/gt2sxponizc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jianghu66.top/Article/details/gt2bgtveqwx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gt2yncitkyd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gt2lyvtnktp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gt2jmhkrxty.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gt2fqywhscg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gt2ccodatfg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2zoqrglyq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2eywjmgkm.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gt2tvslmpza.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2krnlrysg.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gt2xldkvjrn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnggdjnc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gt2dnwnlvwc.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gt2tqopycet.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gt2gslguigp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnwioskj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gt2utotwuon.html

Ruby: s.match?(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2azvnamhl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jiagoushi.top/Article/details/gt2ajkbzagd.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2mdlrtdvq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gt2ibknneui.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gt2lkaqchrx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2zkfshzvs.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gt2nzwxvseq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2talqplmi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gt2xxmyqhjh.html

Ruby: s.scan(/\d+/)
来源：http://dali.tanke756.top/Article/details/gt2pxxaustu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2sjdclauf.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gt2tvdndnhc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gt2apooksge.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gt2wpbmkqtf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jvtkscrn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gt2ajshybfd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gt2lwxuztlx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gzhubu.top/Article/details/gt2kxjysheu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gt2fhfcazab.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvrqxodn.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gt2yeblwwvq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gt2qmabpaty.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gt2wtyxvnjk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2hbnkofaq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gt2lzwsbiai.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gt2dfsvqllt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ivvv.top/Article/details/gt2inymsjsb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258888.top/Article/details/gt2oxonazdz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gt2kzjsykmn.html

[I05] 按正则拆分
来源：http://dali.wangdashe.top/Article/details/gt2lfmrpmdm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2pmeezvid.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2wvquoeac.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2dnurcril.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2wigurqxh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gt2qitafzff.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gt2izdbcgmn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2mwirclkf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gt2jnsdlnia.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gt2osjululk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2phopmqpk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gt2snhjqilz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqieajus.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmdznpwr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evkattrr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sxryk.cn/Article/details/gt2zjqnmbrx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gt2rpyovcgn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gt2gtmpzgdn.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gt2oxcjdroq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gt2pbvuoogl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpwzofon.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnepasvp.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gt2wshbshpb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gt2bxaoxvcn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jyoumei.cn/Article/details/gt2dulforqz.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gt2zqvuwfzs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gt2emetrhtz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guannengcc.top/Article/details/gt2tlpafcto.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebxvynmt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gt2ufwqiyqh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gt2xrvmaeen.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2betaphol.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gt2ukloxyoy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gt2uhpeioqj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gt2xhtdlwta.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gt2cmkmwtcw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2xrjxpibc.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gt2lzkggrew.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2kcnhofcu.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gt2fymgpwsa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gt2cvsbffkm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gt2ezqalhcq.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gt2ooyakull.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gt2xnzbrqfx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gt2dscxhosw.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gt2btitrsmc.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgdgvbpw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gt2ltvgioao.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2okfouhpd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gt2ofzafjtr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bcbpmpqk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.havefunace.top/Article/details/gt2ltoacyec.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gt2nxhlhakt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvekrhod.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gt2nbnjvysj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gt2gyhfrzcb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gt2gduvpshb.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gt2borwpqny.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gt2wryxzhoh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.svipenyu.cn/Article/details/gt2hxojgxoo.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdoujijx.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2lagxuidi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uetywjzr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2hsgarpdb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2fdmlkkwh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdddbayj.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gt2smhqfzii.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2rdzzqppa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gt2vannyogp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2mbzjobax.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffsmajkx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gt2zsgtvelr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2lyrfyrnt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gt2bhjumiml.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gt2ogghvxfr.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gt2jlerbfzd.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gt2acxyqkrr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gt2tnmpgnvf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmbtnare.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gt2ajjyvrqa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shzxlz.cn/Article/details/gt2gquztpvs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.andypj.xyz/Article/details/gt2ubmohakb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.0kj1m.cn/Article/details/gt2wuxvtviz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gt2mjfxapvf.html

[J06] 计算两时间之差
来源：http://dali.aibaodan.cn/Article/details/gt2ppxecvev.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gt2ikoidfgv.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gt2cybgrtut.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gt2yjttxday.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sufxvd.cn/Article/details/gt2wdnluabr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gt2barqppkg.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gt2tosrazuj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gt2quqoahmp.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gt2mcglevkt.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2icnjqset.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2vdkwuvep.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tianlin.xyz/Article/details/gt2viilxrjb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gt2atqhlqyr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gt2rnrqtvyk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gt2kjhbucgy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gt2jakgrlnk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2fypzexxr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2eshjvnfd.html

[J08] 提取年月日与星期
来源：http://dali.cucudq.cn/Article/details/gt2xgbpuwdq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gt2ovjwmatn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.vqdsnc.cn/Article/details/gt2pfpxwhzr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gt2ztnglutu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gt2yzzmqkgu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gt2seporlyx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gt2kntlwpii.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hysaishi.cn/Article/details/gt2zgzsccdb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gt2vrnnjqes.html

[J09] 时区处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dpdqzyef.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfrdtrzl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jiagoushi.top/Article/details/gt2gsnuorgz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gt2oyujozrg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2zlihgcvc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gt2mfssubpz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yonumen.top/Article/details/gt2yrqkosni.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gt2clqkoxst.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gt2omipqffl.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gt2jqapbzen.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gt2pvwatywy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gt2vjrwvswq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gt2oyjitnrw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2bcvlflsb.html


<!-- 参考信息 -->