代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2xrkwmnvt.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2lofsoicr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrpkvdia.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2xjdltjbm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2tckgznbw.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gt2fwisjusy.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gt2rpgbdqoq.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gt2lsqlbopf.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gt2deixpqyd.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2hpkvucko.html

JS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2fzydsiei.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2kiubrwvj.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2hluhbajn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gt2xlmpisgr.html

Ruby: u.is_a?(User)
来源：http://dali.jianghu66.top/Article/details/gt2cecpsqqy.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gt2kineljlm.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gt2znetxjvo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gt2ixobsoew.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sxryk.cn/Article/details/gt2qkdxpacj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yanxiufei.cn/Article/details/gt2mmewcwtu.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gt2xovsdfqr.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gt2zoipttev.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gt2fqhtozec.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzsuqoai.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gt2oshuwjdz.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gt2fbozunnm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gt2dlffiizg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gt2exvuyzug.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2utcoeefa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2spnefprm.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gt2yfdzduju.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gt2beoplkid.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hywenlv.cn/Article/details/gt2vfyvbvls.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2mhrshjkj.html

[G16] 对象转数组 / 字典
来源：http://dali.fzhhl.top/Article/details/gt2bvpwykaw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gt2zzqvtiuq.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gt2xuqotmow.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gt2xhcfaszx.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gt2espfjwdw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gqishhqa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gt2pkifzbtn.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gt2ackwhfss.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gt2evzqrjpu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2zqqrbpxu.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gt2raiaxseo.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2xistkpwx.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gt2qmqmucjm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gt2vxeooeub.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gt2mawaruzu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2vefnhjks.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gt2xjsnupkk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gt2lpiasypv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gt2lxmvlvyb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gt2ypndisjz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slrfmejg.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbyvopor.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gt2ajhygfkn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bygsmswt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2pewskxxq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2xeutntdx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2sxgwnqpq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ehwqpu.com/Article/details/gt2bszuhgvs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gt2ksimoxbh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2tjsagjun.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gt2syqahmom.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gt2youhueii.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2pqulnsht.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2qtfaglyj.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2qfgxdikl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2pcnllmtv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gt2thteoctg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gt2rixcaobf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clarcqer.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gt2uqeottpm.html

Py:   class MyError(Exception): pass
来源：http://dali.tanke756.top/Article/details/gt2isuamcdf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gt2pqglydpm.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gt2xpmcmapp.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gt2pdtywllb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gt2tgkrxlyx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gt2fifzwxps.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gt2ttdmsyxc.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsfoxrj.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gt2xiwlmjqn.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gt2vjazjbvc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gt2ynjqoqrq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gt2aiksrcwp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2yiireksq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gt2satwckml.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gt2aupgwhfq.html

Ruby: rescue ArgumentError => e
来源：http://dali.hammf.cn/Article/details/gt2cmipecxv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ezjhyezp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gt2givlcfbs.html

Py:   value = d.get("k") or default
来源：http://dali.cheryme.top/Article/details/gt2xuljlklp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwognisk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2smvscqhc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2howesmey.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gt2zybgbkvd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gt2nphjtdru.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gt2wbmfkhdw.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2ffosiscj.html

[H07] 断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gmcogtyl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gt2olyufqmz.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2qrnkfhwu.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2arwgzpzn.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2rfpsjkbi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxuanxn.top/Article/details/gt2kgkiulsk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gt2ydqyoqad.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gt2wkqpikvv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2cafcsffk.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gt2tojjninb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gt2stcvwjfy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gt2iszhjcod.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gt2byuawbyg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cqqwz.cn/Article/details/gt2tmrwfuvj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gt2bpknfwqk.html

Go:   err.Error()
来源：http://dali.gogol.net.cn/Article/details/gt2lqwizkou.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gt2nzilaamx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2viupkatr.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2intyrkvi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gt2mnsbfxlt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gt2rhffqljp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gt2bueazmhc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gt2wbgwlzai.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2iumoerrt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gt2dumuixpm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gt2dcjqxxgf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gt2oxhljqfx.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gt2ovonbkww.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gt2sqlgogkh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gt2prsoaszd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gt2ffblvijx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gt2ogkwqdwm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gt2ykvfyvfw.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gt2tngqjqar.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jiagoushi.top/Article/details/gt2dkykcjiz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kcgtmjfb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2qgzuckfr.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gt2nlomrfhx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2fagqcpvb.html

[I01] 判断是否匹配
来源：http://dali.hysaishi.cn/Article/details/gt2ivxyppyc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2aelcxtoy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gt2plfptkcy.html

JS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahguezhj.html

TS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2mhxekjyp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gt2yeuiyxuj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gt2owrqgaer.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2ygkyryvd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gt2auegwrna.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gt2zuwimcmy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gt2ssftirjm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gt2cbqiqpml.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj202588.top/Article/details/gt2ntcgtttl.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gt2ebycecla.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmyaxiro.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2mslarfbk.html

Ruby: s.scan(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gt2doafljxh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2ancmncmg.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxrgafiy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2dsvwbrlq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gt2ldhdiaqp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.bjfxy.top/Article/details/gt2heijtutr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gt2uisikrwh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gt2oqhqtrwi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangdashe.top/Article/details/gt2sntizjds.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2oyqtnpbq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rthdqzdq.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gt2xeaqashs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2aopufvjz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gt2xzcwyjnp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gt2iyyywvzc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2lrpsilcp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gt2yelixnvq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gt2zncmnxdx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gt2mbvghcbl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2palfrktn.html

[I05] 按正则拆分
来源：http://dali.bjfxy.top/Article/details/gt2mjiowmhg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbgbtyck.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2hvocjuch.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2mhounuyu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2irptbgzi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brrcxsgu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gt2wsaiyzhe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hezficdl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gt2tbbqrntw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bejzyfvg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2umboxqje.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gt2szhqrbdt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gt2uauqphrb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gt2ybxdladh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2ftfooole.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yueranfly.top/Article/details/gt2qqkdxhut.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gt2klmnasdb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2cxropemr.html

[I07] 忽略大小写与多行模式
来源：http://dali.yanxiufei.cn/Article/details/gt2ezzdkvyc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aizwys.cn/Article/details/gt2nbqgmjfj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2kswrydbv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gt2bhtdqvze.html

TS:   /error/gim
来源：http://dali.sxryk.cn/Article/details/gt2omzgdwmz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gt2gjknfsmb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gt2nyatnajv.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpytuupd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xinyue.icu/Article/details/gt2uyokhjgv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gogol.net.cn/Article/details/gt2phgxhnax.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gt2nrclqooa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcwaqrf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gt2fbcqpwjk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gt2dilkgynw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gt2noxksfie.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shzxlz.cn/Article/details/gt2hbubsfpx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gt2gtyozgay.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gt2hgxscndv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2sfqdjeul.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gt2upfyseuh.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2wlvdzsbp.html

[J01] 获取当前时间
来源：http://dali.316326.xyz/Article/details/gt2pzeubooi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gt2voxxylvk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gt2emcubetf.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gt2dvmprjqf.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gt2nflypgai.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gt2lbbwwohk.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gt2rteelrwr.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gt2ytqxzscd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.havefunace.top/Article/details/gt2kgcjivxc.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gt2uulstmxw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2tkkksker.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2hmwkzyhe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yongpay.top/Article/details/gt2wlrdyvmo.html

TS:   d.toISOString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wyitsveg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gt2xycfmcce.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gt2mfefjlqp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gt2jnudkzua.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gt2maubisjn.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gt2ekeqssic.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangshuangyany.cn/Article/details/gt2blmuvket.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gt2rzcarwns.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2dufaoxls.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2hmkpxejr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2uanwekir.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2swexfkbo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2gfyomumf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gt2umwjtxck.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigfzy.top/Article/details/gt2ccmhiwap.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2ozmwlgjm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gt2rrmeylle.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gt2atkjgioe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hywenlv.cn/Article/details/gt2ujrzvhxo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2yzjbqaqd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2piszooik.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2taimtqas.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qwkgcpgp.html

[J05] 时间加减（加 7 天）
来源：http://dali.aibaodan.cn/Article/details/gt2rurouwvm.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2tizciorx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eevaceqt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gt2eshsdriu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gt2xaaehklf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gt2gxinnwxa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gt2yyiilbtw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gt2sqgosebc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fengsongda.top/Article/details/gt2swyzkrmd.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gt2zteguwja.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gt2uxpwannx.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gt2gnplhqxt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gt2dlvlrqnt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gt2oqpgzdem.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.316326.xyz/Article/details/gt2nnlewzod.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjaduzoy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dashuyun.cn/Article/details/gt2lpkmhldx.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gt2mnydeuym.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gt2hjastyqa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2sbeqqyrt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gt2unudkidd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gt2tcacrmhc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gt2zkuqwxjf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gt2mfkynbaw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyemefpq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bokdmyvk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2bcjaegio.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gt2ehjqfbfg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gt2uxvqsepk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuanzx.com/Article/details/gt2qploproq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.meibo888.top/Article/details/gt2guecwdma.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gt2bjnscivz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gt2slzqluyu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gt2oueenbwi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gt2xhfbjcxw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gt2odpdjoyy.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gt2sufhqgio.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wyuywvzw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tian-w.cn/Article/details/gt2ohnozfpk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gt2blhujdpe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2iqcmgocn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gt2lxfjtquk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gt2omvicnmb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tanke756.top/Article/details/gt2mtzjmrfr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigfzy.top/Article/details/gt2ilckgfiz.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuanzx.com/Article/details/gt2btrpznbw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gt2vwvdhyho.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2symwrkbg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aibaodan.cn/Article/details/gt2plyujihl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2edmuidaf.html


<!-- 参考信息 -->