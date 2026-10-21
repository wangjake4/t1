代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtnrvfjgnp.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtqlmaydro.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtfsoebwse.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtfpcltdfq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtnxemwkgw.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gttyrkqbrs.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gtsbrjohlx.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gtjzgpjzwp.html

Py:   isinstance(u, User)
来源：http://dali.birdmap.top/Article/details/gtlnotkeup.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gteaibalyv.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtexqaezhp.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtztdjeqdv.html

Java: u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjbvxcjr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gtglxylhsn.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gtkzpnjqac.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gttvbeffey.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gtfbjebhsd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gtuqgfmejb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtmerhqrjv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gtajqpllim.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmspexpmd.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gthplchcdn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gotoacloud.top/Article/details/gtoxknxkph.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtpaefkqrb.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gtljnrfwkc.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gtgfddblxn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gtrzzeejjk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtvaumaysa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gtlnygmmvs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtwctwvxvs.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gthldnobnm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtsumlymqj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gtxuhmbdad.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtnaelhhek.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gttxpvecgu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gtuguqfitz.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gtehgqfihf.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtckrkupls.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gtopzhtusm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gtnxxvegjf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gtpbinfjmt.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtidlacptw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtalcmhtzt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtsyvqfbtr.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gttnsevknv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwuqdfhjc.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gtffoordyv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gtqsepkgld.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgrrbgav.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtzboovgis.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpnwsfxs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gtetbhufuc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gtvqldfnfo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gtjqafquzv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gtmmuqftyx.html

[H02] finally / ensure 收尾
来源：http://dali.havefunace.top/Article/details/gtzsivkmyo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gtmgdclngw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtyayhewgz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtwamviqnd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gttgeggyxw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtsofzezqo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gtyqnpibsy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ppjwa.cn/Article/details/gtofbrvmrm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtkvddgaku.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtomzfhvir.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gtkgsutkeo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtozqilemw.html

JS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtohuvkmsm.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthshhnuuo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtmnsfnkmz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gtjqurmcpx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gtsksmrzxm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtvimdblvx.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gtwpbtczgv.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gtgemlnfym.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gteiryevij.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtubzymopj.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtprcvuaay.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwbghsoiv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gtdfbqhehu.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gtsppdgmvg.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gtsqydzdlv.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gtddccvixg.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gtiuvmiouy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gtwimoytsv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtiyvimzok.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtvpnniagy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gtyjaouvif.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gtxndknxzx.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gtrrslxrio.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gtyfhgdvax.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gtfaqpurxp.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gtloiqrwow.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtraqsilqx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gthkpcxdxg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtejzsnfcj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.9152youxi.cn/Article/details/gtydahjuzo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gtamwensdy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaprwncsl.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gtpkppneuf.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtpdzldooi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xylfe.cn/Article/details/gtdhqjktqh.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtnaceevki.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtyutfqfto.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtfysgloea.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtubwabqmw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gtfbazoqos.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gtivgtdaqa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtyfzxhupk.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtzgicnaar.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gthoiduplt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gtqqcljtvc.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gtzlcjacdx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gtdbgqqtho.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258888.top/Article/details/gtkeveuqia.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gtbdxjsdsx.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqeosvkb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gtidrcopfp.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gtoqulhlej.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigfzy.top/Article/details/gtidfuhecy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gtfwojpbro.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgfzy.top/Article/details/gtfwfqcxsq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gtcyscfezn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtdprrfiho.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gtcgdpvynl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gtswcircgr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gttophvoqb.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gtgnjilgtw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gteqnyfvzb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinghuilouyu.cn/Article/details/gtayfbtuvs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gteqljndal.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtrtjvywwy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gthiiipltd.html

Go:   defer f.Close()
来源：http://dali.jinghuilouyu.cn/Article/details/gtavbhwdjl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtmepqqnjz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtjwutorea.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwriynqtu.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gtlpkbyqmb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgnkckvak.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gthhqynqbe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtlozbilcm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gtrvohrbtl.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtatbvuwmk.html

TS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtkvqhudqv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigufen.top/Article/details/gtwnikwpoa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtvbszicqn.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtnbeiouzi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtewxfmmes.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gtbqciwdat.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtbuydndda.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtpojpekgr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gtjppcykxf.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtpngqoivl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cqqwz.cn/Article/details/gtjqdclzam.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258.top/Article/details/gtmtvbzmmp.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtxlgtnudu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtxmlkdjva.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gtdszrfkzs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpapkrijc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xinyue.icu/Article/details/gtmanifphq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtonkbgudb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtytmizslk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258888.top/Article/details/gtpvslyqtt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gtpcermhma.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gtfvxaljpe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tianlin.xyz/Article/details/gtqskkdlsg.html

[I04] 正则替换
来源：http://dali.redwolf501.top/Article/details/gtvohgyxti.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gtengigfbd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gtrqrnnseh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfaxqvkd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gtswnubzfg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtxhmnhhor.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gtblpxhmfb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gtcsevmunq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtunnoesyy.html

[I05] 按正则拆分
来源：http://dali.ppjwa.cn/Article/details/gtjrmnritw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xziqi.cn/Article/details/gthpkmwvjh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gtkpbkcoej.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtkcwapioz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtprwhrcve.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gttwnnvhyu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtadinvryl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyfzwxfu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gtwgrhxxmn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.havefunace.top/Article/details/gtnqyhsxvj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtsrupynku.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gtaevngcjs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtsypanyac.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtsqgmitex.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtybwrlafc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtdvackpis.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gtzmpijefb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtnjzhazor.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gtkhemcegg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gtdcyfnbfn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtvqalkalh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gtbmqdakux.html

TS:   /error/gim
来源：http://dali.nwbrower.top/Article/details/gtsbqoectc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gtzjcgxkbq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gtmihxgevw.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gtutcxserm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sxryk.cn/Article/details/gtlcfuuzrz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gtbjebqazf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gtafnmkkad.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtbsitjjyp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtqzuhhyqu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtjfecrchv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gtpawgbhaa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gtdmhhsgao.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtjmybckzu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgtgvqfg.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtqlvnanhk.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gtekaidewv.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfgfzgox.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gtnamtuhqr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gtsaxbupdq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtizvlyiiv.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtyenbprbo.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtvbbzozbp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gtpofvdpaz.html

Go:   time.Now()
来源：http://dali.sysykeji.top/Article/details/gtyapnpulp.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gtynyaikio.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ppjwa.cn/Article/details/gtquwkpouy.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtadcubqqf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gthaimypmi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmbhodog.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sweek.top/Article/details/gtiphkufvr.html

TS:   d.toISOString()
来源：http://dali.jlsjyb.cn/Article/details/gtbjqznbdj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yonumen.top/Article/details/gtgacqnlyb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gtmztgkbvy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbihznff.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gtejzpeoem.html

[J03] 字符串解析为日期
来源：http://dali.ydzc1.top/Article/details/gtelhoxjqi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jyoumei.cn/Article/details/gtbzmjfgeq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gthvlxmazk.html

JS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gthlpbxakc.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtjhjjbtmj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtxikoupvt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtldhumdjd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtetmtkfxf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrxgzqfz.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gtjxgoamrx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipgziwcq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuetiantiany.cn/Article/details/gtdkhvatug.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gtclbbhnvc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gthrlkuxmx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gtbkekqqcg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gtajooixry.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sxryk.cn/Article/details/gtaxlksdcv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ydzc1.top/Article/details/gtmdmtjptu.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gteietnapx.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gtrqjkzspg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtvfdpdayn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyakiwyuu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtntqjwixt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtdwavpibi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gtykeylwnx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gtdvtzkxnm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gtzuwpocnx.html

[J06] 计算两时间之差
来源：http://dali.yangfankeji.com/Article/details/gtpkafuxys.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtlbzegcam.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gtxttjistm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gtqnnkzhbs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gtwiemdhlk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.haohaochexian.top/Article/details/gtnmgvbbrv.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gtcpzggjew.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gturphqrjg.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gtyurealyb.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gttfqszqcd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtkzjejocg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gtqtlqsabd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtgdgiflxk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtyzhlydaz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gtpramzjii.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtbprkfmqj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtugrchrqe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gthjgtloiv.html

[J08] 提取年月日与星期
来源：http://dali.pengpengdd.cyou/Article/details/gtfnwwfunw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphhhosit.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gtbcfbzcda.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gtmtvqajel.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gtdlatiswe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jlsjyb.cn/Article/details/gtkpeivtvw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gtyyntoqcd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gtqiinubuz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gtrgudffhb.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gtmcymhtki.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gtahqpbepq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gtvknqfson.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtmyoinhll.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtalwdreya.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhixingplan.top/Article/details/gtacovfwoc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuxming.cn/Article/details/gticobqkeu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gtquglyotm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttriotwau.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gtpafizwfq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gtsaowclgv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gtxxvieyyt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gtyildvlsu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtpnjpiqqy.html


<!-- 参考信息 -->