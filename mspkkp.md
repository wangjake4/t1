代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gt2aegadiss.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfctlpns.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mqdpxach.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2xgduybvg.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gt2iqfbhtll.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gt2uxpqyvds.html

[G12] 对象转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2aadedqnk.html

Py:   def __str__(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gt2rsqtdwfa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2boapdxzb.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2tohncoel.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2yvxqpths.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2tluklftt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2blknnagu.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2fiidtwqr.html

C#:   public override string ToString() => Name;
来源：http://dali.xziqi.cn/Article/details/gt2hbocdkke.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gt2qqivtena.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gt2rtxvdgit.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2cafcbvpo.html

JS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2iluslmic.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2ovcgdvwb.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2lzqpugyx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2neeljcsr.html

Ruby: u.is_a?(User)
来源：http://dali.shuidangran.top/Article/details/gt2xvjeexem.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gt2nsoehbcw.html

[G14] 数据类 / record
来源：http://dali.nwbrower.top/Article/details/gt2vfqliyor.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gt2yxemwbpn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgufenzy.top/Article/details/gt2zprtnokj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gt2vzjcobhe.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2dulknxog.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gt2arqckppi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gt2xonfkzkm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gt2toqgoopk.html

C#:   record User(string Name, int Age);
来源：http://dali.smart0.xyz/Article/details/gt2zmdjvtcr.html

[G15] 枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2aoedvwhk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcoirfag.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2azishuvo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gt2blwukdtt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qolwvqur.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gt2xfclgxft.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbcohtzp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzroqwjs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gt2fwourxwa.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gt2efxcpiyk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gt2moodqvls.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkesnbla.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhbpspnt.html

TS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gt2bzyqiqbq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gt2twpykbtz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gt2gpnovlco.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gt2xvloyarp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gt2mbjodacw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2aercgelu.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2vcqcxmzn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ejvrnjxv.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rqjtgbsd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gt2zqqrdidb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gt2hexrzbqa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2xkvbravz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gt2mqggdqze.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gt2rxsokdxy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gt2qrlcuegy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yonumen.top/Article/details/gt2sfqishgr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gt2omkvvlts.html

[H02] finally / ensure 收尾
来源：http://dali.haohaochexian.top/Article/details/gt2khvkejcy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gt2rwdbalrn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2okjajchk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fetxdyov.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2rjnqagrj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2pyeadogy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gt2zhvoxesn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2xieonqns.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2zlmkauwb.html

[H03] 主动抛出异常
来源：http://dali.shuidangran.top/Article/details/gt2bzarffhj.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gt2ifuvrrxv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxgmjxwo.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgmydjag.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2phmzreea.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2hcmrfuzn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhzwhclm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gt2ftqvpvsu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2wzlapdsu.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gt2mjghmupc.html

Py:   class MyError(Exception): pass
来源：http://dali.gaohongyu789.top/Article/details/gt2fdzdwdnj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2whwivowe.html

JS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gt2yzyjzroo.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gt2zszoehfs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gt2yypoirjm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gt2ktvkkhru.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gt2tuxhkcny.html

C#:   class MyException : Exception {}
来源：http://dali.fzhhl.top/Article/details/gt2xwlhxwxp.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gt2owvzkrpr.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gt2gqekirnd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gt2zxjhffne.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gt2wshzswhc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2hviqnfyv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gt2wergnwis.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gt2fmjpxhal.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gt2txuwoxwt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gt2brdikigl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gt2haexgnom.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gt2olhlpbfc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gt2vmnpjhur.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iuwxfbau.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2favuqbpu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gt2lavcpgia.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.meibo888.top/Article/details/gt2hcryrngi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gt2ffqyhrsn.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gt2tzndpgjq.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gt2ilvewita.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gt2gcnzzdja.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2mbzlnexu.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qconwvmr.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2smnvlwrw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj202588.top/Article/details/gt2rgouwryz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gt2blmaamtx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gt2eabpbrqc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2uuzzfcdw.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gt2mhfnprop.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gt2dydqnjbb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gt2gutovgau.html

JS:   e.message;  e.stack
来源：http://dali.tanke756.top/Article/details/gt2qrbnbwap.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gt2gffdxjtx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gt2redwjudf.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gt2hvbcpcie.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gt2teyobrma.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gt2sngsxyqr.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gt2qjprzsnk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gt2stgcyjag.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gt2cgslesdw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gt2atiqtddo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhixingplan.top/Article/details/gt2ajrbdiso.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gt2xrtxqwvq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xziqi.cn/Article/details/gt2uqxcfngu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdiujtjl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gt2bdgpcsjj.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gt2vxnjrzsw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gt2bqkahtsw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.havefunace.top/Article/details/gt2xlwtnned.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gt2wplwnwqd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2mgfwvtqs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvavfszy.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gt2pjmncked.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gt2vknbrndk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2fifahvng.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ckjxvaqs.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2hvsnitlv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2kkfutjop.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gt2jofnsver.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gt2yizvvhci.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2rsckxbdg.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2udmmepwp.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gt2dfyualcy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ufypkhrk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2ozepzmjk.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gt2oppenfgw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gt2bimlljet.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gt2vyougklp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gt2zmroaagp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.iojbl.cn/Article/details/gt2focrurvp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gt2xzuqwzdm.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gt2stvknqpm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dianchejie.cn/Article/details/gt2gmxfsvjl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gt2lurqygpg.html

Ruby: s.scan(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gt2mankltzm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2oewjyzkf.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gt2hoqfrsoa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2asqwqoum.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.mhx1999.top/Article/details/gt2isjqpwzl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gt2ubfjmoco.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gt2ekhapyxw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gt2gsofpupc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gt2mzpknszn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2pqcyznvg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.bjfxy.top/Article/details/gt2zcejayvh.html

[I04] 正则替换
来源：http://dali.hfpthk.cn/Article/details/gt2pcrxmkwq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guowangkeji.top/Article/details/gt2lpjhmwfa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gt2zrtwzfad.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gt2yfpkrkvm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gt2sopkphbn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvqnwwmc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.havefunace.top/Article/details/gt2fouqurpi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2iuczzizi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gt2uexngtbv.html

[I05] 按正则拆分
来源：http://dali.sxryk.cn/Article/details/gt2parsgewm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gt2mvjaquow.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2ogafkabn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gt2tddxvnqt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gt2fniggeyr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj202588.top/Article/details/gt2zrtpiwka.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gt2emlotpye.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2adndltef.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gt2wigaqtmc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fzhhl.top/Article/details/gt2vexkahbp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2glxuzjgp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gt2oabnknvv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qrmgdixm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gt2xjurnzln.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2qgpckigg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gt2psailobu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fengsongda.top/Article/details/gt2zephogtr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2gplbbtoo.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfoyjwjm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gt2prjdqzka.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2ysegjakk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gt2lnkccmrv.html

TS:   /error/gim
来源：http://dali.zhoulong.xyz/Article/details/gt2pwslxail.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258888.top/Article/details/gt2bsvbqdsm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yonumen.top/Article/details/gt2fgouicss.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gt2rdqzbwvi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hfpthk.cn/Article/details/gt2ibktodhk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gt2omojwogw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gt2eimndrfc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gt2pyhxpckd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gt2ksmsqyge.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gt2ivgivwvx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2zyvosqtv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gt2xnwfoxtu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gt2qxtxdpiy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gt2biyvchoe.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2oyhkcjqx.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gt2vaushruu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2tcecmllc.html

[J01] 获取当前时间
来源：http://dali.zdqjudy.top/Article/details/gt2tciktoxm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gt2tlxinukr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2ilxilbfi.html

JS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gt2vumgfbsu.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2czoteuud.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yongpay.top/Article/details/gt2jsghgpoz.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gt2elnmovkq.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gt2smpjzdik.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbizvwed.html

[J02] 格式化输出
来源：http://dali.ydzc1.top/Article/details/gt2qapuzeik.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2ofnezzha.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gt2fcltihyl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sxryk.cn/Article/details/gt2dkvwhqop.html

TS:   d.toISOString()
来源：http://dali.jianghu66.top/Article/details/gt2nalaonod.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gt2shmscpxe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gt2hcloyemz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gt2jxvoozdp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gt2qrovftvo.html

[J03] 字符串解析为日期
来源：http://dali.vqdsnc.cn/Article/details/gt2uurwbrfi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gt2wbuzpypj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qiobohzy.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkaiupoq.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2usoxqnmz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2kmvvkmny.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2mnxdygca.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2qnntxoqn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gt2lalkfpir.html

[J04] 时间戳与日期互转
来源：http://dali.quarkkingdee.top/Article/details/gt2swarmgfr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2acvtoyyb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vocysnkc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.bjfxy.top/Article/details/gt2btxtctmo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2lixexlvt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gt2spzknryv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2vvvjlscp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.havefunace.top/Article/details/gt2xgbqmvwf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gt2thofpxbg.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gt2vhcqodxm.html

Py:   now + timedelta(days=7)
来源：http://dali.pycfn.com/Article/details/gt2qmmkpnhd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yvedp.cn/Article/details/gt2iwgxaryz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gt2zufotfks.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gt2cwoiwjra.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daria6918.cn/Article/details/gt2xmurytbx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gt2steqkmsu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gt2pbmvtjhb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gt2ztylbzrt.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gt2vgffhtei.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gt2scrkqzun.html

PHP:  $end->diff($start)->days;
来源：http://dali.cdnleiting.top/Article/details/gt2yjoyyzhr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.andypj.xyz/Article/details/gt2mwdsncjl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gt2wunjvjmk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gt2wzzygpky.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gt2gfyyecdp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvuemsgf.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gt2cybdwste.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krmwdhyr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2xhamlohs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gt2kkurkrcn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2zhjgxvjr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sijmkbjr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gt2ovnatqbk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sufxvd.cn/Article/details/gt2ypcitjtm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2uudbpnmu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2cmjaicei.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gt2evyohcaz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lsyyfexj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shuidangran.top/Article/details/gt2lizxkhjy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlhozliy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gt2aebfuyvb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gt2kdviomqe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gt2xahpkumn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2invuxhuo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gt2divqjuwn.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gt2fnnjikpe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gt2yvvdvpvk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gt2kzizihtv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gt2rhemehyu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gt2kkkncsmz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gt2myeklicv.html


<!-- 参考信息 -->