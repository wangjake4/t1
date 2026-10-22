代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2rrxxcwwl.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2uredswsx.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gt2hsolqecl.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2rdcmhnbp.html

Py:   isinstance(u, User)
来源：http://dali.sysykeji.top/Article/details/gt2dktmsjyg.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2pjhrqtcj.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2tyxrevym.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gjxtrahl.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2hkceiosk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gt2vhkzgxcq.html

Ruby: u.is_a?(User)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvpwfqbo.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gt2tdkyvaso.html

[G14] 数据类 / record
来源：http://dali.jinqigufen.top/Article/details/gt2vhjsewlx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gt2hglmxixh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gt2pusmbmzo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gt2ynorkrhw.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gt2pfzvbqdc.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gt2fbmsasmd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gt2pxtjvfus.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2extkhspj.html

C#:   record User(string Name, int Age);
来源：http://dali.cqqwz.cn/Article/details/gt2mcjoxzno.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gt2zisoxbft.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gt2tzyjxktv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bsblsdps.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gt2bistrwkh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gt2fyazqnjk.html

Java: enum Color { RED, GREEN }
来源：http://dali.yueranfly.top/Article/details/gt2vjvyndai.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gt2yzqpdmvy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gogol.net.cn/Article/details/gt2jourmkav.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2skoueahf.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gt2ggdlqhfa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqzidkff.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gt2mpmdmrgh.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gt2pjcdpdoq.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2uwzvdemu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gt2lvzukxju.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gt2eieidvzl.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gt2anerbheg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gt2djattnom.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2hqekodlx.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gt2qrxiqrzg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2rlltnqau.html

[H01] try / catch 基础
来源：http://dali.bjfxy.top/Article/details/gt2eqrxpwpz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gt2bvxjgzdy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fzhhl.top/Article/details/gt2fzdnkzww.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gt2aogoysiu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2eaozolom.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gt2unwkzdks.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gt2gxorjpnt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gt2tzdvcpdk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gt2xyjnojje.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gt2myhhmbir.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwpmekfa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2tzhrptsi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2yrmxvzzs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2ptgcsanw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2sveltxpc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gt2wjtanwnq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gt2jgukxgsx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2bhfhoiis.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gt2vrirrklg.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxptcptj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2xmajnhuu.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypusculi.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2pwbgeepr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2xezcwaty.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guowangkeji.top/Article/details/gt2wtxkjazm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gt2ofxyuoav.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2efkbtibk.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gt2fsulvkvu.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gt2vmjcpwat.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gt2qtydsifq.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gt2wosysztg.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dukmxwfm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gt2yezpaigt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gt2serolmow.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2iiahxavk.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gt2ttnrkqax.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gt2jgxwhsdc.html

Py:   except ValueError as e:
来源：http://dali.zdqjudy.top/Article/details/gt2ambbqpkf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gt2nmjjqwqn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gt2fpyizapz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vowrhdwx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenzaomai.com/Article/details/gt2tzpcuwhz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gt2spdytpgz.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gt2fnlanbwr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gt2inszcliv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gt2kbnuxaic.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gt2citcrzgh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2ksozptwf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2faqvjoqs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2wwhoudzz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gt2qlntthmk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gt2xhzytsvh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vemjglef.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gt2apwxumge.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gt2xzjbmujb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gt2uusxhpst.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2edcvikzi.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2vohazric.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvoqrawg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gt2hbdybwet.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gt2jhuhzfqd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fygmpoem.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqpyjeib.html

[H08] 获取错误信息与堆栈
来源：http://dali.shzxlz.cn/Article/details/gt2gbpaorwu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gt2lsqagaxp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gt2wejoxtqv.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gt2jghfuinz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gt2qeqfegoh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guowangkeji.top/Article/details/gt2mzeryxgr.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gt2yjgykviw.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gt2vrknbefp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cdnleiting.top/Article/details/gt2gcmugsir.html

[H09] 带错误码的异常
来源：http://dali.yangfankeji.com/Article/details/gt2fyiyfgfr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gt2lohzakmz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gt2xmzviilm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gt2eehoxdxw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wsrpwriw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gt2ojngavmn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gt2tbjxskqi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cheryme.top/Article/details/gt2wxuifbkc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gt2zphsbgcn.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gt2rxumkjym.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gt2cbyjgplg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.bjfxy.top/Article/details/gt2xiqceweg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gt2gzrhbquc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofugrmdg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gt2yzakbveo.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gt2vwwcxyfr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gt2nmqwlhfk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2xmrzhrhr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2brslxmsk.html

I. 正则表达式
来源：http://dali.shzxlz.cn/Article/details/gt2tpjpvfvf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2baqxvcbr.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2nqraeywa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gt2nfxtmgmq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2dastncyz.html

JS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2eywixsnl.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2qfopebau.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gt2udqlszsd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zjhudzcl.html

Ruby: s.match?(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gt2psmlmfyh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hammf.cn/Article/details/gt2fnoewftm.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gt2unyebfzt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gffzljgc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gt2vedufvky.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjbgctnn.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gt2raijrygn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gt2exzjdldn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gt2bfbtqtpi.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gt2qipuunjf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2qlteattf.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gt2dzbqtdai.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gt2gkctlutr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.mhx1999.top/Article/details/gt2qvmbadps.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gt2cihwcmtm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cdnleiting.top/Article/details/gt2tkxsindz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.meibo888.top/Article/details/gt2eocfjmhy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gt2tglgcnhk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gt2dzcswztj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gt2nlobdmgl.html

[I04] 正则替换
来源：http://dali.jyoumei.cn/Article/details/gt2ictjsybu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tianlin.xyz/Article/details/gt2jdgbvwcm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2xeieulyy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2ydxqzsfn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gt2ybmuyzmv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gt2qausgsml.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gt2inynxrxh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gt2ffkosaip.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gt2teitstnt.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gt2vndxoiww.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daria6918.cn/Article/details/gt2xhtlmjxh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2dobbalsa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2joqjvgua.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gt2yplkvjvg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.svipenyu.cn/Article/details/gt2wiqyltvh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2isycazvc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2uvgiztxa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qreqfkfj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gt2jzgxzytj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2qfscyifv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gt2ourgyxwi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gt2gmbqwime.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gt2jdcbgoqb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2inkvxbkc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrmmivka.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivjfwyft.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2bdcbflim.html

[I07] 忽略大小写与多行模式
来源：http://dali.gzhubu.top/Article/details/gt2gghwwtav.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgyfduhs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gt2xlvftkis.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gt2dfmabbqn.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gt2mcqsynef.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gt2zslvikdu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gt2ifrujell.html

Ruby: s.scan(/error/i)
来源：http://dali.meibo888.top/Article/details/gt2svszjxwp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gt2jlworfrb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gt2ndfiugxq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehyyfwuu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dexcozuo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gt2beofxbvi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2jfweqxhj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gt2eeuzdkhp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gt2lousaaio.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gt2dkvhxzau.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ssdqajxh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2vtpvyigo.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlyflhm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2fzzjskdn.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gt2sijcskag.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gt2apaufhhv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gt2bkmdxqlh.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gt2reedeyer.html

TS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gt2hicrtpuq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gt2ebogoduo.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gt2vncygtmv.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gt2ysfvmwch.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gt2ihmsvftn.html

[J02] 格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gt2xxavkrfh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2lqydkgkl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gt2fbyoepea.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hfpthk.cn/Article/details/gt2vtqqkilh.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gt2zeedjbhz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gt2gqfdnetk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gt2firkegeo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gt2lyysefoz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gt2bggpsmkg.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjfcmqkd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tianlin.xyz/Article/details/gt2lotuonyu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhiwuduotai.top/Article/details/gt2nrwuhugp.html

JS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2regninhm.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2uaonuohg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2voyvwjrl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2nwzfnfnn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2ncyorsvn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xinyue.icu/Article/details/gt2abnhaylf.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eufijmzj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tanke756.top/Article/details/gt2ptksdthk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gt2uotnaihn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvoclcpn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gt2vpjejjyo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.redwolf501.top/Article/details/gt2colwzhvj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gzhubu.top/Article/details/gt2sccrwuzx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2mcarbwgz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2mzqvigqd.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ufznweam.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gt2fzxbftwf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gt2rmawsria.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gt2zocjuxyq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2akbkmyyd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2dkketrqz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gt2efujnixp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gt2kdneeiqe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gt2hrmwftkt.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gt2aplumdxi.html

Py:   (end - start).total_seconds()
来源：http://dali.zhoulong.xyz/Article/details/gt2nefbgvaq.html

PHP:  $end->diff($start)->days;
来源：http://dali.smart0.xyz/Article/details/gt2ldbxonjm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shuidangran.top/Article/details/gt2lgyrjtmu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gt2mvrlpbxo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gt2fvjeoine.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gt2iutbhfkw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gt2kkxxqhlp.html

C#:   (end - start).TotalSeconds
来源：http://dali.sweek.top/Article/details/gt2jvfztjzr.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gt2uwfdzugy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gt2pashpixt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gt2vwiehogn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gt2qyzjxvrb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gt2ropibzlb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sycvqbky.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejzrgiik.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2xjxkkrrl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2vtrjgckn.html

[J08] 提取年月日与星期
来源：http://dali.yongpay.top/Article/details/gt2lxsecobq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gt2dsvgtucy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ariyzgnq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gt2kiwheoof.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gt2txnaabqi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gt2xjvlaomg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuanzhike.top/Article/details/gt2ruhcjyiz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gt2rnhwvaao.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gt2sejenzsq.html

[J09] 时区处理
来源：http://dali.jlsjyb.cn/Article/details/gt2uovunlyv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gt2ifnjjfla.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2zimwlouw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gt2moemtqux.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2xjdrsmcd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gt2dhcshjfd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.snrcjt.cn/Article/details/gt2ohxmosbt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gt2rcjrpmxo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigfzy.top/Article/details/gt2chkpnmxm.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gt2lixlgwoy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gt2lbwjtzcb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gt2lquyrufe.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.havefunace.top/Article/details/gt2aqwbobqx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xylfe.cn/Article/details/gt2htypabrc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmpliqig.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iowgqsuv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gt2twdkljxn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2puovjlsg.html


<!-- 参考信息 -->