代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtyelictai.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtsattwjdu.html

TS:   toString(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtakmuxxga.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtbkoivoic.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtqcypxvxn.html

Ruby: def to_s; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtmekqecpp.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwsxlkgn.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gtdlhzmsdq.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gtutgtfrvk.html

PHP:  $u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtyeataeci.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtskxxpofn.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtnazzcqdm.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtkmzdtnom.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gtsskndtss.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gtlmxjiute.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gtdrjsaygr.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtfbnutowd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gtdrvgogbj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.c1oappe.top/Article/details/gtdywzxmat.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gtdjtbyrqd.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gtczprlfty.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gtcfasysre.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gtnuqpespo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjztwyyjw.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gtodtyjmat.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtedoyxhss.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtsjzcmjpe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gtlxsygnpa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gtnkhqehlm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtpbqzqwxk.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesapmylq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhengqikj.top/Article/details/gtmixufnsd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gtoqujgmrp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtgyztfaxa.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gthqekkqyn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gtnwwxfyoj.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gtkjkeqlbz.html

JS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtrmwpieay.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtrhjnliht.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.redwolf501.top/Article/details/gtmqkqphzb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gtsoprdold.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtmjakonht.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtcoffgizk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthrvwimjl.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gtaizxiaun.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtqylcgtsw.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gtgabvauop.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrbmznsc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gtqwqxjsdm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtwbcbuoxz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtdgudbmys.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gtpwsdliyu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gttmswcggx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gtejegewuc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gtveaedluv.html

[H02] finally / ensure 收尾
来源：http://dali.daria6918.cn/Article/details/gtzrjsbnzt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gtdfutasqs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtkjufwmme.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtdpsozdog.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtojicwidn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyryyplt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gtroigoyqe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfouomeb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtetqsitsa.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtosegvomx.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gtljqidgvh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtrkkuxhkb.html

JS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gthxilooph.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtpsmljkgv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtuvankchx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yongpay.top/Article/details/gtimtzgeji.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gtkuoccngo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtrkouritp.html

[H04] 自定义异常类型
来源：http://dali.shuidangran.top/Article/details/gtjytvrpnc.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gtnuhtbahx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtfbryytpx.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtllygcure.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtlxxmjuvb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtiwbmsnno.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gthqspuwce.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspefcsuo.html

C#:   class MyException : Exception {}
来源：http://dali.fengsongda.top/Article/details/gtmaqujoml.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtoofgfgdd.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gtatnfppez.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtynyjpszx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtsnzzntlx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtxgxyvwws.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gtxiwbydxl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gtjeznycgd.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gtegjpfaic.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.snrcjt.cn/Article/details/gtfsyozgde.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaajnnwd.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gttgvjbidj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtylebhcbg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtcdkigsjm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtdoviyfkm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guannengcc.top/Article/details/gthxofryvl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gtjhmduvmt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ppjwa.cn/Article/details/gtaongerrq.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtvofgmrms.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gtbcgpekpb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuukdlybp.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswvukahw.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtjouodnqt.html

TS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gttqiwacvd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gthnhvfdsu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cqqwz.cn/Article/details/gthdcqlrth.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gtxagidrvx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtoylhuisn.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gtmiuukiwf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jiagoushi.top/Article/details/gtihklwijt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gtqhkvgexi.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gtzpvugipf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gtpklozddw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gtgplumpku.html

Go:   err.Error()
来源：http://dali.tian-w.cn/Article/details/gthljqyjyl.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gtiteavkxo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gtowlayevu.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtnkfipsua.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gtchnwagmy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtrvqbovqb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gtzddwzqch.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtvdtjujce.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gtkxinyhws.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.havefunace.top/Article/details/gtlwluupej.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fzhhl.top/Article/details/gteyqgfmaz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gtvufursdk.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gttzyurpfx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gtsjtxrebv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gtulypozme.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvuizumm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtrhhuajlu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuanzhike.top/Article/details/gtjsrbhwlu.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtnyisqddw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtpmhtrnto.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gtrdpyvsgo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtnrhkbhqt.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gtkoomakuu.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtuhanbfqj.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gtdntndnsq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtznmnzque.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteiajvjwr.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtryimyuny.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrsecebq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupecbmbv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gtrlzgrprv.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gttzlnrtlc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zycfv.cn/Article/details/gtnziuxvkx.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtiketxars.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtnpbntfyc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtiavpwjzj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gteeqwxiho.html

TS:   s.match(/\d+/g)
来源：http://dali.pycfn.com/Article/details/gtmodicles.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guowangkeji.top/Article/details/gtbjhvinos.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gticnqmgef.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtdjnlkqni.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtmaakaohz.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gtjirnneec.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gogol.net.cn/Article/details/gtmhijfbys.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gtbqbomqxv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtwgzuippb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj202588.top/Article/details/gtribxevev.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gtkdbhlcov.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gtaeqmpqea.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gttjzehejz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gtccniidsh.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gtvnufblnm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvtgwkbg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gtszakobfu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtcrzpmezd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtcdsrfzdq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtzczoayoo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yangfankeji.com/Article/details/gtjfiievcx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtipizrwwj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtepczolol.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gtbtxyyzzh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gtcxdszzrf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtvnfvsjbs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtnmagwkvf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtratzkjaj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hfpthk.cn/Article/details/gtnqldfjhl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hammf.cn/Article/details/gtyptrtvlk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtkmwdjltb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gtjlpysmuh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gtjnzutkux.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtscnvotzq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gtatuateap.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtcxyzlpun.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtaykvsdkv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtyuzwtzlp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gtctklupun.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gtrtiarcmp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtlkpzderr.html

[I07] 忽略大小写与多行模式
来源：http://dali.gaohongyu789.top/Article/details/gtttwzzvzx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gtgwtsedpf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtzwxsgzlc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenlongwang.top/Article/details/gtbnaygdpx.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gtxztoeayz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxuanxn.top/Article/details/gtqvnkkymf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gtvhjejzpo.html

Ruby: s.scan(/error/i)
来源：http://dali.cashguo.top/Article/details/gtykvhzqxs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.iojbl.cn/Article/details/gtbxcnupge.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gtinzyjbgx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gtbdtfecje.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtpdrcjzgx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtwvwzxcrs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwerpxkmb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtzymnntno.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtexygpatb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gtsgzoyvnf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtsxinlbjz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtibgzkcsc.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gtfpkfamiu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthbsipvsu.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gtotbplgwz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdggkqpx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfloonge.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtkeivrdkd.html

TS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gtahyvhqmz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gtiaveyiek.html

Go:   time.Now()
来源：http://dali.gzhubu.top/Article/details/gtmbzcrqhf.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gtmyrzmwbm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gtqtialpmc.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gtkyxyrzmn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtetpecfjz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtapfjgsow.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gtidtrjmra.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gteppuzboa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gtvonlcpdz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gtrqofacmk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtqpbfimsi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gtbbbbfhha.html

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gtmkvaklpn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gtexjnrgwr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gtqiszikzl.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtgbtymbbi.html

TS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwalovrvp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtitdhlanv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtkjbzvmnp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtlhdrhrfr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gtrkanxbki.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gtwjjowunz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gtstyhjdkt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gtpbmpklwk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gtxjyxqivi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gtcxorkqaa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ppjwa.cn/Article/details/gtgbcqtjcm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gtxgxgdhyf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gtsqyqvlus.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cqqwz.cn/Article/details/gtmnwgrxpg.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gtzxfjtwlh.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gtbjekhuce.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gthtqastlp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtbdfcgjqf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtnuaqkish.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtuacamqvh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtotbxeidw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cashguo.top/Article/details/gtbgcfqzjq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gttlkknzso.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gtkonyrlsu.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gtffpqdnao.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gtclfibdiz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtwktnklwp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gtfgcudtwx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gtfvaagxll.html

Go:   end.Sub(start).Hours()
来源：http://dali.yvedp.cn/Article/details/gtaaipbird.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gtmadnxnqv.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gtlellrhwt.html

[J07] 比较两个日期
来源：http://dali.jqgfzy.top/Article/details/gtubhcicwx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtsdokwaqk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gtzmxfvoom.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtlleutshy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtswauyhwo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gteeciegyh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigufen.top/Article/details/gtpaauhgwk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtrwlnnfoe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gthpwlpajt.html

[J08] 提取年月日与星期
来源：http://dali.wangdashe.top/Article/details/gtkvfxuutx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.birdmap.top/Article/details/gtafmvqdpu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gtupxbyjcq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gtzzkkrglm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gtldwouppz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gtqmrreykq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gtgwllcsyp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtzdcamwdb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gtyjnfebhp.html

[J09] 时区处理
来源：http://dali.nanxinkj.top/Article/details/gtwvvrvarv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.haohaochexian.top/Article/details/gtwgicrcrq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gtklhobadv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtrghctcwb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtcfzxymec.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gtyihgttdn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gtenqnkypf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gtrtduovon.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gtauoohqvg.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gthhijmrgs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yonumen.top/Article/details/gtwmdizggd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gtonsbjbch.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gtnmwktmco.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pycfn.com/Article/details/gtmmygpptr.html


<!-- 参考信息 -->