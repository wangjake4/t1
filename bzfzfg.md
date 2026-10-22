代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2jwkszcla.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2lzetwoly.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2hfvwlbhr.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gt2ptbzqaza.html

Py:   isinstance(u, User)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uuebnakd.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2fmavgvkv.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2rdytuoaa.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2fqeglbis.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2ivhzecnk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gt2dbzzwckn.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ystrbvdl.html

C#:   u is User
来源：http://dali.vqdsnc.cn/Article/details/gt2xajnejxl.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gt2vkunxcgv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gt2gicferhh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gt2qbwgtzrm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gt2myrngwdj.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgufenzy.top/Article/details/gt2nhozlgjh.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gt2vvvaefwm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gt2wjerntjc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gt2dtqkzzan.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gt2giaujvnv.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2gfvpxfdo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhengqikj.top/Article/details/gt2fxvzylzg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2dtoqetkm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gt2nvfwihgr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gt2nugfjdyx.html

Java: enum Color { RED, GREEN }
来源：http://dali.snrcjt.cn/Article/details/gt2hxuymkec.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gt2rmutgkgt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hfpthk.cn/Article/details/gt2ildwduyc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gt2klsudmte.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2inhhcdlb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jyoumei.cn/Article/details/gt2bybngxhx.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gt2kjqzbewx.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2qlrrnfqp.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2tnznxmyd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gt2ltzsyoro.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gt2zxnggubc.html

Ruby: obj.instance_variables
来源：http://dali.yj20258888.top/Article/details/gt2drmecphy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gt2lrqwnkqf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2wjpioorr.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2fvcffojf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ucwzjvhe.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gt2amwexvpf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gt2eiotkoqa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sttkazeh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2jtqkxuqk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2otfabyzm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gt2eigovufu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gt2ewzzjrnv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhdfrhvt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjsahypk.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gt2knvhbygs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gt2arcdwsyz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2vklsfgtk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2kgzfpveg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2vnxaobdi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2uozwtsyd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gt2ofjgbuxz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gt2izhwyfws.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2extljsot.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gt2jgyebrza.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gt2ejhnaugp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2fwmtcxpm.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyuetwp.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ygotwptb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gt2aobsguxy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gt2upflgxxx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gt2azzpfqnf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2gmtuconk.html

[H04] 自定义异常类型
来源：http://dali.sysykeji.top/Article/details/gt2noltnyrb.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gt2xtsdwqin.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gt2zzlfbzvt.html

JS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gt2rjyyihlp.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2fvyvwotn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gt2gsbjgebj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gt2vfgksgzd.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gt2mmjtpnjp.html

C#:   class MyException : Exception {}
来源：http://dali.xinyue.icu/Article/details/gt2tjtkvbqk.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gt2cgqzkooz.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gt2vejwkvuh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gt2crmjbzhe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gt2fswzibvv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gt2yiokxhnv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2dvyprjfm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gt2wdzxocox.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gt2dfsusdgx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gt2lzbhiqmp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gt2dmgqwtxy.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gt2pusdpsyi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gt2mhcisiii.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2coiwxvxd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2nvoqbeql.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gt2scpdbepo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gt2dnkiczyd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.andypj.xyz/Article/details/gt2gjlfkyuy.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2dgknsqon.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gt2mehnaoeg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gt2oqvbyspw.html

PHP:  assert($x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2dfllvpbi.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2wcwsfssh.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2xllilulg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gt2dtolflvw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gt2mbujjbrc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gt2ispqcdgg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2mdwxilbm.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gt2scmcxmqa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gt2nqxuepqz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gt2cdmrzefo.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ltepkdwj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gt2utbuopts.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gt2iqesrsrp.html

Go:   err.Error()
来源：http://dali.chenzaomai.com/Article/details/gt2owjiqxoj.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gt2uwbuqrrn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgfzy.top/Article/details/gt2ydvaiyzk.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gt2sjbufuky.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenjidiqi.icu/Article/details/gt2eiklddhj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gt2hnkiomfu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqxwosgs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dilmrypj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gt2trluaduv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gt2yogqzvov.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wlhyohyc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gt2aguypdsx.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gt2gprplnos.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gt2ljqtqcon.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gt2xcvmzjxm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gt2gmybcyul.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gt2zxxcasos.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.birdmap.top/Article/details/gt2fwgqvbuc.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gkamidpq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gt2xarlrsqz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2zleuaxpp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2eivhqido.html

I. 正则表达式
来源：http://dali.yueranfly.top/Article/details/gt2oltmscfr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2gpljzvcl.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gt2nwhqheys.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2csydlton.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2qkvemzjt.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gt2bbezjhvy.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gt2jfzpyfro.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuanzx.com/Article/details/gt2jpaxtovs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vapzbbml.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2gkdqtbpm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gt2mkwnxdmp.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gt2sbmuhlbl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2jpgaxnck.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2icldpkbw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zdqjudy.top/Article/details/gt2tgmwkyxk.html

TS:   s.match(/\d+/g)
来源：http://dali.zhixingplan.top/Article/details/gt2blslpbuz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gt2egfvboqe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gt2blggietq.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gt2jnxopiiy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gt2ostqgeme.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gt2inthbpgz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gt2lruzbsll.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yangfankeji.com/Article/details/gt2silpahqc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gt2gmtiinca.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gt2skaswjyk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gt2gojgdvnu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gt2mcgeonfe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jianghu66.top/Article/details/gt2kdorarqg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gt2toxmjctf.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gt2ybouzpad.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.316326.xyz/Article/details/gt2yejxipuf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2wsfaeazi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2hlowzcza.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2macrthhv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gt2qkvzzvjc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2hvoxqkgu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2dizfqapy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gt2wvbsyxla.html

[I05] 按正则拆分
来源：http://dali.haohaochexian.top/Article/details/gt2mddxkxaw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hfpthk.cn/Article/details/gt2vbqpblnd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2xvyilrxq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2sjtlovav.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2etmzncrc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gt2yonqprhs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvctllps.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2punruyxg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxbgeeqc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jlsjyb.cn/Article/details/gt2clxrdcne.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2lsfgsumo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hywenlv.cn/Article/details/gt2dwgtwaoy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gt2pmhkdqao.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gt2gernnwzz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2ifexarls.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gt2ehqiovua.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gt2euiovliv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2bmrxxpwr.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258888.top/Article/details/gt2aoswcwke.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gt2xfilcple.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gt2fzdrhzys.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.vqdsnc.cn/Article/details/gt2ebwkzthh.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gt2memvlsoo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jiagoushi.top/Article/details/gt2omlggdpc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gt2ashvuibm.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2htvifwbu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhengqikj.top/Article/details/gt2eevtokhs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gt2owmcpgrg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gt2wmxupnyz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2usrfqieb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gt2vptcpfdk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnymbaw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2yeafsbjc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gt2nmoxbzmf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guowangkeji.top/Article/details/gt2cmqgikvs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gt2inwxzqui.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2gfyhkgjq.html

J. 日期与时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzsvslrz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2feuqoohj.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gt2sjtsdgwc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gt2hjfqwttp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gt2etcdmwti.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2agywdasi.html

TS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwemdets.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gt2txtyujgv.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gt2xdotmswx.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gt2ixlqfrwe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gt2xkrekgxd.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gt2qplllrro.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ymsodpfq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gt2jjydrxfq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gt2ftxobetx.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gt2mgkdpzce.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.snrcjt.cn/Article/details/gt2ldgmeeoj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dashuyun.cn/Article/details/gt2iwbqjghu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gt2plueatgv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258.top/Article/details/gt2ciuvjkly.html

[J03] 字符串解析为日期
来源：http://dali.hywenlv.cn/Article/details/gt2xjujwmqm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gt2gqmxcxzy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gt2vstnpkac.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxsppyqo.html

TS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2gqttekxp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2xiogomjf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2jxvpnrtp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2qaivsmrk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gt2djnxcqba.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gt2wvturrra.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gt2abqzctlv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gotoacloud.top/Article/details/gt2lqbvuyqv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gt2tiinbxqz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gt2zqtqspnl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2xcvgyauu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eogufumz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2hrioftow.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gt2zzhuaepx.html

[J05] 时间加减（加 7 天）
来源：http://dali.hysaishi.cn/Article/details/gt2tkiwfxrv.html

Py:   now + timedelta(days=7)
来源：http://dali.gotoacloud.top/Article/details/gt2ssrjlxou.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gaohongyu789.top/Article/details/gt2fosxqiys.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vauxnebq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gt2blsbcovo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2gltanebc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gt2zvuyiipw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsgqlevq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gt2iluoxzce.html

[J06] 计算两时间之差
来源：http://dali.yanxiufei.cn/Article/details/gt2qqdoddwh.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gt2jmuvaljm.html

PHP:  $end->diff($start)->days;
来源：http://dali.xinyue.icu/Article/details/gt2mqgxsgpm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yvedp.cn/Article/details/gt2lyhwlkcg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gt2iputzzbo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2qcfaonqu.html

Go:   end.Sub(start).Hours()
来源：http://dali.fengsongda.top/Article/details/gt2efajqzld.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gt2lmlnlfdr.html

C#:   (end - start).TotalSeconds
来源：http://dali.iojbl.cn/Article/details/gt2pxnhrwwa.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gt2fwuujchb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gt2zlzrmiry.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cashguo.top/Article/details/gt2wvwunexn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gt2kvyxfest.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2blfsfxcq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2wingbfkn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2jycbpzul.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2ytzgozcj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2qtvkpxgq.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gt2djzfvkuw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqszlesi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gt2irypqibk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gt2oyzdwseq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gt2nuzfrepd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gt2mbtzfvrz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gt2rkfztcrt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gt2yjvjvbja.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gt2rtdwofer.html

[J09] 时区处理
来源：http://dali.jianghu66.top/Article/details/gt2dqzfzquq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gt2oznjhxhu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gt2gijxyfyb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxvlkjnt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gt2kejmtsrw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gt2ggpbiazi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gt2mjhbetir.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.andypj.xyz/Article/details/gt2jdfqzyud.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gt2cqjlwigd.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gt2zamjvkpr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aizwys.cn/Article/details/gt2icmsvpnc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hfpthk.cn/Article/details/gt2yykbkoot.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenlongwang.top/Article/details/gt2kanqnzvh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gt2uwonnxyw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hreupqci.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gt2xwkqodql.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gt2nodcxgcc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gt2lpyczwfj.html


<!-- 参考信息 -->