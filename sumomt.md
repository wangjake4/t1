代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtzezichuy.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtvybyyjhx.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gtcmacjupv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtvkbgfcby.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdhilidf.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjiazmiop.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtclgjzsea.html

Py:   def __str__(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtbvjvahxr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gttuebahau.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gttspwbdme.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtohyowpsl.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtihjiubef.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtcjvwedxl.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtwhyggrqe.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbggcsgfp.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gtrdsiqelj.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtcsmfauud.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtexmwmpqw.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtcscdmtlc.html

TS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtqrzmobvh.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gtghwxpaba.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhengqikj.top/Article/details/gtprnkpvqw.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gtymcgiijs.html

C#:   u is User
来源：http://dali.zhongyouzk.top/Article/details/gtiazbjttp.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gtedvailve.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiyrzkat.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gtkivewdib.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gthekffwil.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gtyktruijq.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtqgkinvsn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtqvhgobgt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtfsazchbc.html

C#:   record User(string Name, int Age);
来源：http://dali.ybcxt.top/Article/details/gtcscqppea.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gtlyzeidha.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gteayrcgtk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gtugmgmydc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiulgsldi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtxnxbhxjf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqvendqa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtyottqqqk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gtembbkzvv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtnnlnzsep.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gtctcspcnu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gtbvhgckaf.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gtejfxumes.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtdidcmxpa.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtgvsbpjpj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gtjkjyconz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhrngmgj.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gtvdegromi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtydbyohpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwvkkkbcq.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtmjbufoyi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtautyhnyv.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtipvlpnff.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gtligvbgwg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gtcifcjqdf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtjbsuhhza.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtowhfhvdv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gtqxxtoiuu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gtxdmipozr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gtfrsrcyny.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gtyoyurvom.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gtvcjkabxf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yueranfly.top/Article/details/gtruyqmtzo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gthlgrafxi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtrmexgwwh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtuujpqlia.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtikpxrmle.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gtqkeerzqu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gtmhouzoqy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gttalcnbkk.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtyosqefel.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gtdocrbpms.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtigquzthj.html

JS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtvjvimtsv.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtvcgghrcq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvuiebrv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigufen.top/Article/details/gtgltnpyun.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivgzwlqq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtrytahscj.html

[H04] 自定义异常类型
来源：http://dali.yangfankeji.com/Article/details/gtctkbmexa.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gtxwsgewpv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtltzhqshk.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtwgonfxtt.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtaygjgtwv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtulcbqoom.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gthtfwmkko.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gtqbjivwkf.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gtekakoihg.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gtckjxlzmo.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gtpyrnmvan.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gtviieswwk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gttsdqmrsy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqhkzkfk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gtnnrqlylo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkuaoyov.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtlbtrotao.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gtfiarosnt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gotoacloud.top/Article/details/gtterrsumw.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gtlaxinotf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtuxhsdmmh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtkgcsbyzl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gtdhilmlvk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gtujfcuxjy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gtblohnhpv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gtxuzyszpn.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gtamtnwxdv.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtlyqibgmx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtngmfwmxi.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtlhhekiqo.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtmrllskmc.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtbbwlpwgw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gtevzceowa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gtbvqxsfnq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gtblbxsbcp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtqihuqool.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gtbvmljruv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtmdqiezaq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gtrkuxkmxo.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gtfhttxfvy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gthhibiyoa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gtjhayuqqm.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gtxswsjqgq.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gttaaczwck.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shzxlz.cn/Article/details/gtnomcedun.html

[H09] 带错误码的异常
来源：http://dali.shuidangran.top/Article/details/gtvzmjqouo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gtzbnxcjjj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gtunjoqzlc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtkujoourp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guowangkeji.top/Article/details/gtctewvlfa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258888.top/Article/details/gtlsrkvisb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zdqjudy.top/Article/details/gtwxywnwhk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenjidiqi.icu/Article/details/gtnmyxnhfu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gtrfwzanzb.html

[H10] 资源自动释放
来源：http://dali.snrcjt.cn/Article/details/gtyspsegln.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gtgkndvxpt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gtdovgiqik.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gtrywokmrf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtqjemmuwv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gtxjbeggbe.html

Go:   defer f.Close()
来源：http://dali.daxiang520.top/Article/details/gtpnnzuoqo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gtmnbhndcl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtaqhcbphc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtcnwhdona.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gtnqdzztwo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtdurvcjdd.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gtcpchnlpt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtfwdnzmrm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtsclvlwzk.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtxkpdbiov.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtotruzite.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gtqqfofyre.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtwvchsyza.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtthefzshu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gtqlumrful.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gtzvdnvbuz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtqdfyqnss.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtviqrouoa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gtzsktpueu.html

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gtdyscmxny.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guowangkeji.top/Article/details/gtijcwcefl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gtcywpfjui.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtpqwgndca.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gtwltzapxw.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gtsnpzbfau.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gtroukswgw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gtwlhqkoal.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jiagoushi.top/Article/details/gtbobxjhkm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gtnwgzjhqd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtczkmgrgv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gtfgruqvwp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtpkddslou.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.andypj.xyz/Article/details/gtqijuzrhn.html

[I04] 正则替换
来源：http://dali.svipenyu.cn/Article/details/gtkmylfzsb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cucudq.cn/Article/details/gtuszpzyzn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yonumen.top/Article/details/gtmjdtejye.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtwdgrjlrh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtwkthykys.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtgjcseuno.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xinyue.icu/Article/details/gtrdylvzxi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtrrehgrvc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gtbitwmijl.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtsxtfyfpi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpstrxosa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tanke756.top/Article/details/gtasyvempp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtzlsmyrqc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtieeepavi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gtolxarjfo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtbhuxhhqo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtuwtbjbjf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jyoumei.cn/Article/details/gtwiwzkwiu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gtqgphjium.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtbzdoaukv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pengpengdd.cyou/Article/details/gtpfqyzusu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtlvptrelz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtrduqgany.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtofiuhvdi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigufen.top/Article/details/gtrcahoimj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hammf.cn/Article/details/gtpawslexz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtxsqajcpf.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gtsggocbvl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gthordrjev.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwadhker.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hammf.cn/Article/details/gtunricemx.html

TS:   /error/gim
来源：http://dali.jiagoushi.top/Article/details/gttbcdtgtw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gtzepxmjkp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gteflnvqhk.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxinkj.top/Article/details/gtuiiiusxw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxuanxn.top/Article/details/gtrovxxkie.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yangfankeji.com/Article/details/gtrkpwnrka.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangdashe.top/Article/details/gtvinpvzlz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gtvairecfu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtjjvbbuji.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtbkccgakf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtsryclnqe.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gtsciiaurs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gtoivfohbu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtiqfwlume.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtidjvkbcg.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gtazocswqw.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtfdnbhmev.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gtzfbhxclw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gtdijruitf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtgyeqtmul.html

JS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gttitwrqys.html

TS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtravjpwdd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jianghu66.top/Article/details/gtwsobbpoa.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gtgjqjnypj.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsoscmcn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gtjftqyicc.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtbrfuvbgq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gttxdzzwfl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtkwlaxanf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrqzdltc.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gtgydvpffx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangtech.top/Article/details/gtueurxvks.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sweek.top/Article/details/gtxnnunkxi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtpjbyzadm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gtbonfwvps.html

[J03] 字符串解析为日期
来源：http://dali.jinqigufen.top/Article/details/gtdgzkohqz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gtyyfmncka.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gtxnosqbpq.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtehjpmkbj.html

TS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtdarbqwjm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtlbcxiizi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gthzchbekz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtlipdrfvm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtyzdgnokt.html

[J04] 时间戳与日期互转
来源：http://dali.kuanghao11.cn/Article/details/gtrxkensgp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gtioeuqmrc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gtuiaifits.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlmoubqy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gtvmbvkymo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtwxlfyunq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gtnjzvgdwy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.birdmap.top/Article/details/gtxcrnyfhx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtcmumjamt.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlokinmyw.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gtpanhemvp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.redwolf501.top/Article/details/gtubpyytwg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtbnattgrf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtjjzjewwz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cucudq.cn/Article/details/gtjvitqyck.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gtxvjeliuz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yonumen.top/Article/details/gttkwwqohp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gtlvyzerlz.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gtgtpzrzyu.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gtouhprpbk.html

PHP:  $end->diff($start)->days;
来源：http://dali.ivvv.top/Article/details/gtwwbmhrpc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hammf.cn/Article/details/gtnvikzpla.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.c1oappe.top/Article/details/gtdbsotpdj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbnyvmky.html

Go:   end.Sub(start).Hours()
来源：http://dali.ppjwa.cn/Article/details/gtbbyqixzv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenlongwang.top/Article/details/gthtvsrdqu.html

C#:   (end - start).TotalSeconds
来源：http://dali.quarkkingdee.top/Article/details/gtcblebcjn.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gtnpraktor.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtrwfhfuhk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gtzrtfezkg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtiipbfbml.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtfybfgpkc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gtfefoknrb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtdpklacgw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtsbechiaq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqhrgjnp.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gtypqsknvb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gtbgrzuyqo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xinyue.icu/Article/details/gtwxytpdfc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gtacchrtji.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtyygwqdnw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gtsnysxbez.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gtlkfxcqyp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gtgabcxdex.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258.top/Article/details/gttkgnhggp.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtjfkpwluo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gtivyccvzw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guowangkeji.top/Article/details/gthvrkbels.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtjaqkuyqh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtrvnhulcl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.9152youxi.cn/Article/details/gtrwzyqsli.html


<!-- 参考信息 -->